# AWS Week 10 Task: S3 → Lambda Automation

This repository contains the deliverables for **Week 10 AWS assignment**, demonstrating the creation of an **S3 bucket** that automatically triggers a **Lambda function** whenever a new file is uploaded.

## Task Overview
- Create an **S3 bucket**.  
- Configure **event notifications** to trigger a Lambda function on new file uploads.  
- Lambda function performs a simple action, such as:
  - Printing the uploaded file name  
  - Writing to **CloudWatch Logs**  
  - Sending a notification email via **SNS/SES**

## Files Included
- `Lambda Function Code.png` – Screenshot of Lambda code/configuration  
- `Event Notification on S3.png` – Screenshot of S3 event trigger  
- `Cloudwatch LogGroup.png` – Proof that the Lambda executed  
- `Test Email From SNS.png` – Screenshot of email notification  
- `IAM Roles.png` – Screenshot of IAM roles used  

## Outcome
- The Lambda function is triggered automatically whenever a file is uploaded to S3.  
- CloudWatch logs and/or email notifications confirm execution.  

## Notes
- AWS resources were deleted after screenshots were taken to avoid billing charges.  
- All files in this repository are screenshots and documentation of the task.

