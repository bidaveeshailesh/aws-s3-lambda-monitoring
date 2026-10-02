# AWS S3 Activity Monitoring with Lambda

## 📌 Project Overview

This project demonstrates how to monitor activity in an **Amazon S3 bucket** using **AWS Lambda** and **Amazon CloudWatch Logs**.

When objects are uploaded to or downloaded from the S3 bucket, an S3 event triggers the Lambda function. The Lambda function processes the event and records the activity in CloudWatch Logs.

## 🏗️ Architecture

```text
User
  |
  v
Amazon S3 Bucket
  |
  | S3 Event
  v
AWS Lambda
  |
  | Logs
  v
Amazon CloudWatch
```

## ☁️ AWS Services Used

- **Amazon S3** — Stores objects and generates activity events.
- **AWS Lambda** — Processes S3 events without managing servers.
- **Amazon CloudWatch** — Stores and displays Lambda execution logs.
- **AWS IAM** — Provides permissions required by the services.

## ⚙️ How It Works

1. An object is uploaded to or accessed from the S3 bucket.
2. Amazon S3 generates an event.
3. The event triggers the AWS Lambda function.
4. Lambda processes the event details.
5. Activity information is written to CloudWatch Logs.
6. The logs can be reviewed for monitoring and troubleshooting.

## 🔐 IAM Permissions

The project requires appropriate IAM permissions for:

- S3 event access
- Lambda execution
- CloudWatch log creation and writing

## 🛠️ Technologies Used

- AWS S3
- AWS Lambda
- Amazon CloudWatch
- AWS IAM
- Python
- Git & GitHub

## 🎯 What I Learned

- How S3 event notifications work
- How to create and use AWS Lambda functions
- How Lambda can respond to S3 events
- How to monitor Lambda execution using CloudWatch Logs
- Basic AWS IAM permissions
- How to document an AWS project using GitHub

## 📂 Project Type

**Cloud / AWS / Serverless / Monitoring**

## 👨‍💻 Author

**Shailesh Bidave**

GitHub: [@bidaveeshailesh](https://github.com/bidaveeshailesh)
