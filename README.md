# Simple Web Service

Basic setup to deploy a web app using Docker, GitHub Actions, and Terraform on AWS

## What this does

- Basic web app **can be developed to something better in the future**
- Dockerfile + Makefile
- CI/CD: GitHub Actions builds + pushes to Docker Hub
- Terraform creates an EC2 instance and runs the app

## Requirements

- AWS account (free tier)
- Terraform installed

## Docker

```bash
make build   # builds the image
make run     # runs the container
make push    # pushes to Docker Hub
