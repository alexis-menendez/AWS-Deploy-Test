# Terraform Practice

This repository is a personal sandbox for learning and experimenting with deploying full-stack applications to [Amazon Web Services (AWS).](https://aws.amazon.com/) It is focused on understanding cloud deployment workflows using tools like Elastic Beanstalk and S3.

## ⚠️ Disclaimer

This repository was created as a self-guided learning project for exploring AWS deployment strategies. It is intended solely for educational purposes and may include in-progress, incomplete, or non-production configurations. The goal is to deepen my understanding of cloud hosting and deployment mechanics through hands-on experimentation.


## Purpose

To gain hands-on experience with:
- Deploying full-stack applications on AWS
- Using AWS Elastic Beanstalk for Node.js and React apps
- Hosting static assets with S3
- Managing environment variables and deployment pipelines
- Troubleshooting cloud service issues in real-time

## Tools & Technologies

- AWS Elastic Beanstalk
- Amazon S3
- Node.js / Express
- React
- AWS CLI
- Docker (for containerized deployments)

## Getting Started

> These steps will guide you through deploying a simple app using AWS services.

### Prerequisites
- AWS account with appropriate IAM permissions
- AWS CLI installed and configured (aws configure)
- Node.js and npm installed locally
- A simple full-stack app to deploy (or use a sample from this repo)

### Steps

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/AWS-Deploy-Test.git
   cd AWS-Deploy-Test

2. Install dependencies for both client and server (if present).

3. Set up your Elastic Beanstalk environment:

   ```bash
   eb init

4. Create and deploy the environment:

   ```bash
   eb create my-env-name
   eb deploy

5. (Optional) Use Amazon S3 for static assets:
- Create a bucket via the AWS Console
- Upload static files
- Configure permissions and public access settings

6. Monitor and troubleshoot with:

   ```bash
   eb status
   eb logs

## Folder Structure

```bash
AWS-Deploy-Test/
├── client/              # React frontend  
├── server/              # Node.js backend  
├── .elasticbeanstalk/   # EB configuration files  
└── README.md            # This file  
```

## Resources

[**AWS Elastic Beanstalk Docs:**](https://docs.aws.amazon.com/elastic-beanstalk/)

[**AWS CLI Command Reference:**](https://docs.aws.amazon.com/cli/latest/)

[**AWS S3 Documentation:**](https://docs.aws.amazon.com/s3/)

[**Deploying a MERN App to AWS (Tutorial):**](https://www.youtube.com/watch?v=eRdeAbGKyuk&themeRefresh=1)
