# Project05 Networking Concepts

## 📌 Project Overview
After migrating services to the cloud, the EC2 instances couldn’t access the internet, and there were issues connecting to the database. This project aimed to fix connectivity problems by updating the VPC settings.

## 🚀 Key Features & Services
- **Amazon VPC** for networking.
- **Security Groups** for traffic control.

## 🖥️ Application in Action
![Security Group](p5-1.png)
![Security Group](p5-2.png)

## 📊 Lessons Learned
- Configured an Internet Gateway and attached it to the VPC to enable internet access.  
- Updated route tables to direct traffic from the public subnet to the Internet Gateway.  
- Defined security group rules to allow traffic between the web server and the database.
