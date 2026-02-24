# Cloud Infrastructure

This document covers the basics of deploying and managing resources on AWS (Amazon Web Services).

## EC2 Instances (Elastic Compute Cloud)

Instance Type: Selecting the hardware capacity (e.g., t3.medium for the final project).

AMI (Amazon Machine Image): The operating system template (e.g., RedHat OS).

Public IP: The address used to access the instance over the internet.

## Security Groups

Acts as a virtual firewall for the instance.

## Inbound Rules:

SSH (Port 22): For remote terminal access.

HTTP (Port 80): For web traffic.

Custom (Port 8080): Common for development or Docker containers.

## Key Pairs

.pem or .ppk files used for authentication.

Must be kept secure and never uploaded to public repositories.