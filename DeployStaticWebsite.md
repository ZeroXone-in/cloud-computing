# AWS Cloud Practical File

## Deploying a Static Website on the Cloud

### Objective:
Host a static website using cloud storage services.

### Platform Used:
AWS S3

### Requirements:
- AWS Account  
- Static website files (`index.html`, `style.css`, images)

### Steps:

#### a) Deploy a Static Website using AWS S3

1. Login to AWS Management Console.
2. Open **Amazon S3** service.
3. Click **Create Bucket**.
4. Enter bucket name (must be unique).
5. Select region.
6. Disable **Block Public Access** settings.
7. Create the bucket.

#### Upload Website Files

1. Open created bucket.
2. Click **Upload**.
3. Upload files:
   - `index.html`
   - `style.css`
   - Images / assets

#### Enable Static Website Hosting

1. Go to **Properties** tab.
2. Scroll to **Static Website Hosting**.
3. Click **Enable**.
4. Set:
   - Index document: `index.html`
   - Error document: `error.html` (optional)

#### b) Configure Permissions and Enable Public Access

1. Open **Permissions** tab.
2. Add Bucket Policy:

```json
{
  "Version":"2012-10-17",
  "Statement":[{
    "Sid":"PublicReadGetObject",
    "Effect":"Allow",
    "Principal":"*",
    "Action":["s3:GetObject"],
    "Resource":["arn:aws:s3:::your-bucket-name/*"]
  }]
}
```
<img width="1918" height="967" alt="1" src="https://github.com/user-attachments/assets/23f80a75-9775-4eda-8037-46505c2525c0" />

