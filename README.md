# AWS Web Application Hosting

## Project Overview

This project demonstrates the deployment of a basic cloud-hosted web application environment using Amazon Web Services (AWS).

The infrastructure includes networking, compute, security, and storage components required to host and access a web application.

## AWS Services Used

- Amazon VPC
- Internet Gateway
- Security Groups
- Amazon EC2
- Amazon S3

## Architecture

Internet
   |
Internet Gateway
   |
Amazon VPC
   |
Security Group
   |
Amazon EC2
   |
Web Application

Amazon S3
   |
Object Storage

## Project Implementation

### 1. Amazon VPC

Created a Virtual Private Cloud (VPC) to provide an isolated network environment for the application.

### 2. Internet Gateway

Attached an Internet Gateway to enable internet connectivity for resources in the VPC.

### 3. Security Groups

Configured Security Group rules to control inbound traffic for:

- HTTP
- SSH

### 4. Amazon EC2

Launched an Amazon EC2 instance to host the web application.

Configured the Linux server and managed the web service using Apache HTTP Server.

### 5. Amazon S3

Created an Amazon S3 bucket and uploaded objects for storage.

## Skills Demonstrated

- AWS Cloud Infrastructure
- Amazon EC2
- Amazon VPC
- Amazon S3
- Linux
- Networking
- Security Groups
- Apache HTTP Server

## Troubleshooting

The project includes troubleshooting for common issues related to:

- EC2 connectivity
- Security Group configuration
- Internet access
- Web server service status
- S3 access

## Project Outcome

Successfully deployed and documented a basic AWS web application hosting environment using VPC, EC2, S3, Internet Gateway, Security Groups, and Apache HTTP Server.

## Documentation

Detailed project documentation and configuration screenshots will be available in this repository.
