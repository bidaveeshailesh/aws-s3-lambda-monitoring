# aws-s3-lambda-monitoring
AWS project demonstrating S3 event monitoring using Lambda and CloudWatch Logs to track object PUT and GET activities.
# AWS S3 Activity Monitoring with Lambda

## Project Date

2025

## Project Overview

This project demonstrates how AWS Lambda can be used to monitor
activities performed on objects in an Amazon S3 bucket.

When an object is uploaded or accessed, an S3 event notification
can trigger a Lambda function. The Lambda function processes the
event information and records relevant details in Amazon CloudWatch Logs.

## AWS Services Used

- Amazon S3
- AWS Lambda
- Amazon CloudWatch
- AWS IAM

## Project Objectives

- Create and configure an S3 bucket
- Configure S3 event notifications
- Create an AWS Lambda function
- Trigger Lambda using S3 events
- Process S3 activity information
- Store logs in CloudWatch
- Monitor bucket activity

## Basic Workflow

S3 Bucket
    |
    | Object Event
    v
AWS Lambda
    |
    | Process Event
    v
CloudWatch Logs

## Example Events

- Object upload (PUT)
- Object access/event notification (GET, where configured)

## What I Learned

- S3 event notifications
- AWS Lambda triggers
- CloudWatch logging
- IAM permissions
- Basic serverless architecture
- Monitoring AWS resources

## Project Type

Resume Project / Learning Project
