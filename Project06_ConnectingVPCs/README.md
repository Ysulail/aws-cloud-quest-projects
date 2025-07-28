# Project06 Connecting VPCs

## 📌 Project Overview
This project solves the issue of communication between isolated department VPCs (Marketing, Development, Finance) by implementing **VPC Peering**.  
The goal was to allow Marketing and Developer EC2 instances to access Financial reports hosted in a separate VPC.

## 🚀 Key Features & Services
- **Amazon VPC** – For creating isolated networks for each department.  
- **VPC Peering** – To enable secure traffic flow between Marketing/Development and Finance VPCs.  
- **Route Tables** – To update routing rules for cross-VPC communication.  
- **Private IP Addressing** – Communication done securely without going over the public internet.

## 🖥️ Application in Action
![VPC Peering](p6-1.png)
![VPC Peering](p6-2.png)
![VPC Peering](p6-3.png)

## 📊 Lessons Learned
- VPC Peering is a simple yet powerful way to enable inter-department communication.  
- Peering is **non-transitive**, so each VPC must be peered directly to any other it needs access to.  
- Route table updates are mandatory after peering – without them, traffic won’t flow.  
- AWS enforces CIDR block uniqueness between peered VPCs to avoid conflicts.
