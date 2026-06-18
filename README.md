AWS CloudWatch Monitoring & SNS Alerting Project

Project Overview

This project demonstrates monitoring and alerting using Amazon CloudWatch and Amazon SNS.

When CPU utilization exceeds the configured threshold, CloudWatch triggers an alarm and Amazon SNS sends an email notification to the administrator.

Architecture

EC2 Instance

↓

CloudWatch Metrics

↓

CloudWatch Alarm

↓

SNS Topic

↓

Email Notification

AWS Services Used

- Amazon EC2
- Amazon CloudWatch
- Amazon SNS
- Ubuntu Linux
- Apache Web Server

Implementation Steps

EC2 Setup

- Launched Ubuntu EC2 Instance
- Installed Apache Web Server
- Hosted Monitoring Web Page

SNS Configuration

- Created SNS Topic
- Created Email Subscription
- Confirmed Subscription Successfully

CloudWatch Alarm Setup

- Selected CPUUtilization Metric
- Created CloudWatch Alarm
- Connected Alarm with SNS Topic

Alert Testing

- Generated CPU Load Using Stress Tool
- Triggered CloudWatch Alarm
- Received Email Alert Successfully

Screenshots

EC2 Instance Running

"EC2" (./ec2-running.png)

Monitoring Web Page

"Web" (./web-page.png)

SNS Topic Created

"SNS" (./sns-topic.png)

Email Subscription Confirmed

"Subscription" (./email-subscription-confirmed.png)

CloudWatch Alarm Created

"Alarm" (./cloudwatch-alarm-created.png)

CPU Stress Test

"Stress" (./cpu-stress-test.png)

Email Alert Received

"Email Alert" (./email-alert-received.png)

Skills Demonstrated

- Amazon EC2 Administration
- Amazon CloudWatch Monitoring
- Amazon SNS Notifications
- Monitoring and Alerting
- Linux Administration
- Apache Web Server
- AWS Operations
- Troubleshooting

Project Outcome

Successfully implemented a monitoring and alerting solution using Amazon CloudWatch and Amazon SNS. The system automatically detects high CPU utilization and sends email notifications to administrators. notifications to administrators.
