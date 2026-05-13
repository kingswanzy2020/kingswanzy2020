<div align="center">

<!-- Animated typing headline — replaces static "Hi there" -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=1F8EF1&center=true&vCenter=true&width=700&lines=Hey+%F0%9F%91%8B+I'm+Ahmed+Tetteh;AWS+DevOps+Engineer;Cloud+Infrastructure+%7C+CI%2FCD+%7C+IaC;Building+reliable+systems+at+scale)](https://git.io/typing-svg)

<!-- One-liner value proposition — what a hiring manager sees in 3 seconds -->
**DevOps Engineer** · AWS Certified · EKS · Terraform · CI/CD Automation · RAG × DevOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmed%20Tetteh-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-tetteh)
[![Email](https://img.shields.io/badge/Email-kingsleyswanzy%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kingsleyswanzy@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![Location](https://img.shields.io/badge/Location-Daejeon%2C%20South%20Korea-4285F4?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

## 🚀 About Me

```yaml
name:       Ahmed Tetteh
role:       DevOps Engineer
focus:      Cloud Infrastructure · CI/CD · Container Orchestration · IaC
cloud:      AWS (EKS, CodePipeline, Lambda, CloudFormation, ECS, DynamoDB)
containers: Docker · Kubernetes · Helm · Amazon EKS
iac:        CloudFormation · Terraform (in progress) · AWS CDK
cicd:       GitHub Actions · AWS CodePipeline · Jenkins
monitoring: Prometheus · Grafana · ELK Stack · CloudWatch
cert:       AWS Certified Solutions Architect Associate
currently:  Deepening Kubernetes, Terraform, and AI-powered DevOps pipelines
```

---

## 🏗️ Featured Projects

> Click any project to explore the full implementation.

### ⚙️ [AI CI/CD Pipeline with GitHub Actions](https://github.com/kingswanzy2020/ai-cicd-github)
**GitHub Actions · Python · Docker · AWS**

End-to-end CI/CD pipeline for an AI application using GitHub Actions — covers build, test, and deployment automation following patterns used by enterprise engineering teams.

- ✅ Automated testing on every pull request
- ✅ Artifact packaging and environment promotion workflows
- ✅ Mirrors real-world Netflix/Spotify-style deployment automation

---

### ☸️ [Deploy a RAG API to Kubernetes](https://github.com/kingswanzy2020/Projects/tree/main/Nextwork%20Projects/DevOps%20%26%20AI/Deploy%20a%20RAG%20API%20to%20Kubernetes)
**Docker · Kubernetes · Minikube · kubectl · FastAPI · RAG · Ollama (TinyLlama)**

Containerized a FastAPI-based RAG API and deployed it to a Kubernetes cluster using Minikube. Wrote Deployment and Service YAML manifests, loaded the Docker image into Minikube's isolated daemon, and validated the full request flow from outside the cluster through to the running pod.

- ✅ Kubernetes self-healing confirmed — deleted pod automatically recovered via the reconciliation loop with zero manual intervention
- ✅ Debugged real cross-environment networking: resolved Ollama host-machine connectivity from inside the cluster
- ✅ AI responses successfully served through Kubernetes NodePort after full containerization

---

### 🔁 [AWS Native CI/CD Pipeline](https://github.com/kingswanzy2020/Projects/tree/main/Nextwork%20Projects/DevOps%20Challenge(CI_CD%20Pipepline)%20)
**CodePipeline · CodeBuild · CodeDeploy · CodeArtifact · CloudFormation · S3 · EC2**

A 7-day end-to-end DevOps challenge building a full AWS-native CI/CD pipeline from scratch — web app on EC2, GitHub integration, secure package management with CodeArtifact, automated builds with CodeBuild, deployments with CodeDeploy, and the entire stack defined as Infrastructure as Code with CloudFormation.

- ✅ Full pipeline: commit → CodePipeline → CodeBuild (buildspec.yaml) → CodeDeploy → EC2 production
- ✅ Secure dependency management via AWS CodeArtifact — no public package registry exposure
- ✅ Entire infrastructure reproducible from a single CloudFormation template

---

### 🤖 [AI-Powered PR Code Review with Gemini](https://github.com/kingswanzy2020/Projects/tree/main/Nextwork%20Projects/Review%20GitHub%20Pull%20Requests%20with%20Gemini)
**GitHub Actions · Python · Gemini API (Google AI) · github-script**

Built an AI code reviewer that automatically analyzes every pull request using Google's Gemini 2.5 model. The GitHub Actions workflow triggers on PR open/update, generates a code diff, sends it to Gemini for security and quality analysis, and posts the review as a PR comment — with auto-labeling by severity (Critical / Warning / Good).

- ✅ Detected real SQL injection and shell injection vulnerabilities in test diffs via Gemini
- ✅ Auto-labels PRs by AI-assessed severity using structured machine-readable output parsing
- ✅ API key secured as a GitHub Secret — zero credentials exposed in the repository

---

### 📬 [Serverless Lead Capture on AWS](https://github.com/kingswanzy2020/Projects/tree/main/Serveless%20Lead%20Capture%20on%20AWS)
**Lambda · API Gateway · DynamoDB · S3 · CloudFront · Route 53 · SES · ACM**

Built a production-grade, fully serverless eBook lead capture platform deployed on a custom domain (`kahmedt.com`) with global CDN delivery. A visitor submits a form → Lambda instantly emails the business owner via SES, stores the lead in DynamoDB, and logs the event in CloudWatch. Zero servers. Zero idle cost. Pure event-driven architecture.

- ✅ End-to-end serverless: S3 + CloudFront + Route 53 + ACM for the frontend; API Gateway + Lambda for the backend
- ✅ IAM least-privilege design — Lambda role scoped to only `dynamodb:PutItem` and `ses:SendEmail`
- ✅ Debugged real-world CORS, DNS propagation, and ACM region constraints in production

---

## 🧰 Tech Stack

**Cloud & IaC**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F00?style=for-the-badge&logo=amazonaws&logoColor=white)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

**CI/CD & Automation**

![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)

**Languages & Scripting**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Monitoring & Databases**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)

**Version Control**

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

[![Ahmed's GitHub stats](https://github-readme-stats.vercel.app/api?username=kingswanzy2020&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/anuraghazra/github-readme-stats)

![Streak](https://nirzak-streak-stats.vercel.app/?user=kingswanzy2020&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kingswanzy2020&theme=tokyonight&hide_border=true&layout=compact&count_private=true)

</div>

---

## 🎓 Certifications

| Certification | Issuer |
|---|---|
| ✅ AWS Certified Solutions Architect Associate | Amazon Web Services |
| ✅ AWS Certified Cloud Practitioner (CLF-C02) | Amazon Web Services |
| ✅ Docker Training — Absolute Beginner | KodeKloud |
| ✅ KodeKloud Engineer — Docker Level 1 | KodeKloud |
| ✅ Introduction to DevOps | IBM |
| ✅ Linux Commands & Shell Scripting | IBM |

---

<div align="center">

*Open to DevOps, SRE, and Cloud Engineer roles — let's connect!*

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-tetteh)
[![Email](https://img.shields.io/badge/Send%20an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kingsleyswanzy@gmail.com)

[![](https://visitcount.itsvg.in/api?id=kingswanzy2020&icon=0&color=1)](https://visitcount.itsvg.in)

</div>
