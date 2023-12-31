# s3-lambda-data-receiver

## Description:

This CloudFormation Templete creates and setup the S3 Bucket. 

What it is created?

- Two S3 Buckets

---
## Parameters

This template are parametrized

- **S3BucketAppName:** The S3 Bucket used to store the Python application
    - **Default:** lambda-data-receiver
---

## How to run
Read the main documentation [README.md](../README.md), section *How to use*.
---

## Outputs

This template has outputs and this outputs can be used by anothe Stack.
- **S3BucketAppName:** A reference to the created S3 Bucket's name
- **S3BucketAppArn:** A reference to the created S3 Bucket's ARN

| Key                | Value                                           | Description                          | Export name                                |
|--------------------|-------------------------------------------------|--------------------------------------|--------------------------------------------|
| S3BucketAppArn     | arn:aws:s3:::lambda-data-receiver               | A reference to the created S3 Bucket | s3-lambda-data-receiver-S3BucketAppArn     |
| S3BucketAppName    | lambda-data-receiver                            | A reference to the created S3 Bucket | s3-lambda-data-receiver-S3BucketAppName    |
