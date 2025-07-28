# Project10 Auto Healing And Scaling

## 📌 Project Overview
In this project, I helped a gaming café automate the provisioning and recovery of their EC2-based game servers using **Amazon EC2 Auto Scaling**—a service that automatically adjusts capacity to maintain steady performance and minimize cost. The goal was to replace crashed instances automatically, enforce daily instance limits, and prepare servers ahead of peak gaming events through scheduled scaling.

## 🚀 Key Features & Services
- **Amazon EC2 Auto Scaling Group**: Automatically replaces failed EC2 instances to maintain desired capacity.
- **Launch Template**: Used to define instance configuration for consistent deployments.
- **Target Tracking Scaling Policy**: Scales in/out based on average CPU utilization.
- **CloudWatch Alarms** to trigger scaling actions based on usage thresholds.

## 🖥️ Application in Action
![Alarm Graph](p10-1.png)

## 📊 Lessons Learned
- **Auto Scaling Groups** helped ensure server availability by automatically launching replacement instances when failures occurred.
- **Launch Templates** simplified the reuse of server configurations across scaling events.
- **CloudWatch Alarms** played a key role in monitoring CPU usage to trigger scaling policies dynamically.
