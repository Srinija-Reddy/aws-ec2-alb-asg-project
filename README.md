# AWS EC2 + ALB + ASG Auto-Scaling Project

## 🚀 Project Overview
In this project, I configured a highly available, scalable environment on AWS by setting up an EC2 Launch Template, an Application Load Balancer (ALB), and an Auto Scaling Group (ASG). The goal was to demonstrate cloud architecture deployment, scaling, load balancing, and resource optimization, all while staying within AWS Free Tier limits.

## 🔧 Steps Completed
- Created a Launch Template for EC2 instances with Apache Web Server installed (via User Data).
- Set up a Target Group to manage instance registration and health checks.
- Deployed an Application Load Balancer (ALB) with HTTP listener and forwarding rules.
- Configured an Auto Scaling Group (ASG) attached to the ALB for dynamic scaling.
- Validated live access via ALB DNS and ensured fault-tolerant architecture.
- Performed full cleanup after validation, including:
  - Deregistering AMIs
  - Deleting Snapshots, Volumes, and Elastic IPs
  - Deleting Load Balancer, Auto Scaling Group, and Launch Template
  - Ensuring Free Tier optimization

## 📸 Project Screenshots
- EC2 Instance created and running Apache
- ALB setup and Listener forwarding configured
- Target Group health checks successful
- Auto Scaling Group created and EC2 automatically launched
- Final cleanup confirmation (AWS dashboard with zero running resources)


## 🛡️ Skills Demonstrated
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Elastic IP Management
- Amazon Machine Images (AMI) and Snapshots
- VPC Networking (Security Groups, Network Interfaces)
- AWS Cost Optimization and Resource Management

## 📚 Key Takeaways
- Deep hands-on experience in setting up scalable cloud infrastructure.
- Real-world troubleshooting across network, security, and service boundaries.
- Professional-level AWS cleanup and Free Tier management.

---
