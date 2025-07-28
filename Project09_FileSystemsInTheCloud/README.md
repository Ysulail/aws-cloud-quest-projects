# Project09 File Systems In The Cloud

## 📌 Project Overview
In this project, I helped a growing pet service company centralize their media storage by setting up a scalable and shared file system using **Amazon Elastic File System (EFS)**. The goal was to enable consistent access to pet client photos from multiple branches, eliminate storage limitations, and enforce file-level permissions across teams.


## 🚀 Key Features & Services
- **Amazon EFS** to provide scalable, shared file storage across branches.  
- **Mount Targets** to connect EC2 instances in different Availability Zones.  
- **Multi-AZ Redundancy** for high availability and data durability.  
- **File-level Permissions** to restrict access for VIP client folders.

## 🖥️ Application in Action
![EFS Setup](p9-1.png)

## 📊  Lessons Learned
- Amazon EFS simplifies file sharing between distributed systems without provisioning storage.  
- Built-in redundancy across AZs increases resilience and reduces risk of data loss.  
- File-level permissions enable secure access control tailored to organizational needs.  
- Mount targets ensure that compute resources in all AZs can access the same file system.
