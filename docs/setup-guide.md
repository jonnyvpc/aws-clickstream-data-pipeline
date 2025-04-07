# Setup Guide

## Prerequisites
- AWS Account with appropriate permissions
- AWS CLI installed and configured
- Basic understanding of AWS services (EC2, CloudWatch, S3)

## Initial Setup

### 1. IAM Role Configuration
1. Create an IAM role for EC2 instances
2. Attach the following policies:
   - CloudWatchLogsFullAccess
   - AmazonS3FullAccess
   - AWSCloud9Environment

### 2. S3 Bucket Setup
```bash
# Create S3 bucket for clickstream data
aws s3 mb s3://your-cafe-clickstream-bucket
```

### 3. EC2 Instance Setup
1. Launch EC2 instance using Amazon Linux 2
2. Attach the IAM role created in step 1
3. Configure security groups to allow necessary traffic

### 4. CloudWatch Setup
1. Create log groups for application logs
2. Set up metrics and alarms
3. Configure dashboards using provided templates

## Configuration Files
All necessary configuration files are available in the `src` directory:
- CloudWatch dashboard templates
- IAM role policies
- Setup scripts

## Verification Steps
1. Verify EC2 instance is sending logs to CloudWatch
2. Confirm S3 bucket is receiving clickstream data
3. Test dashboard accessibility and data visualization

## Troubleshooting
Common issues and their solutions:
1. IAM permissions issues
2. CloudWatch log delivery problems
3. S3 bucket access denied
