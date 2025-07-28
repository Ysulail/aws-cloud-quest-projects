# Project05 Networking Concepts

## 📌 Project Overview
In this project, I helped a banking organization resolve network connectivity issues after migrating to the cloud.  
The goal was to enable internet access for EC2 instances and ensure secure connectivity between the web server and database.

## 🚀 Key Features & Services
- **Amazon VPC**: Used to isolate network infrastructure and define IP ranges for both public and private subnets.
- **Internet Gateway (IGW)**: Attached to the VPC and linked through the route table to enable outbound traffic to the internet.
- **Routing Tables**: Updated to allow traffic from the public subnet to route through the IGW.
- **Security Groups**:
  - Allowed the web server to connect to the database on port **3306**.
  - Added rule to allow outbound internet access from EC2 instances.

## 🖥️ Application in Action
![Security Group](p5-1.png)
![Security Group](p5-2.png)

## 📊 Lessons Learned
- Proper configuration of route tables and internet gateways is essential for enabling internet access in AWS VPCs.
- Security groups must be correctly scoped to allow communication between services without overexposing resources.
- AWS VPC offers fine-grained control to separate public-facing and internal services securely.
