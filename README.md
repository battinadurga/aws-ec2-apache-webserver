# aws-ec2-apache-webserver
Apache web server deployed on AWS EC2 using IAM, AWS CLI, and SSH.
# AWS EC2 Apache Web Server

## Overview
This project shows how I deployed an Apache web server on an AWS EC2 instance. I connected to the server using SSH and managed AWS using an IAM user and the AWS CLI.

## Tools Used
- AWS EC2
- AWS IAM
- AWS CLI
- SSH
- Apache HTTP Server
- Linux

## Steps
1. Created an IAM user and configured the AWS CLI.
2. Launched an EC2 Linux instance.
3. Opened ports 22 (SSH) and 80 (HTTP) in the security group.
4. Connected to the instance using SSH.
5. Installed and started the Apache web server.
6. Opened the public IP in the browser to check the web page.

## Screenshots
![Apache page](apache-page.png)

## What I Learned
- Launching and managing EC2 instances
- Using IAM users and the AWS CLI
- Connecting to a server with SSH
- Installing and running a web server on Linux
