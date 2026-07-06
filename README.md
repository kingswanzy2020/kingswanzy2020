<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:1F6FEB,100:39D353&height=180&section=header&text=Ahmed%20Tetteh&fontSize=54&fontColor=ffffff&animation=fadeIn&desc=DevOps%20%7C%20Cloud%20%7C%20Platform%20Engineering&descSize=18&descAlignY=75" alt="banner" width="100%"/>


[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=1F8EF1&center=true&vCenter=true&width=780&lines=Ahmed+Tetteh+—+DevOps+Engineer;AWS+%7C+Kubernetes+%7C+GitOps+%7C+Terraform;Pipelines+that+self-heal+before+you+notice;Security-first+cloud-native+infrastructure)](https://git.io/typing-svg)

**DevOps Engineer** — AWS Certified · EKS in Production · GitOps · IaC at Scale · AIOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmed%20Tetteh-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-tetteh-76a538126)
[![Email](https://img.shields.io/badge/Email-kingsleyswanzy%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kingsleyswanzy@gmail.com)
[![AWS SAA](https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![Location](https://img.shields.io/badge/📍-Daejeon%2C%20South%20Korea-4285F4?style=flat-square)](#)

</div>

---

## About Me

```yaml
name:        Ahmed Tetteh
role:        DevOps Engineer
focus:       Cloud-native infrastructure · GitOps · Container orchestration · AIOps
cloud:       AWS (EKS, CodePipeline, Lambda, CloudFormation, ECS, RDS, DynamoDB)
containers:  Docker · Kubernetes (EKS production) · Helm · eksctl
gitops:      ArgoCD · Kustomize · Sealed Secrets · Renovate Bot
iac:         Terraform (modular, GitOps-managed) · CloudFormation · AWS CDK
cicd:        GitHub Actions · AWS CodePipeline · Jenkins · ArgoCD
security:    OIDC federation · IAM least-privilege · RBAC · Bitnami Sealed Secrets
monitoring:  Prometheus · Grafana · Alertmanager · CloudWatch
certs:       AWS Solutions Architect Associate · AWS Cloud Practitioner
building:    Autonomous incident response pipelines · Production-grade GitOps systems
```

---

## Featured Projects

### 🤖 [AI-Powered Log Analysis & Autonomous Incident Response](https://github.com/kingswanzy2020/Projects/tree/main/ai-devops/ai-log-analysis-incident-response)
**`Python` `Kubernetes` `FastAPI` `Ollama (LLM)` `Redis` `Fluent Bit` `GitHub API`**

An autonomous SRE pipeline that ingests live Kubernetes error logs via Fluent Bit, runs local LLM root-cause diagnosis, and auto-files structured GitHub incident reports — end-to-end, without a human in the loop.

| Outcome | Detail |
|---|---|
| ⚡ **Sub-10s MTTD** | Reduced mean time to detect from minutes to under 10 seconds |
| 🧠 **~90% LLM cache hit** | Redis MD5-based deduplication (10-min TTL) eliminates redundant inference |
| 🔕 **Zero duplicate tickets** | Signature-matched GitHub Issue dedup eliminates repeated incident reports |
| 🛡️ **Rate-limited & resilient** | Token-bucket limiter prevents runaway API calls under log storm conditions |

---

### 🔄 [GitOps Deployment Pipeline with ArgoCD](https://github.com/kingswanzy2020/Projects/tree/main/kubernetes/gitops-argocd-pipeline)
**`Kubernetes` `ArgoCD` `Kustomize` `Sealed Secrets` `GitHub Actions` `Renovate Bot`**

Production-grade GitOps system where the cluster is the single source of truth. ArgoCD continuously reconciles desired vs actual state; any unauthorized change is reversed before an engineer could manually notice.

| Outcome | Detail |
|---|---|
| 🔁 **Sub-10s drift correction** | Self-healing and pruning revert unauthorized cluster changes automatically |
| 🔒 **100% plaintext secrets eliminated** | Bitnami Sealed Secrets encrypts credentials with asymmetric RSA before they touch Git |
| 🤖 **Zero manual deployment steps** | GitHub Actions + Renovate Bot route all changes through auditable, automated PRs |
| 📣 **Real-time deploy visibility** | ArgoCD Notifications posts pending/success/failure statuses to GitHub across 3 sync phases |
| 🗄️ **Safe DB migrations** | PreSync hooks validate database migrations before any deployment proceeds |

---

### 🏗️ [Enterprise Terraform GitOps Pipeline](https://github.com/kingswanzy2020/Projects/tree/main/infrastructure-as-code/enterprise-terraform-gitops)
**`Terraform` `GitHub Actions` `AWS` `OIDC` `TFLint` `Checkov`**

Modular IaC pipeline that provisions 30+ AWS resources across VPC, compute, storage, and IAM — governed by a full GitOps workflow where infrastructure changes go through the same review gates as application code.

| Outcome | Detail |
|---|---|
| 🏛️ **30+ resources, 5 modules** | VPC, EC2, S3, IAM, RDS — each environment reproducible with a single command |
| 🚫 **No long-lived credentials** | OIDC federation between GitHub Actions and AWS; zero static secrets |
| 🔍 **Shift-left security** | Checkov scans every plan; TFLint enforces standards before merge |
| 🤝 **Safe collaboration** | S3 remote state + DynamoDB locking prevents concurrent state corruption |

---

### 📊 [Kubernetes CI/CD Pipeline with Helm & Full Observability](https://github.com/kingswanzy2020/Projects/tree/main/kubernetes/helm-cicd-monitoring)
**`Kubernetes` `Jenkins` `Helm` `Prometheus` `Grafana` `Alertmanager` `Docker`**

End-to-end pipeline from code commit to monitored production deployment. Jenkins handles the build and delivery; a Helm-managed observability stack surfaces the RED method metrics needed to know if the deployment is actually healthy.

| Outcome | Detail |
|---|---|
| 🚀 **Zero manual build-push-deploy** | Jenkins automates the full cycle; rolling deployments with no downtime |
| 📈 **RED method dashboards** | Grafana tracks request rate, error rate, and P99 latency per service |
| 🔔 **Automated alerting** | Custom PrometheusRules fire on 5xx error rate threshold breaches |
| 🔎 **Zero-config scraping** | ServiceMonitor-based auto-discovery picks up new services without manual config |

---

### ☁️ [AWS Native CI/CD Pipeline](https://github.com/kingswanzy2020/Projects/tree/main/ci-cd/aws-devops-cicd-challenge)
**`CodePipeline` `CodeBuild` `CodeDeploy` `CodeArtifact` `CloudFormation` `S3` `EC2`**

Fully AWS-native delivery pipeline — commit to production without leaving the AWS ecosystem. Dependency management runs through CodeArtifact so no build ever touches a public package registry.

| Outcome | Detail |
|---|---|
| 📦 **60% higher deployment frequency** | Automated pipeline removes the friction of manual release coordination |
| 🔐 **Supply chain secured** | Private CodeArtifact mirror; no direct public registry access at build time |
| ♻️ **One-command infra** | Entire stack (pipeline + EC2 + networking) reproduced from a single CloudFormation template |
| ↩️ **Rollback on failure** | Versioned S3 artifacts and CodeDeploy rollback hooks for zero-downtime recovery |

---

### 🔍 [AI-Powered Pull Request Code Review](https://github.com/kingswanzy2020/Projects/tree/main/ci-cd/ai-pr-review-gemini)
**`GitHub Actions` `Python` `Gemini 2.5 API` `github-script`**

Automated code reviewer wired into the PR workflow. Every PR triggers a diff analysis via Gemini 2.5; the workflow parses structured output, labels by severity (Critical / Warning / Good), and posts the review as a PR comment — all before a human reviewer touches the code.

| Outcome | Detail |
|---|---|
| 🐛 **Real vulnerability detection** | Caught SQL injection and shell injection vulnerabilities in test diffs |
| 🏷️ **Machine-readable triage** | Structured Gemini output parsed to auto-label PRs by AI-assessed severity |
| 🔑 **Zero credentials exposed** | API key stored as a GitHub Secret; no secrets in workflow YAML or diff output |

---

### ⚡ [Production Serverless Lead Capture Platform](https://github.com/kingswanzy2020/Projects/tree/main/aws/serverless-lead-capture)
**`Lambda` `API Gateway` `DynamoDB` `S3` `CloudFront` `Route 53` `SES` `ACM`**

End-to-end serverless platform that ran in production at a custom domain (`kahmedt.com`) with global CDN delivery. Visitor submits a form → Lambda fires SES email to the business owner, writes the lead to DynamoDB, and logs to CloudWatch — all within milliseconds, with no servers to manage.

| Outcome | Detail |
|---|---|
| 🌍 **Production-deployed** | Ran at `kahmedt.com` with ACM TLS, CloudFront, and Route 53 DNS (decommissioned after project completion) |
| 🔒 **Least-privilege Lambda** | Role scoped to exactly `dynamodb:PutItem` + `ses:SendEmail` — nothing more |
| 🛠️ **Real debugging** | Resolved production CORS misconfiguration, DNS propagation delays, and ACM us-east-1 region constraint |

---

## 🗺️ Repository Map

All my work, organized. The 📁 **[Projects](https://github.com/kingswanzy2020/Projects)** repo is the portfolio hub — full write-ups, architecture diagrams, and KPIs for every project — while these standalone repos hold the live code:

| Category | Repository | What it is |
|---|---|---|
| 📁 **Portfolio Hub** | [Projects](https://github.com/kingswanzy2020/Projects) | All project write-ups: `ci-cd/` · `kubernetes/` · `infrastructure-as-code/` · `aws/` · `ai-devops/` · `observability/` |
| 🤖 SRE / AIOps | [autonomous-sre](https://github.com/kingswanzy2020/autonomous-sre) | Autonomous incident response inside a Kubernetes cluster |
| 🔄 GitOps | [gitops-demo](https://github.com/kingswanzy2020/gitops-demo) | Git source-of-truth repo driving the ArgoCD pipeline |
| 🏗️ IaC | [terraform-gitops](https://github.com/kingswanzy2020/terraform-gitops) | Enterprise Terraform workflow — plan on PR, apply on merge |
| ☸️ Kubernetes | [fittrack](https://github.com/kingswanzy2020/fittrack) | Helm chart + Jenkins pipeline for the monitored FitTrack app |
| 🔁 CI/CD | [cicd-pipeline-app](https://github.com/kingswanzy2020/cicd-pipeline-app) | App code behind the Jenkins + SonarQube pipeline |
| 🔁 CI/CD | [nextwork-web-project](https://github.com/kingswanzy2020/nextwork-web-project) | Java web app behind the AWS CodePipeline build |
| 🧠 AI / RAG | [nextwork-rag-api](https://github.com/kingswanzy2020/nextwork-rag-api) | RAG API with its own CI/CD pipeline |
| 🛡️ Security | [security-scanner](https://github.com/kingswanzy2020/security-scanner) | AI-powered vulnerability scanner |
| 🏛️ Platform | [petclinic-platform](https://github.com/kingswanzy2020/petclinic-platform) | Infrastructure code for an 8-service microservices platform |
| 🧪 Sandbox | [Lab](https://github.com/kingswanzy2020/Lab) | Experiments and learning scratchpad |

---

## 🧰 Tech Stack

**Cloud & IaC**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F00?style=for-the-badge&logo=amazonaws&logoColor=white)

**Containers, Orchestration & GitOps**

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

**CI/CD & Automation**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![AWS CodePipeline](https://img.shields.io/badge/CodePipeline-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**Languages & Scripting**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Monitoring & Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F00?style=for-the-badge&logo=amazonaws&logoColor=white)

**Security**

![Sealed Secrets](https://img.shields.io/badge/Sealed%20Secrets-1A1A2E?style=for-the-badge&logo=bitnami&logoColor=white)
![OIDC](https://img.shields.io/badge/OIDC%20Federation-0052CC?style=for-the-badge&logo=openid&logoColor=white)

---

## 📊 GitHub Activity

<div align="center">

<img src="github-metrics.svg" alt="GitHub metrics" width="100%"/>

</div>

<sub>Generated daily inside this repo by a [lowlighter/metrics](https://github.com/lowlighter/metrics) GitHub Action — no external image service to break.</sub>

---

## 🎓 Certifications

| Certification | Issuer |
|---|---|
| ✅ AWS Certified Solutions Architect – Associate | Amazon Web Services |
| ✅ AWS Certified Cloud Practitioner (CLF-C02) | Amazon Web Services |
| ✅ Docker Training — Absolute Beginner | KodeKloud |
| ✅ KodeKloud Engineer — Docker Level 1 | KodeKloud |
| ✅ Introduction to DevOps | IBM |
| ✅ Hands-on Linux Commands & Shell Scripting | IBM |

---

<div align="center">

*Open to DevOps, SRE, and Cloud Infrastructure roles — South Korea and remote.*

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-tetteh-76a538126)
[![Email](https://img.shields.io/badge/Send%20an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kingsleyswanzy@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:39D353,50:1F6FEB,100:1a1b27&height=90&section=footer" alt="footer" width="100%"/>
