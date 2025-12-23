# AWS Practice Repository

This repository contains hands-on AWS practice exercises and experiments for learning cloud infrastructure and services.

## Prerequisites

- AWS CLI v2 (automatically installed via devcontainer)
- AWS account with appropriate credentials configured
- Basic understanding of cloud computing concepts

## Setup

Configure AWS credentials:

```bash
aws configure
```

You'll need:
- AWS Access Key ID
- AWS Secret Access Key
- Default region (e.g., us-east-1)
- Default output format (json recommended)

## Repository Structure

```
.
├── s3/
│   └── bash/
│       ├── create-bucket    # Create S3 bucket
│       └── delete-bucket    # Delete S3 bucket
├── aws-practice/            # General AWS exercises
└── README.md
```

## AWS Services Covered

- EC2 (Elastic Compute Cloud)
- S3 (Simple Storage Service)
- IAM (Identity and Access Management)
- VPC (Virtual Private Cloud)
- Lambda
- CloudFormation
- And more...

## Usage

### S3 Bash Scripts

Create an S3 bucket:
```bash
./s3/bash/create-bucket your-unique-bucket-name
```

Delete an S3 bucket:
```bash
./s3/bash/delete-bucket your-bucket-name
```

**Important**: S3 bucket names must be globally unique across all AWS accounts. Use lowercase letters, numbers, and hyphens only (3-63 characters).

## Resources

- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS CLI Reference](https://docs.aws.amazon.com/cli/latest/reference/)
- [AWS Free Tier](https://aws.amazon.com/free/)

## Notes

Always review costs before deploying resources. Use the AWS Free Tier when possible and clean up resources after practice sessions.
