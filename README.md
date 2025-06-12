Simple Web Service
A basic web application that can serve as a starting point for future development and expansion.

**📋 Prerequisites

An AWS account (free tier is sufficient)

Terraform installed

AWS CLI installed and configured (aws configure)

**🚀 Deployment Instructions

1. Download the Terraform file
Navigate to:
Part 3 Infrastructure as Code/main.tf
and download the main.tf file to your local machine.

2. Authenticate with AWS
Ensure the AWS CLI is configured and logged in to your account
3. Initialize and Apply Terraform
Open Command Prompt or PowerShell in the directory containing main.tf.

Run the following commands:
terraform init
terraform plan
terraform apply
(Type yes when prompted)

4. Retrieve the Public IP
After Terraform finishes applying, you will see the EC2 instance's public IP address in the output.

🌐 Accessing the Web App
Open your browser or use curl to access the web app (http://<PUBLIC_IP>) ensure using http instead of https as the web is hosted on port 80


