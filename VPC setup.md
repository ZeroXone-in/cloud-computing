# AWS Cloud Practical File

## 1. Set Up a VPC

### Objective:
Create and configure a Virtual Private Cloud (VPC).

### Steps:

#### a) Create Custom VPC
- CIDR Block: `10.0.0.0/16`

Create Subnets:
- Public Subnet: `10.0.1.0/24`
- Private Subnet: `10.0.2.0/24`

#### b) Launch EC2 Instances
- One instance in Public Subnet.
- One instance in Private Subnet.

#### c) Configure Internet Gateway
1. Create Internet Gateway.
2. Attach to VPC.
3. Update route table for public subnet.

#### d) Configure NAT Gateway
1. Create NAT Gateway in Public Subnet.
2. Associate Elastic IP.
3. Update private route table.

### Result:
Successfully created VPC with public and private subnet.

---

<img width="1918" height="966" alt="1" src="https://github.com/user-attachments/assets/e9022a7f-ac51-48f5-8b40-52b7bb5b509b" />
<img width="1918" height="966" alt="2" src="https://github.com/user-attachments/assets/97b87f8b-2d08-4037-bb98-be5d7fb84f55" />
<img width="1918" height="967" alt="3" src="https://github.com/user-attachments/assets/d83d9e28-f303-4d91-90e7-97f84db3f23d" />
<img width="1918" height="970" alt="4" src="https://github.com/user-attachments/assets/dfa44d1c-af69-42a6-9b3d-d810af01d3c9" />
<img width="1918" height="967" alt="5" src="https://github.com/user-attachments/assets/4fb104fd-0c07-4b92-92f6-38dbee7fa262" />
<img width="1918" height="970" alt="6" src="https://github.com/user-attachments/assets/8200d2c4-781a-4323-b875-6424ef8619f4" />
<img width="1918" height="971" alt="7" src="https://github.com/user-attachments/assets/c05c97ab-e042-4dd9-b4c4-b081fef67460" />
<img width="1918" height="972" alt="8" src="https://github.com/user-attachments/assets/7e81875c-b537-4b3e-895a-b36a3bb3c4d1" />
<img width="1918" height="970" alt="9" src="https://github.com/user-attachments/assets/3f895ec3-9f8a-476c-84dd-df02e883dd4f" />
<img width="1918" height="963" alt="10" src="https://github.com/user-attachments/assets/05fc37c1-3627-4c4f-87b5-5bcaf5a90d84" />
<img width="1918" height="966" alt="11" src="https://github.com/user-attachments/assets/0a3a835c-74a4-432c-86e5-d91e113995b7" />
<img width="1918" height="966" alt="12" src="https://github.com/user-attachments/assets/87815ad4-9fc1-42bf-bcd6-ed2b7572f279" />
