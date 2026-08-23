<div align="center">

# Kunal Waghmare

### DevOps Engineer · Platform Engineer · Site Reliability Engineer

**Cloud Infrastructure · Kubernetes · Terraform · GitOps · Observability · DevSecOps**

Building reliable, automated, and observable cloud-native platforms — from infrastructure provisioning to deployment, monitoring, incident response, and recovery.

<p>
  <a href="https://www.linkedin.com/in/kunal-waghmare-b48b1b226/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://devops-portfolio-chi.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="mailto:kunalwaghmare1207@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

</div>

---

## 👋 About Me

I'm a **DevOps / Platform Engineer with 3+ years of professional experience** building and operating cloud infrastructure, Kubernetes environments, CI/CD pipelines, and production-oriented reliability tooling.

My engineering focus sits at the intersection of:

```text
Cloud Infrastructure
        +
Kubernetes & Containers
        +
Infrastructure as Code
        +
GitOps & CI/CD
        +
Observability
        +
Security
        +
Site Reliability Engineering
```

I don't treat DevOps as a collection of tools.

I focus on the **engineering system around those tools** — how infrastructure is provisioned, applications are deployed, workloads are observed, failures are detected, incidents are investigated, and systems recover.

### What I build

* ☁️ Cloud infrastructure and Kubernetes platforms
* ⚙️ Infrastructure automation with Terraform
* 🚀 CI/CD and GitOps delivery pipelines
* 📊 Metrics, logs, traces, and operational dashboards
* 🔐 DevSecOps controls and runtime security
* 📈 SRE practices around SLI, SLO, error budgets, and incident response
* 🧩 Internal Developer Platform and platform engineering capabilities
* 💥 Failure testing and chaos engineering workflows

---

# 🧭 Engineering Focus

| Area                         | Technologies                                                                  |
| ---------------------------- | ----------------------------------------------------------------------------- |
| **Cloud**                    | AWS · EKS · EC2 · IAM · VPC · RDS · S3 · CloudWatch · GCP                     |
| **Infrastructure as Code**   | Terraform · Ansible                                                           |
| **Containers**               | Docker · Kubernetes · Helm · Kustomize                                        |
| **Platform Engineering**     | Internal Developer Platforms · Control Planes · Kubernetes Controllers · CRDs |
| **GitOps**                   | Argo CD                                                                       |
| **CI/CD**                    | GitHub Actions · Jenkins · GitLab CI                                          |
| **Observability**            | Prometheus · Grafana · Loki · Alertmanager · OpenTelemetry · ELK              |
| **Reliability**              | SLI · SLO · Error Budgets · Burn Rate · Incident Response                     |
| **Security**                 | Trivy · IAM · RBAC · NetworkPolicies · SecurityContexts · Secrets Management  |
| **Runtime Security**         | eBPF · Cilium Tetragon                                                        |
| **Autoscaling**              | Kubernetes HPA · KEDA                                                         |
| **Chaos Engineering**        | Chaos Mesh                                                                    |
| **Programming & Automation** | Go · Python · Bash · PowerShell · TypeScript · Node.js                        |
| **Operating Systems**        | Linux · Ubuntu · RHEL · Windows Server                                        |

---

# 🚀 Featured Engineering Projects

These projects represent the areas where I spend the most time experimenting, building, and developing deeper production-oriented engineering skills.

---

## 🏗️ OpsForge 2.0

### Internal Developer Platform · SRE · Cloud Native · DevSecOps

> **Build it. Deploy it. Observe it. Break it. Recover it.**

OpsForge 2.0 is a production-oriented **Internal Developer Platform and SRE engineering laboratory** designed to demonstrate how modern platform capabilities work together as a single system.

Instead of building isolated DevOps demos, OpsForge models the complete operational lifecycle:

```text
Code
 ↓
Test
 ↓
Security Scan
 ↓
Build
 ↓
Containerize
 ↓
Deploy
 ↓
Observe
 ↓
Detect
 ↓
Investigate
 ↓
Recover
 ↓
Learn
```

### Engineering capabilities

* Internal Developer Platform architecture
* Go-based control plane
* Kubernetes controller and reconciliation model
* Developer portal using React / TypeScript
* Kubernetes orchestration
* Terraform-based AWS infrastructure
* Crossplane-based infrastructure management
* Argo CD GitOps delivery
* KEDA event-driven autoscaling
* OpenTelemetry instrumentation
* Prometheus / Grafana / Loki observability
* Alertmanager alert routing
* Trivy security scanning
* RBAC and Kubernetes security controls
* Cilium Tetragon / eBPF runtime visibility
* SLI / SLO / Error Budget concepts
* Chaos Mesh failure experiments
* Python and PowerShell SRE automation

### Architecture

```text
Developer
   │
   ├───────────────┐
   ▼               ▼
Portal            CLI
React             Go
   │               │
   └───────┬───────┘
           ▼
     Go Control Plane
           │
     ┌─────┴─────┐
     ▼           ▼
PostgreSQL   K8s Controller
                 │
                 ▼
             Kubernetes
                 │
       ┌─────────┼─────────┐
       ▼         ▼         ▼
     ArgoCD     KEDA    Crossplane
       │
       ▼
    Workloads
       │
       ▼
OpenTelemetry
       │
 ┌─────┼──────────┐
 ▼     ▼          ▼
Prom  Grafana    Loki
       │
       ▼
  Alertmanager
```

**Repository:**
➡️ https://github.com/kunal-1207/OpsForge

---

# ⚔️ Valkyrie Platform

### AWS EKS · Terraform · GitOps · Observability · DevSecOps

Valkyrie is a production-oriented Kubernetes platform built around **Amazon EKS**, Infrastructure as Code, GitOps, and operational observability.

### Key capabilities

* AWS infrastructure provisioning with Terraform
* Amazon EKS
* Kubernetes workload management
* Helm-based application packaging
* GitHub Actions CI
* Argo CD GitOps delivery
* Prometheus and Grafana
* Loki log aggregation
* Alertmanager
* IAM / RBAC
* Trivy security scanning
* SRE-oriented operational monitoring

The project focuses on the complete path from **infrastructure → application → deployment → observability → operations**.

**Repository:**
➡️ https://github.com/kunal-1207/valkarie_platform

---

# ☁️ Cloud Native DevOps Platform

### Terraform · Kubernetes · Argo CD · Prometheus · GitOps

A production-style cloud-native platform demonstrating how infrastructure provisioning, Kubernetes orchestration, CI/CD, GitOps, and observability can be connected into a repeatable deployment workflow.

### Focus areas

* AWS infrastructure
* Terraform
* Kubernetes
* Docker
* GitHub Actions
* Argo CD
* Prometheus
* Grafana
* Deployment automation
* Operational visibility

**Repository:**
➡️ https://github.com/kunal-1207/cloud-native-devops-platform

---

# 🧠 Redis-Compatible Database

### Systems Programming · Networking · Concurrency

A Redis-compatible in-memory database implemented from scratch to explore the internals behind distributed caching systems.

### Engineering concepts explored

* RESP protocol
* TCP networking
* Socket programming
* Concurrent client handling
* GET / SET / DEL / TTL
* In-memory key-value storage
* Persistence
* Networking fundamentals

This project complements my infrastructure work by going deeper into the systems that infrastructure engineers ultimately operate.

**Repository:**
➡️ https://github.com/kunal-1207/redis-personal-project

---

# 🏥 Healthcare RCM Data Platform

### AWS · Terraform · ETL · Data Platform

A production-oriented cloud data platform focused on scalable healthcare Revenue Cycle Management workflows.

### Focus areas

* AWS
* Terraform
* ETL pipelines
* Cloud storage
* Data processing
* Medallion architecture
* Infrastructure automation

**Repository:**
➡️ https://github.com/kunal-1207/rcm-data-platform

---

# 🔬 Current Engineering Interests

I'm currently going deeper into the areas that sit beyond traditional CI/CD:

```text
Kubernetes
   │
   ├── Networking
   ├── Controllers & Operators
   ├── Autoscaling
   ├── Runtime Security
   └── Multi-Cluster Architecture
          │
          ▼
Platform Engineering
   │
   ├── Internal Developer Platforms
   ├── Self-Service Infrastructure
   ├── Developer Experience
   └── Control Planes
          │
          ▼
SRE
   │
   ├── Observability
   ├── SLOs
   ├── Error Budgets
   ├── Incident Response
   └── Chaos Engineering
```

Areas I'm actively exploring include:

* Kubernetes networking
* Platform engineering
* Internal Developer Platforms
* Distributed systems
* eBPF
* Runtime security
* Service mesh
* Advanced observability
* Cloud security
* Kubernetes controllers
* Event-driven infrastructure
* Reliability engineering

---

# 🛠️ How I Think About DevOps

I believe DevOps is not primarily about knowing more tools.

It's about building a system where engineering teams can move quickly **without sacrificing reliability, security, or operational visibility**.

My preferred engineering loop is:

```text
Automate
   ↓
Deploy
   ↓
Observe
   ↓
Measure
   ↓
Detect
   ↓
Investigate
   ↓
Recover
   ↓
Improve
```

A successful platform should make the **right engineering behavior the easiest behavior**.

---

# 📊 GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=kunal-1207&show_icons=true&hide_border=true&rank_icon=github&theme=transparent"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kunal-1207&layout=compact&hide_border=true&theme=transparent"/>

</div>

<br>

<div align="center">

<img src="https://streak-stats.demolab.com?user=kunal-1207&hide_border=true&theme=transparent"/>

</div>

---

# 🏅 Google Cloud Learning

Google Cloud skill badges covering:

* Terraform infrastructure
* Kubernetes application deployment
* DevOps workflows
* Cloud Operations monitoring and logging
* Managed Service for Prometheus
* Kubernetes application deployment workflows

---

# 📚 Engineering Domains

<div align="center">

### ☁️ Cloud

AWS · EKS · EC2 · IAM · VPC · RDS · S3 · GCP

### ☸️ Platform

Kubernetes · Docker · Helm · Kustomize · Argo CD · KEDA · Crossplane

### 🏗️ Infrastructure

Terraform · Ansible · Cloud Infrastructure · Infrastructure Automation

### 🔭 Observability

Prometheus · Grafana · Loki · Alertmanager · OpenTelemetry · ELK

### 🔐 Security

Trivy · IAM · RBAC · NetworkPolicies · SecurityContexts · eBPF

### 🚨 Reliability

SRE · SLI · SLO · Error Budgets · Burn Rate · Incident Response · Chaos Engineering

### 💻 Engineering

Go · Python · TypeScript · Node.js · Bash · PowerShell

</div>

---

# 🎯 What I'm Looking For

I'm particularly interested in engineering teams working on:

* **DevOps Engineering**
* **Site Reliability Engineering**
* **Platform Engineering**
* **Cloud Infrastructure**
* **Kubernetes Platform Engineering**
* **DevSecOps**

Especially environments where infrastructure is treated as an engineering product rather than simply an operational responsibility.

---

# 📫 Let's Connect

<div align="center">

<a href="https://devops-portfolio-chi.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-Visit%20Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/kunal-waghmare-b48b1b226/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:kunalwaghmare1207@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

<div align="center">

### **Build systems that are reliable enough to trust and observable enough to understand.**

**DevOps · Platform Engineering · Site Reliability Engineering**

</div>
