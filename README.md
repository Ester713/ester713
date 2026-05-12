<div align="center">

# Hey, I'm Ester 👋

### Cloud & DevOps Engineer in Training | AWS | Python | Infrastructure

[![GitHub followers](https://img.shields.io/github/followers/Ester713?style=social)](https://github.com/Ester713)

</div>

---

## 🚀 About Me

I am an aspiring Cloud and DevOps Engineer currently in a hands-on IT training program, building and deploying real production infrastructure on AWS. Every project I complete is a working, deployed application — not just theory.

- 🌱 Currently learning **Cloud Engineering, DevOps, and AWS Infrastructure**
- 🔭 Building full-stack applications on **AWS**
- 💡 Passionate about **automation, reliability, and cloud security**
- 🎯 Goal: **AWS Solutions Architect Associate certification**

---

## 🛠️ Tech Stack

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=amazon-rds&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazon-dynamodb&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

**DevOps & Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Monitoring & Security**

![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazon-aws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

## 📂 Featured Projects

### 🏗️ Project 1 & 2 — AWS Resume Portal
> Full-stack job application portal deployed on production AWS infrastructure

**Architecture:**
- **Frontend:** S3 + CloudFront with custom domain and HTTPS
- **Backend:** ALB + Auto Scaling Group + EC2 running Flask/Gunicorn/nginx
- **Database:** RDS PostgreSQL in private subnets
- **Storage:** Private S3 bucket for resume files
- **Email:** AWS SES for confirmation emails
- **Security:** IAM least privilege, Secrets Manager, Session Manager, ACM

**What I built:**
- Configured nginx as a reverse proxy for Flask
- Debugged multi-layer production failures across 6+ AWS services
- Created golden AMIs for consistent ASG deployments
- Set up end-to-end HTTPS with ACM and Route53

🔗 [View Repository](https://github.com/Ester713/resume-portal)

---

### ⚡ Project 3 — Serverless User Registration API
> Full CRUD application built entirely on serverless AWS services

**Architecture:**
- **Frontend:** S3 + CloudFront
- **API:** API Gateway (REST) with 3 resources and 6 methods
- **Backend:** AWS Lambda (Python 3.12)
- **Database:** DynamoDB

**What I built:**
- Created Lambda function with full CRUD operations
- Configured API Gateway with Lambda proxy integration and CORS
- Built a responsive frontend that consumes the API
- Implemented Create, Read, Update, Delete for user records

🔗 [View Repository](https://github.com/Ester713/resume-portal/tree/main/serverless-user-api)

---

### 📊 Project 4 — Cloud Monitoring & Alerting
> Production-grade monitoring setup for the serverless application

**What I configured:**
- CloudWatch logging for API Gateway — every request logged with IP, method, path, status
- Lambda custom logging with INFO/WARNING/ERROR log levels
- DynamoDB metrics in CloudWatch
- S3 request metrics
- CloudWatch alarm for Lambda errors
- SNS email notifications — receive alerts within minutes of a failure

**Real world result:** When Lambda throws an error CloudWatch detects it and sends an email alert automatically.

🔗 [View Repository](https://github.com/Ester713/resume-portal)

---

## 📈 What I Have Learned

```
✅ Cloud Architecture    — Multi-tier AWS applications
✅ Linux Administration  — Server config, services, logs
✅ Networking            — DNS, HTTPS, load balancing, reverse proxy
✅ Security              — IAM, Secrets Manager, VPC, private subnets
✅ Serverless            — Lambda, API Gateway, DynamoDB
✅ Monitoring            — CloudWatch, SNS, alarms
✅ Debugging             — Systematic layer-by-layer troubleshooting
✅ Version Control       — Git, GitHub, commit history
```

---

## 🔥 Troubleshooting Experience

One of the most valuable skills I have built is **systematic production debugging**:

- Traced and fixed a 6-layer API submission failure (wrong bucket name → missing IAM permission → wrong secret name → wrong RDS hostname → missing DB key → placeholder URL)
- Diagnosed nginx default config conflicts causing ALB health check failures on Fedora
- Resolved ASG instance refresh failures using golden AMI strategy
- Identified stale EC2 instances registered in ALB target group causing intermittent 404s
- Fixed KMS key permissions blocking RDS connectivity

---

## 📊 GitHub Stats

<div align="center">

![Ester's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Ester713&show_icons=true&theme=dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Ester713&layout=compact&theme=dark&hide_border=true)

</div>

---

## 📫 Get In Touch

- 💼 Open to **Cloud Engineer / Junior DevOps** opportunities
- 📧 Reach me at **ester@ade@gmail.com**

---

<div align="center">

*"Every production outage is a learning opportunity in disguise."*

</div>
