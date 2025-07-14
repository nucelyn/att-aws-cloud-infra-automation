# att-aws-cloud-infra-automation
# Enterprise Cloud Infrastructure Automation – AT&T Mobility (Simulated)

## 📌 Project Summary
Led the design, automation, and operational support of a scalable and secure AWS infrastructure mimicking enterprise-level standards used at AT&T Mobility. Focused on improving infrastructure reliability, enforcing compliance, and enabling rapid deployment of mobile and internal applications through Infrastructure as Code (IaC), CI/CD, and monitoring solutions.

## ⚙️ Key Responsibilities
- Provisioned cloud infrastructure using Terraform and AWS CloudFormation to build secure and reusable modules for VPC, EC2, ALB, RDS, S3, and IAM.
- Built and maintained CI/CD pipelines using Jenkins and AWS CodePipeline for automated deployment of infrastructure and application artifacts across development, staging, and production environments.
- Designed and implemented centralized logging and monitoring with CloudWatch, Datadog, and AWS Lambda for alerting and performance tuning.
- Automated security and compliance enforcement using AWS Config, GuardDuty, and IAM Access Analyzer to align with enterprise policies (SOC2-like).
- Supported cost optimization efforts by analyzing AWS Cost Explorer data and recommending reserved instances, right-sizing EC2 instances, and leveraging S3 lifecycle policies.
- Developed runbooks and documentation in Confluence and version-controlled diagrams in Git for disaster recovery procedures and onboarding.
- Collaborated with cross-functional teams to integrate infrastructure changes via Jira, participating in daily standups and sprint planning sessions.

## 🧰 Tools & Technologies
- **AWS Services**: EC2, S3, RDS (PostgreSQL), Lambda, VPC, IAM, CloudWatch, CloudTrail, Systems Manager, Route 53, Config  
- **Infrastructure as Code**: Terraform, CloudFormation, AWS CDK  
- **CI/CD**: Jenkins, GitLab CI, AWS CodePipeline, CodeBuild, CodeDeploy  
- **Monitoring & Logging**: CloudWatch, Datadog, Splunk, SNS  
- **Security & Governance**: IAM, KMS, GuardDuty, AWS Config, Inspector, Security Hub  
- **Collaboration**: Jira, Confluence, GitHub, Slack

## 🏆 Key Achievements
- Reduced environment provisioning time by **80%** through fully automated Terraform pipelines.
- Increased deployment success rate by **90%** by implementing automated pre-deployment checks and rollback mechanisms.
- Enabled proactive incident response by integrating CloudWatch alerts with Slack via Lambda functions.
- Identified and resolved 12+ high-risk IAM misconfigurations, improving security posture and passing internal compliance audits.

## 🗂️ Repository Structure
```
att-aws-cloud-infra-automation/
├── README.md
├── infra/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
├── ci-cd/
│   ├── Jenkinsfile
│   └── buildspec.yml
├── scripts/
│   └── deploy.sh
├── monitoring/
│   └── cloudwatch-alarms.json
├── security/
│   └── iam-policies/
├── docs/
│   └── architecture.png
└── cost-optimization/
    └── cost-analyzer.ipynb
```

## 📌 Note
This is a simulated portfolio project inspired by real-world enterprise environments (e.g., AT&T Mobility) and showcases best practices in cloud engineering and DevOps on AWS.
