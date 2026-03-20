# Cloud Monitoring using AWS CloudWatch

## Overview
This project demonstrates how to set up monitoring and alerting for a cloud-based application using AWS CloudWatch. The system tracks resource usage and sends notifications when thresholds are exceeded.

## Platform
AWS (Amazon Web Services)

## Services Used
- Amazon EC2 (Virtual Machine)
- AWS CloudWatch (Metrics, Alarms, Dashboards)
- AWS SNS (Email Notifications)

## Objective
- Monitor CPU Utilization
- Trigger alerts when CPU usage exceeds 50%
- Create a dashboard to visualize:
  - CPU Utilization
  - Network In/Out
  - Disk Read/Write Operations

## Implementation Steps
1. Launched an EC2 instance (t2.micro)
2. Opened CloudWatch service in AWS Console
3. Created a custom monitoring dashboard
4. Added metrics:
   - CPUUtilization
   - NetworkIn
   - DiskReadOps / DiskWriteOps
5. Configured an alarm:
   - Metric: CPUUtilization
   - Threshold: > 50%
6. Set up SNS topic for email notifications
7. Tested alert by generating load on EC2 instance

## Results
- Successfully configured monitoring dashboard
- Alerts triggered when CPU usage exceeded threshold
- Email notifications received via SNS

## Screenshots
- Dashboard View
- Alarm Configuration
- Metrics Overview
- SNS Setup
- Email Notification

## Learnings
- Gained practical experience with AWS CloudWatch
- Understood monitoring and alerting mechanisms in cloud
- Learned how to integrate SNS for real-time notifications

