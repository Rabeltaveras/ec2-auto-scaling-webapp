# EC2 Auto Scaling Web Application

## Overview
This project demonstrates a highly available web application deployed on AWS using an Application Load Balancer and an EC2 Auto Scaling Group across multiple Availability Zones.

## Architecture
Client → ALB → Target Group → EC2 Auto Scaling Group

## Key Features
- Multi-AZ Application Load Balancer
- EC2 Auto Scaling Group (min 2, max 4)
- CPU-based scaling using CloudWatch
- Load balanced traffic across instances
- Auto Scaling successfully launches new instances


<img width="1913" height="866" alt="New Screenshot" src="https://github.com/user-attachments/assets/f3361aa9-ae25-4fc8-a418-caa2ef4f6a7e" />

<img width="1920" height="1080" alt="Screenshot From 2026-01-28 12-03-05" src="https://github.com/user-attachments/assets/76892dc3-37a7-44c3-b3a0-387472599996" />

<img width="1920" height="1080" alt="Screenshot From 2026-01-28 12-03-16" src="https://github.com/user-attachments/assets/430f0123-9290-4175-bb61-9f558a557f4b" />

<img width="1920" height="1080" alt="Screenshot From 2026-01-28 12-03-22" src="https://github.com/user-attachments/assets/dc07615f-3bd6-4bd4-ab67-ec0e21b9d0cd" />


## Future Improvements
- Secure networking using security groups

## Validation
- Target group shows healthy instances
- Convert to Infrastructure as Code
- Add HTTPS using ACM
- Add CI/CD pipeline
