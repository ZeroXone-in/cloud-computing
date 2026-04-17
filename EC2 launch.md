# AWS Cloud Computing Practicals

## Practical 1: Launch Your First Amazon EC2 Instance

### Objective
To deploy a virtual machine on AWS using Amazon EC2 service.

### Requirements
- AWS Account  
- Internet Connection  
- SSH Client (PuTTY / Terminal)

### Steps Performed

#### a) Launch an EC2 Instance from AWS Management Console
1. Logged in to AWS Management Console.
2. Searched for **EC2** service.
3. Clicked on **Launch Instance**.
4. Entered instance name as **MyFirstEC2**.

#### b) Use a Pre-configured AMI
1. Selected **Amazon Linux 2 AMI**.
2. Chose **t2.micro** instance type (Free Tier eligible).

#### c) Configure Security Groups
1. Created a new security group.
2. Allowed **SSH (Port 22)** from Anywhere (0.0.0.0/0).

#### d) Connect to Instance using SSH
1. Downloaded key pair (.pem file).
2. Opened terminal.
3. Connected using command:

```bash
ssh -i mykey.pem ec2-user@<Public-IP>
```
<img width="1918" height="927" alt="1" src="https://github.com/user-attachments/assets/9db0be45-d536-4ad7-b239-a97a2cf44b40" />
<img width="1917" height="921" alt="2" src="https://github.com/user-attachments/assets/1acbfa99-95c6-4635-82a8-9f3b8a7f4d61" />
<img width="1918" height="966" alt="3" src="https://github.com/user-attachments/assets/cb6ee388-b519-4a52-bb8a-5c6099bde215" />
<img width="1918" height="970" alt="4" src="https://github.com/user-attachments/assets/bb78c346-2af2-4211-ac85-615d7c2d84b4" />
<img width="1918" height="967" alt="5" src="https://github.com/user-attachments/assets/a16deb9c-1196-4148-b6bd-395de467bb93" />
<img width="1918" height="1078" alt="6" src="https://github.com/user-attachments/assets/f066e1ae-80e3-42f7-b5b4-ce0edb5783b8" />

