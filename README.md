
# End-to-End AWS Cloud Engineering Project: VPC, EC2, RDS, IaC & Monitoring

##  Overview

This project demonstrates my hands-on experience in designing, deploying, and managing AWS cloud infrastructure.
I built a secure and scalable environment using **VPC, EC2, RDS, IAM, CloudFormation, and CloudWatch**, simulating a real-world cloud engineering workflow.

The project highlights skills in:

* Cloud Infrastructure Deployment (VPC, EC2, RDS)
* Infrastructure as Code (CloudFormation)
* Monitoring & Logging (CloudWatch, CloudTrail)
* Security (IAM, Security Groups, SSL/TLS)
* Automation & Cost Optimization

---

##  Architecture Diagram

<img width="1881" height="659" alt="architecture" src="https://github.com/user-attachments/assets/655b3048-a5f2-4ed5-8c3d-6103dc224393" />

![Architecture Diagram](01-vpc-ec2-rds/diagram.png)

---

##  Project Steps

 1️ VPC & EC2 Deployment

* Created a **custom VPC** with public/private subnets, route tables, and NAT gateway.
* Launched EC2 instances in the public subnet for web servers.
* Configured security groups and IAM roles.

📷 Example:
<img width="1871" height="615" alt="EC2 in running state" src="https://github.com/user-attachments/assets/3a62d786-f2e0-4b95-ac82-24469d930a78" />
<img width="990" height="523" alt="hello from PT" src="https://github.com/user-attachments/assets/6c71eeca-ddbd-4208-8de7-978564a8fd29" />

```md
![EC2 & VPC Deployment Screenshot](01-vpc-ec2-rds/ec2.png)
```

---

2 RDS Database Setup

* Deployed a **MySQL RDS instance** inside private subnet.
* Configured parameter groups, subnet groups, and security groups.
* Ensured encryption and backups were enabled.

📷 Example:
![RDS Database Created](01-vpc-ec2-rds/db created.png)
<img width="1884" height="940" alt="db created" src="https://github.com/user-attachments/assets/c315cce4-8a42-48e9-a4d0-c50c8bd5d1f0" />

---

3  Infrastructure as Code (IaC) with CloudFormation

* Created **CloudFormation templates** to automate deployment of EC2, Security Groups, and VPC.
* Validated deployment and reviewed **stack events**.

📷 Examples:
![CloudFormation Stack Complete](03-iac/IAC_cloud Formation.png)
![CloudFormation Events](03-iac/IAC_Cloud formation_events.png)
<img width="1433" height="483" alt="IAC_cloud Formation" src="https://github.com/user-attachments/assets/0d764024-1ced-46e0-9ec1-e4d51f5b5f0f" />
<img width="1886" height="771" alt="IAC_Cloud formation_events" src="https://github.com/user-attachments/assets/408868c9-47d7-4745-b730-ce174f99286b" />

---

### 4️⃣ Monitoring & Logging

* Enabled **CloudWatch metrics and alarms** for EC2 and RDS.
* Configured **CloudTrail** to track API activity.
* Created **KPI dashboards** to visualize performance.
<img width="1897" height="510" alt="image" src="https://github.com/user-attachments/assets/7886102f-cf69-43bf-b9df-8c32877ff692" />

---

## 📊 Key Learnings

* Gained practical experience in **building secure AWS infrastructure**.
* Learned how to apply **IaC for repeatable deployments**.
* Practiced **monitoring and cost-optimization techniques**.
* Strengthened knowledge of **VPC networking, RDS security, and IAM principles**.

---<img width="1153" height="645" alt="metrics Dashboard exceed set alarm" src="https://github.com/user-attachments/assets/0ff57502-90e2-4d1c-89c7-1e721b83631e" />
<img width="1909" height="583" alt="budget" src="https://github.com/user-attachments/assets/759ee6f0-5e84-4ed7-b15e-0ebce455088b" />
<img width="1226" height="478" alt="SNS Notification" src="https://github.com/user-attachments/assets/71a783d3-ef3e-4374-9c48-1c7025747673" />
<img width="833" height="424" alt="SNS Sub confirmed" src="https://github.com/user-attachments/assets/15531f7d-831f-496a-a72a-06b18064ec83" />
<img width="1885" height="857" alt="trusted advisor report" src="https://github.com/user-attachments/assets/6641f012-c9eb-4637-b506-58d8f82329db" />


## 🚀 Next Steps

* Add **Terraform** templates for multi-cloud comparison.
* Deploy a containerized app using **ECS/EKS**.
* Integrate with **CI/CD pipeline (CodePipeline/CodeBuild)**.

---

