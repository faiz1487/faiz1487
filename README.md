# Faizan Kaishar — Cloud & DevOps Engineer

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/faizan-kaishar-5b53a7235) [![Email](https://img.shields.io/badge/-Email-D14836?logo=gmail\&logoColor=white)](mailto:faizankaishar95@gmail.com)
<p align="left"> <img src="https://komarev.com/ghpvc/?username=faiz1487&label=Profile%20views&color=0e75b6&style=flat" alt="faiz1487" /> </p
## 🚀 About Me

I’m **Faizan Kaishar**, a Cloud & DevOps Engineer with hands-on experience building and automating cloud infrastructure, CI/CD pipelines, and observability for reliable, scalable systems. I have practical experience with AWS, Terraform, Ansible, Docker, Kubernetes, Jenkins, GitHub Actions, and Python scripting — and a background in manufacturing automation which gives me a strong operational mindset.

* 📍 Based in: Noida, Uttar Pradesh, India
* 📧 Email: [faizankaishar95@gmail.com](mailto:faizankaishar95@gmail.com)
* 💼 LinkedIn: [https://www.linkedin.com/in/faizan-kaishar-5b53a7235](https://www.linkedin.com/in/faizan-kaishar-5b53a7235)
    >

<p>
  <a href="https://www.linux.org/"><img src="https://www.vectorlogo.zone/logos/linux/linux-icon.svg" height="70"/></a>
  <a href="https://aws.amazon.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/2560px-Amazon_Web_Services_Logo.svg.png" height="70"/></a>
  <a href="https://azure.microsoft.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Microsoft_Azure.svg/1200px-Microsoft_Azure.svg.png" height="75"/></a>
  <a href="https://www.docker.com/"><img src="https://raw.githubusercontent.com/itsksaurabh/itsksaurabh/master/assets/docker.gif" height="80"/></a>
  <a href="https://kubernetes.io/"><img src="https://raw.githubusercontent.com/itsksaurabh/itsksaurabh/master/assets/k8s.gif" height="80"/></a>
  <a href="https://helm.sh/"><img src="https://raw.githubusercontent.com/itsksaurabh/itsksaurabh/master/assets/helm.gif" height="80"/></a>
  <a href="https://docs.gitlab.com/ee/ci/"><img src="https://raw.githubusercontent.com/itsksaurabh/itsksaurabh/master/assets/cicd.gif" height="80"/></a>
  <a href="https://www.terraform.io/"><img src="https://raw.githubusercontent.com/itsksaurabh/itsksaurabh/master/assets/terraform.gif" width="120"/></a>
  <a href="https://www.jenkins.io/"><img src="https://raw.githubusercontent.com/DARK-art108/ItsRitesh/master/assets/ll.png" height="80"/></a>
  <a href="https://www.ansible.com/"><img src="https://www.vectorlogo.zone/logos/ansible/ansible-icon.svg" height="80"/></a>
  <a href="https://pages.github.com/"><img src="https://media.giphy.com/media/kH1DBkPNyZPOk0BxrM/giphy.gif" width="80"/></a>
  <a href="https://code.visualstudio.com/"><img src="https://i.giphy.com/media/IdyAQJVN2kVPNUrojM/200.webp" height="80"/></a>
  <a href="https://golang.org/"><img src="https://raw.githubusercontent.com/itsksaurabh/itsksaurabh/master/assets/golang.gif" height="80"/></a>
</p>


## 🛠️ Tech Stack

**Cloud / Infra:** AWS (EC2, S3, RDS, VPC, IAM, CloudWatch, EKS)

**IaC & Automation:** Terraform, Ansible, CloudFormation (familiar)

**CI/CD & DevOps:** Jenkins, GitHub Actions, Docker, Helm, Kubernetes (EKS)

**Monitoring & Logging:** Prometheus, Grafana, CloudWatch

**Languages & Scripting:** Python, Bash

---

## 📂 Projects (Highlights)

> Each project folder contains a README with setup steps, architecture diagram, and demo instructions.

### 1. MES Data Pipeline — AWS + Terraform + Ansible (mes-project)

**Stack:** AWS (S3, RDS), Terraform, Ansible, Docker, GitHub Actions, CloudWatch

Short: A simulated Manufacturing Execution System pipeline that collects simulated factory telemetry, stores raw data in S3 and structured records in RDS, and deploys via Terraform + Ansible with automated CI/CD. Includes CloudWatch metrics and alarms for observability.

**Repo:** `./mes-project` — see `README.md` inside for infra commands, architecture diagram (`/docs/mes-architecture.png`), and demo scripts to generate simulated sensor data.

---

### 2. Microservices on AWS (microservices-aws)

**Stack:** Java microservices, Docker, Kubernetes (EKS), Helm, Terraform, Jenkins

Short: End-to-end microservices deployment on AWS EKS with automated Jenkins pipelines, Helm charts, and HPA-based scaling.

**Repo:** `./microservices-aws` — includes Helm charts, Terraform infra modules, and CI config.

---

### 3. Hybrid CI/CD & Secure Pipeline (hybrid-ci-cd)

**Stack:** GitHub Actions, Jenkins, Trivy, Docker, ECR, EKS

Short: A hybrid CI/CD workflow demonstrating code scanning, container image build & signing, and automated deploys to EKS with rollback on failed checks.

**Repo:** `./hybrid-ci-cd` — contains pipeline YAMLs and example policies.

---

## 📋 How to run (example)

**Clone the repository:**

```bash
git clone https://github.com/<your-github>/faizan-devops-portfolio.git
cd mes-project
```

**Terraform (example):**

```bash
cd terraform
terraform init
terraform plan -var-file=envs/dev.tfvars
terraform apply -auto-approve -var-file=envs/dev.tfvars
```

**Ansible (bootstrap example):**

```bash
ansible-playbook -i inventory/prod.ini playbooks/deploy.yml --extra-vars "image_tag=latest"
```

**Generate demo data (simulator):**

```bash
cd collector
python3 simulator.py --rate 10
```

---

## 📈 Observability & Monitoring

Each project includes Prometheus scraping endpoints and Grafana dashboards (JSON in `/monitoring`) plus CloudWatch Logs/metrics integration. See `/monitoring/dashboards.json` for dashboard exports.

---

## ✅ Resume & Contact

* Resume: `Faizan_kaishar_DevOps_Engineer.pdf` (root) in this repo.
* Email: [faizankaishar95@gmail.com](mailto:faizankaishar95@gmail.com)
* LinkedIn: [https://www.linkedin.com/in/faizan-kaishar-5b53a7235](https://www.linkedin.com/in/faizan-kaishar-5b53a7235)

---
### GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=faiz1487&show_icons=true&count_private=true&theme=nightowl" />

    
</div>

--- 

## 🤝 Contribution & Feedback

I welcome feedback, issues, and PRs. If you want a live walkthrough or a short demo, reach out via email or LinkedIn and we can schedule a session.

---

## 📌 Notes & Roadmap

* Add Terraform modules for EKS (modularized) and sample IaC templates for production-grade security.
* Add demo GitHub Actions workflows with secrets and environment protection examples.
* Add architecture diagrams in `/docs` (PNG + draw.io source) and an interactive README with badges.

---

*Built with ❤️ by Faizan — aiming to bridge manufacturing automation with cloud-native DevOps practices.*
