## 2. Configure Auto Scaling and Load Balancing

### Objective:
Set up Auto Scaling Group and Load Balancer.

### Steps:

#### a) Create Auto Scaling Group
1. Create Launch Template.
2. Use Amazon Linux 2 AMI.
3. Create Auto Scaling Group.

#### b) Configure Scaling Policies
- Scale up when CPU > 70%
- Scale down when CPU < 30%

#### c) Deploy Application Load Balancer
1. Create ALB.
2. Add target group.
3. Register EC2 instances.

#### d) Test Auto Scaling
1. Generate high CPU load.
2. Observe new instances launched automatically.

### Result:
Successfully configured Auto Scaling and Load Balancer.

---

<img width="1918" height="963" alt="1" src="https://github.com/user-attachments/assets/d4af6410-4eba-42bf-98da-8fe977ee7f2b" />
<img width="1918" height="968" alt="2" src="https://github.com/user-attachments/assets/122e86de-b401-497a-9984-30efddaa1a3f" />
<img width="1918" height="967" alt="3" src="https://github.com/user-attachments/assets/95fb029a-7526-4e32-a94b-1c364d19434b" />
