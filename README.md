<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B+I'm+Ester+Ade;Cloud+%26+DevOps+Engineer;AWS+%7C+Python+%7C+Serverless" alt="Typing SVG" />

### Cloud & DevOps Engineer | AWS | Python | Serverless | Infrastructure

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ester-ade-92997640a)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ester713)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Ester.ade01@gmail.com)
[![Location](https://img.shields.io/badge/Dallas%2C%20TX-00897B?style=for-the-badge&logo=google-maps&logoColor=white)](#)

</div>

---

## 👩‍💻 About Me

Cloud and DevOps Engineer based in **Dallas, TX**, specializing in AWS infrastructure, serverless architecture, and production system reliability.

I design, deploy, and maintain full-stack cloud applications — from multi-tier EC2 architectures behind Application Load Balancers to fully serverless Lambda pipelines. Every project in my portfolio is a **live, working deployment** built and debugged from scratch on AWS.

What sets me apart is my hands-on troubleshooting experience — I have diagnosed and resolved complex production failures across multiple AWS services simultaneously, the kind of real-world problems that most engineers only encounter after years on the job.

- 🔭 Currently building production-grade AWS infrastructure
- 💡 Passionate about **cloud security, automation, and reliability**
- 🎯 Pursuing **AWS Solutions Architect Associate** certification
- 💼 Open to **Cloud Engineer** and **DevOps Engineer** opportunities

---

## 🛠️ Tech Stack

**Cloud Platforms & Services**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=amazon-rds&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazon-dynamodb&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=for-the-badge&logo=amazon-aws&logoColor=white)

**DevOps & Infrastructure**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Security & Monitoring**

![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazon-aws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Secrets Manager](https://img.shields.io/badge/Secrets_Manager-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![SNS](https://img.shields.io/badge/SNS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

## 🚀 Featured Projects

### 🏗️ Project 1 & 2 — AWS Resume Portal
> **Production full-stack job application portal on AWS**

A complete job application system where candidates submit their information and resume PDF, which is saved to a database and triggers a confirmation email — all running on enterprise-grade AWS infrastructure.

| Layer | Technology |
|-------|-----------|
| Frontend | S3 + CloudFront + Custom Domain + HTTPS |
| Backend | ALB + Auto Scaling Group + EC2 + Flask + Gunicorn + nginx |
| Database | RDS PostgreSQL (private subnet) |
| Storage | Private S3 bucket |
| Email | AWS SES |
| Security | IAM, Secrets Manager, ACM, Session Manager |

**Key achievements:**
- ✅ Diagnosed and resolved a **6-layer production failure** — wrong S3 bucket, missing IAM permission, incorrect secret name, wrong RDS hostname, missing DB key, placeholder URL — each discovered and fixed systematically
- ✅ Resolved nginx default config conflicts causing ALB health check failures
- ✅ Implemented **golden AMI strategy** eliminating unreliable user data scripts
- ✅ Identified stale EC2 instances in ALB target group causing intermittent 404 errors
- ✅ Full HTTPS with ACM certificate, Route53 DNS, and CloudFront CDN

🔗 [View Repository](https://github.com/Ester713/resume-portal)

---

### ⚡ Project 3 — Serverless User Registration API
> **Full CRUD application on serverless AWS infrastructure**

A complete user management system with zero server management — Lambda handles all compute, DynamoDB stores all data, and API Gateway manages all routing.

| Layer | Technology |
|-------|-----------|
| Frontend | S3 + CloudFront |
| API | API Gateway REST — 3 resources, 6 methods |
| Backend | AWS Lambda (Python 3.12) |
| Database | DynamoDB |

**Key achievements:**
- ✅ Built full CRUD operations — Create, Read, Update, Delete
- ✅ Configured API Gateway with Lambda proxy integration and CORS
- ✅ Diagnosed and fixed Lambda proxy integration failure causing silent data loss
- ✅ Resolved DynamoDB partition key schema mismatch
- ✅ Built responsive frontend consuming the API end to end

🔗 [View Repository](https://github.com/Ester713/resume-portal/tree/main/serverless-user-api)

---

### 📊 Project 4 — Cloud Monitoring & Alerting
> **Production monitoring across all AWS services**

Comprehensive observability setup — every request logged, every error detected, every alert delivered within minutes.

**What I configured:**
- ✅ API Gateway access logging — IP, method, path, status code per request
- ✅ Lambda custom logging — INFO, WARNING, ERROR log levels
- ✅ DynamoDB read/write metrics in CloudWatch
- ✅ S3 request metrics
- ✅ CloudWatch alarm — fires on any Lambda error
- ✅ SNS email notification — alert delivered within 2 minutes of failure

**Real result:** Lambda throws an error → CloudWatch detects it → SNS fires → email received. Zero manual checking required.

🔗 [View Repository](https://github.com/Ester713/resume-portal)

---

## 🔥 Production Troubleshooting Experience

The most valuable skill in cloud engineering is knowing how to debug what you cannot see. Here is what I have resolved in production:

```
🔴 nginx default server block overriding custom proxy config on Fedora
   → Replaced entire nginx.conf, eliminated Fedora defaults

🔴 ASG instance refresh stuck at 0% — new instances failing health checks
   → Switched from unreliable user data scripts to golden AMI strategy

🔴 Intermittent 404 errors despite healthy ASG instances
   → Identified stale manual EC2 instances still registered in ALB target group

🔴 6-layer API submission failure chain
   → Wrong bucket name → missing IAM permission → wrong secret name
     → wrong RDS hostname → missing DB key → placeholder URL in frontend

🔴 RDS connection timeout despite correct security groups
   → Traced to KMS key missing EC2 IAM role as authorized key user

🔴 DynamoDB PutItem ValidationException
   → Partition key created as 'type' instead of 'id' — recreated table
```

---

## 📈 Skills Summary

```
✅ Cloud Architecture     Multi-tier and serverless AWS applications
✅ Linux Administration   nginx, systemd, bash, service management
✅ Networking             DNS, HTTPS, load balancing, reverse proxy, VPC
✅ Security               IAM least privilege, Secrets Manager, KMS, ACM
✅ Serverless             Lambda, API Gateway, DynamoDB
✅ Monitoring             CloudWatch logs, alarms, SNS notifications
✅ Databases              RDS PostgreSQL, DynamoDB
✅ Debugging              Systematic layer-by-layer production troubleshooting
✅ Version Control        Git, GitHub, commit history, branching
```

---

## 📊 GitHub Stats

<div align="center">

![Ester's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Ester713&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Ester713&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 📫 Let's Connect

<div align="center">

| | |
|---|---|
| 📧 **Email** | [Ester.ade01@gmail.com](mailto:Ester.ade01@gmail.com) |
| 💼 **LinkedIn** | [linkedin.com/in/ester-ade-92997640a](https://www.linkedin.com/in/ester-ade-92997640a) |
| 🐙 **GitHub** | [github.com/Ester713](https://github.com/Ester713) |
| 📍 **Location** | Dallas, TX |

💼 **Open to Cloud Engineer and DevOps Engineer opportunities**

</div>

---

<div align="center">

*"In production, every error is a teacher. I have learned from many."*

</div>









