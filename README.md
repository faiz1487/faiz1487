<div align="center">

<img src="./hero.svg" alt="Faizan Kaishar — Cloud and DevOps Engineer" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/faizan-kaishar-5b53a7235)
[![Portfolio](https://img.shields.io/badge/Portfolio-Explore-7C3AED?style=for-the-badge&logo=netlify&logoColor=white)](https://faizankaishar.netlify.app)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:faizankaishar95@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-faiz1487-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/faiz1487)

![Profile Views](https://komarev.com/ghpvc/?username=faiz1487&label=PROFILE+VIEWS&color=22d3ee&style=for-the-badge)

<img src="./about-life.svg" alt="About Faizan and his approach to DevOps" width="100%" />

</div>

## 👨‍💻 About Me

I'm **Faizan Kaishar**, a Cloud & DevOps Engineer based in **Noida, Uttar Pradesh, India**. I work with AWS infrastructure, Infrastructure as Code, container orchestration, CI/CD automation, and observability. My background in manufacturing automation informs how I approach reliable operations and system design.

- ☁️ **Cloud:** AWS (EC2, S3, RDS, VPC, IAM, CloudWatch, EKS); Azure
- 🧱 **Infrastructure as Code:** Terraform, Ansible; familiar with CloudFormation
- 🚀 **Delivery:** Docker, Kubernetes, Helm, Jenkins, GitHub Actions
- 📊 **Observability:** Prometheus, Grafana, Amazon CloudWatch
- 🐍 **Scripting:** Python, Bash, Linux
- 🎯 **Focus:** Repeatable infrastructure, secure delivery, scalable services

<div align="center"><img src="./stack.svg" alt="Cloud, automation, CI/CD, observability and scripting technology stack" width="100%" /></div>

## 🛠️ Tools & Technologies

<div align="center">

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub_Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

<img src="./id-dashboard.svg" alt="Developer ID and delivery pipeline dashboard" width="100%" />

</div>

## 📂 Featured DevOps Projects

> These are project descriptions from my portfolio. Repository links below are relative placeholders until the project folders are published in this profile repository.

| Project | Overview | Stack |
|:--|:--|:--|
| 🏭 **[MES Data Pipeline](./mes-project)** | Simulated manufacturing telemetry pipeline: raw events in S3, structured records in RDS, automated provisioning and deployment, CloudWatch alarms. | AWS, Terraform, Ansible, Docker, GitHub Actions |
| ☸️ **[Microservices on AWS](./microservices-aws)** | Containerized Java microservices on EKS with Helm deployments, Jenkins CI/CD and horizontal pod autoscaling. | Java, Docker, EKS, Helm, Terraform, Jenkins |
| 🔐 **[Hybrid Secure CI/CD](./hybrid-ci-cd)** | Pipeline concept combining image scanning, image signing, ECR publishing, EKS deployment and rollback checks. | GitHub Actions, Jenkins, Trivy, Docker, ECR, EKS |

## 🔄 DevOps Delivery Lifecycle

```text
💻 Code → 🧪 Test → 🏗️ Build → 🔐 Scan → 📦 Publish → ☸️ Deploy → 📊 Monitor
   Git        CI        Docker      Trivy        ECR          EKS       Grafana
```

## 📈 GitHub Dashboard

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=faiz1487&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats for faiz1487" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=faiz1487&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages for faiz1487" height="170" />

</div>

## 🌃 My 3D Contribution City

<div align="center">

*Every contribution helps build the city. Updated daily by GitHub Actions after initial setup.*

<img src="https://raw.githubusercontent.com/faiz1487/faiz1487/output/profile-3d-contrib/profile-night-view.svg" alt="3D GitHub contribution graph; appears after the workflow first succeeds" width="100%" />

</div>

> **Setup:** Enable GitHub Actions write permissions and run the included `3D Contribution Graph` workflow once. The graph will not appear until the `output` branch is generated.

## 🗺️ Learning & Development Roadmap

- [ ] Modular Terraform EKS infrastructure with production-minded security defaults
- [ ] Protected GitHub Actions environments and secrets-management examples
- [ ] Architecture diagrams and repeatable deployment demos
- [ ] GitOps deployment examples and enhanced observability

## ▶️ Example: Run the MES Demo

```bash
# Replace this with the URL of the actual project repository if separate.
git clone https://github.com/faiz1487/faizan-devops-portfolio.git
cd faizan-devops-portfolio/mes-project/terraform
terraform init
terraform plan -var-file=envs/dev.tfvars
# Review the plan and expected AWS charges before applying.
terraform apply -var-file=envs/dev.tfvars
```

> Commands are illustrative and require the corresponding project files, AWS credentials, and a valid environment configuration. Destroy unused cloud resources to avoid charges.

## 📬 Let's Connect

<div align="center">

<img src="./connect.svg" alt="Let's connect" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/faizan-kaishar-5b53a7235)
[![Portfolio](https://img.shields.io/badge/Portfolio-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://faizankaishar.netlify.app)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:faizankaishar95@gmail.com)

**Automate thoughtfully. Deploy confidently. Monitor continuously.** ⚡

</div>
