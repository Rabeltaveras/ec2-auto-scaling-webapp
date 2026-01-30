# EC2 Auto Scaling Web Application

## Overview
This project demonstrates a highly available web application deployed on AWS using an Application Load Balancer and an EC2 Auto Scaling Group across multiple Availability Zones.

## Architecture
Client → ALB → Target Group → EC2 Auto Scaling Group

## Key Features
- Multi-AZ Application Load Balancer
- EC2 Auto Scaling Group (min 2, max 4)
- CPU-based scaling using CloudWatch
- Secure networking using security groups

## Validation
- Target group shows healthy instances
- Load balanced traffic across instances
- Auto Scaling successfully launches new instances

## Future Improvements
- Convert to Infrastructure as Code
- Add HTTPS using ACM
- Add CI/CD pipeline
