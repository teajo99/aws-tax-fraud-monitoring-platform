Architecture Diagram
![image alt](https://github.com/teajo99/aws-hmrc-fraud-intelligence-platform/blob/ffa287577216672c54730955b8ae599b02b90565/aws-hmrc-fraud-intelligence-platform/Architecture%20Diagram.png)

Architecture diagram of a cloud-based fraud intelligence system deployed on AWS EC2. The system follows a multi-layer web architecture where user requests are routed through an NGINX reverse proxy running on a Linux EC2 instance. Requests are forwarded to a Flask-based REST API that processes fraud detection logic and returns JSON responses. The system includes a frontend dashboard for visualization and demonstrates secure network configuration using AWS VPC and security groups.

## Cloud-Based Fraud Intelligence System
## Overview
This project implements a cloud-hosted multi-tier fraud intelligence system deployed on AWS EC2, designed to simulate a real-time risk evaluation and monitoring platform.
The system demonstrates a traditional web application architecture deployed in a cloud environment using Linux server management, reverse proxy configuration, and REST API design principles.

## Business Problem
Financial and risk systems require:
Real-time fraud detection
Fast API-based decision systems
Secure deployment environments
Scalable backend services
Separation of web and application layers
This system simulates a production-grade fraud monitoring service.
## AWS Architecture
Amazon EC2 used for full application hosting
Amazon VPC provides network isolation
Security Groups control HTTP and API access
Linux OS used for system-level deployment and configuration
## System Architecture
NGINX handles incoming HTTP traffic (reverse proxy layer)
Flask API processes fraud detection logic
Rule-based fraud engine evaluates risk scores
Dashboard UI displays results to users
## Key Features
Multi-layer web architecture (NGINX + Flask + UI)
REST API-based fraud detection system
Reverse proxy configuration for request routing
Cloud-based Linux server deployment
Real-time JSON response generation
Secure port and network configuration
## Technical Skills Demonstrated
AWS EC2 deployment and management
Linux system administration
NGINX reverse proxy configuration
Flask REST API development
Networking (ports, routing, security groups)
Debugging cloud deployment issues
Full-stack cloud application deployment
## Architecture Decisions
NGINX used to separate web traffic from backend logic
Flask chosen for lightweight and fast API processing
EC2 used for full control of infrastructure and OS-level configuration
Port separation (80/5000) simulates real production architecture patterns
Stateless API design allows future scalability improvements
## Challenges & Solutions
Configured AWS security groups for controlled access
Resolved NGINX service and routing issues
Debugged Flask port binding and connectivity issues
Verified communication between proxy and backend API
Managed Linux-level deployment and service monitoring
## What This Project Demonstrates
Real cloud deployment experience (not simulated AWS services)
Multi-tier application architecture design
System-level troubleshooting in production-like environment
Understanding of web traffic routing and backend design
End-to-end application deployment lifecycle
