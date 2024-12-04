# CloudFormation GitSync Infrastructure

This repository contains AWS CloudFormation templates for deploying a 3-tier architecture using CloudFormation Git sync.

## Architecture Overview
- VPC with public and private subnets across 2 AZs
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG) with EC2 instances
- IAM roles and security groups
- S3 bucket for application assets

## Environment Configuration
- Development: dev/stack-config.yaml
- Production: prod/stack-config.yaml

## Directory Structure

