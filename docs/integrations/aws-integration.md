# AWS Integration

Connect Document360 with Amazon Web Services (AWS) to leverage cloud infrastructure for documentation hosting, storage, and automation.

---

## Overview

The AWS integration allows teams to use AWS services such as S3, CloudFront, and Lambda to extend Document360's capabilities, enabling custom hosting, asset management, and event-driven documentation workflows.

---

## Prerequisites

- An AWS account with appropriate IAM permissions
- Document360 project admin access
- AWS access key ID and secret access key

---

## Setup Steps

1. Navigate to **Settings → Integrations → AWS** in Document360.
2. Enter your AWS **access key ID** and **secret access key**.
3. Select the AWS region for your resources.
4. Configure S3 bucket settings for asset storage.
5. Set up CloudFront distribution if using CDN for documentation.
6. Click **Save**.

---

## Features

- **S3 Asset Storage** – Store documentation images and files in an S3 bucket.
- **CloudFront CDN** – Deliver documentation assets globally with low latency.
- **Lambda Triggers** – Use AWS Lambda to automate documentation workflows.
- **IAM Access Control** – Manage documentation access using AWS IAM policies.

---

## Use Cases

- Host documentation assets in S3 for scalable and cost-effective storage.
- Use CloudFront to speed up documentation delivery for a global audience.
- Trigger documentation updates via Lambda functions when AWS infrastructure changes.

---

## Best Practices

- Use IAM roles with least-privilege access for Document360 AWS credentials.
- Enable S3 versioning to maintain a history of uploaded documentation assets.
- Set up CloudFront cache invalidation rules for documentation updates.

---

## Summary

The AWS integration extends Document360 with the power of Amazon's cloud services, enabling scalable, globally distributed, and automated documentation infrastructure.
