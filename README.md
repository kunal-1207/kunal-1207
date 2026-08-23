<div align="center">

# Kunal Waghmare

### DevOps Engineer | Site Reliability Engineer | Platform Engineer

**AWS · Kubernetes · Terraform · CI/CD · GitOps · Python · Observability · DevSecOps**

Building, automating, and operating reliable cloud-native infrastructure and Kubernetes platforms.

<p>
<a href="https://www.linkedin.com/in/kunal-waghmare-b48b1b226/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://devops-portfolio-chi.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-Visit-111111?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>
<a href="mailto:kunalwaghmare1207@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
</p>

</div>

---

## About

DevOps / Site Reliability Engineer with **3+ years of professional experience** designing, developing, automating, and operating cloud infrastructure, Kubernetes environments, CI/CD pipelines, and production-oriented engineering systems.

My core focus is the intersection of:

**Cloud Infrastructure + Kubernetes + Infrastructure as Code + CI/CD + GitOps + Observability + Security + Reliability Engineering**

I work across the software delivery lifecycle — from infrastructure provisioning and deployment automation to monitoring, troubleshooting, incident response, and continuous improvement.

```text
Provision → Build → Secure → Deploy → Observe → Diagnose → Recover → Improve
```

---

## Core Competencies

| Domain                     | Technologies / Practices                                                      |
| -------------------------- | ----------------------------------------------------------------------------- |
| **Cloud**                  | AWS · Amazon EKS · EC2 · VPC · IAM · RDS · S3 · CloudWatch · GCP              |
| **Infrastructure as Code** | Terraform · Ansible                                                           |
| **Containers**             | Docker · Kubernetes · Helm · Kustomize                                        |
| **CI/CD**                  | GitHub Actions · Jenkins · GitLab CI                                          |
| **GitOps**                 | Argo CD                                                                       |
| **Platform Engineering**   | Internal Developer Platforms · Control Planes · Kubernetes Controllers · CRDs |
| **Observability**          | Prometheus · Grafana · Loki · Alertmanager · OpenTelemetry · ELK              |
| **SRE**                    | SLI · SLO · Error Budgets · Burn Rate · Incident Response · Runbooks          |
| **Security**               | Trivy · IAM · RBAC · NetworkPolicies · SecurityContexts                       |
| **Runtime Security**       | eBPF · Cilium Tetragon                                                        |
| **Autoscaling**            | HPA · KEDA                                                                    |
| **Chaos Engineering**      | Chaos Mesh                                                                    |
| **Programming**            | Python · Go · Bash · PowerShell · TypeScript · Node.js                        |
| **Operating Systems**      | Linux · Ubuntu · RHEL · Windows Server                                        |

---

# Engineering Experience

### DevOps · SRE · Cloud Infrastructure

My engineering experience covers:

* **Designed and developed** automated infrastructure provisioning using Infrastructure as Code.
* **Implemented and maintained** Kubernetes-based application environments.
* **Developed and integrated** CI/CD pipelines for repeatable application delivery.
* **Implemented** GitOps workflows using Argo CD.
* **Configured and operated** monitoring and observability platforms using Prometheus, Grafana, Loki, Alertmanager, and OpenTelemetry.
* **Analyzed and diagnosed** infrastructure, deployment, application, and Kubernetes issues.
* **Investigated and resolved** operational failures through structured troubleshooting.
* **Automated** repetitive infrastructure and operational workflows using Python, Bash, PowerShell, and Go.
* **Implemented** security controls across cloud and Kubernetes environments.
* **Evaluated and improved** reliability using operational metrics, SLI/SLO concepts, alerting, and failure analysis.
* **Collaborated** across development and infrastructure workflows to improve deployment and operational processes.
* **Standardized** infrastructure and deployment workflows to improve repeatability and reduce manual intervention.

---

# Featured Engineering

## 🏗️ OpsForge 2.0

### Internal Developer Platform · SRE · Cloud Native · DevSecOps

> **Build it. Deploy it. Observe it. Break it. Recover it.**

OpsForge 2.0 is a production-oriented **Internal Developer Platform and SRE engineering laboratory** designed to demonstrate how modern cloud-native engineering capabilities operate as one system.

The platform brings together:

**AWS · Terraform · Kubernetes · GitOps · CI/CD · Observability · Security · Autoscaling · SRE · Chaos Engineering**

### Engineering Lifecycle

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
```

### Platform Architecture

```text
Developer
   │
   ├───────────────┐
   ▼               ▼
Web Portal        Go CLI
   │               │
   └───────┬───────┘
           ▼
    Go Control Plane
           │
     ┌─────┴─────┐
     ▼           ▼
PostgreSQL   Kubernetes
                 Controller
                     │
                     ▼
                Kubernetes
                     │
       ┌─────────────┼─────────────┐
       ▼             ▼             ▼
    Argo CD         KEDA       Crossplane
       │
       ▼
   Application Workloads
       │
       ▼
 OpenTelemetry
       │
 ┌─────┼────────────┐
 ▼     ▼            ▼
Prom  Grafana      Loki
       │
       ▼
  Alertmanager
```

### What the project demonstrates

**Platform Engineering**

* Internal Developer Platform architecture
* Go control plane
* Kubernetes controller
* CRDs
* Reconciliation
* Developer portal
* Go CLI
* Self-service platform workflows

**Cloud Infrastructure**

* AWS
* Amazon EKS
* VPC
* IAM
* RDS
* S3
* Terraform
* Crossplane

**Delivery Engineering**

* GitHub Actions
* Jenkins
* Argo CD
* Helm
* Kustomize
* GitOps

**Observability**

* OpenTelemetry
* Prometheus
* Grafana
* Loki
* Alertmanager
* Jaeger

**Security**

* Trivy
* RBAC
* NetworkPolicies
* SecurityContexts
* Cilium Tetragon
* eBPF runtime visibility

**Reliability**

* Golden Signals
* SLI / SLO
* Error Budgets
* Burn Rate
* Incident Response
* Chaos Mesh
* Failure recovery

### Engineering problems explored

* **Designed** a platform control-plane architecture.
* **Developed** Kubernetes controller and reconciliation workflows.
* **Automated** cloud infrastructure provisioning.
* **Integrated** GitOps-based application delivery.
* **Implemented** centralized metrics, logs, and traces.
* **Configured** event-driven autoscaling with KEDA.
* **Analyzed** Kubernetes and infrastructure state.
* **Investigated** deployment and runtime failures.
* **Tested** controlled failure scenarios with Chaos Mesh.
* **Measured** reliability signals through SLI/SLO concepts.
* **Implemented** security controls across the platform.

**Repository →** https://github.com/kunal-1207/OpsForge

---

# ⚔️ Valkyrie Platform

### AWS EKS · Terraform · Kubernetes · GitOps · Observability

Valkyrie is a production-oriented Kubernetes platform focused on **AWS infrastructure, container orchestration, automated delivery, observability, and DevSecOps**.

### Key Engineering Work

* **Designed** AWS infrastructure using Terraform.
* **Provisioned** Amazon EKS infrastructure.
* **Developed** Kubernetes deployment workflows.
* **Integrated** GitHub Actions CI pipelines.
* **Implemented** GitOps delivery with Argo CD.
* **Configured** Helm-based application deployments.
* **Integrated** Prometheus and Grafana monitoring.
* **Implemented** Loki log aggregation.
* **Configured** Alertmanager.
* **Applied** IAM and RBAC security controls.
* **Integrated** Trivy security scanning.
* **Analyzed** operational metrics and application health.

**Repository →** https://github.com/kunal-1207/valkarie_platform

---

# ☁️ Cloud Native DevOps Platform

### AWS · Terraform · Kubernetes · CI/CD · GitOps

A cloud-native DevOps platform demonstrating infrastructure provisioning, container orchestration, CI/CD automation, GitOps delivery, and observability.

### Focus

* AWS infrastructure
* Terraform
* Kubernetes
* Docker
* GitHub Actions
* Argo CD
* Prometheus
* Grafana
* CI/CD automation
* GitOps workflows

**Repository →** https://github.com/kunal-1207/cloud-native-devops-platform

---

# 🧠 Redis-Compatible Database

### Systems Engineering · Networking · Concurrency

A Redis-compatible in-memory database **developed from scratch** to explore networking, protocols, concurrency, and storage fundamentals.

### Implemented

* RESP protocol
* TCP socket server
* Concurrent client handling
* GET / SET / DEL / TTL
* Key-value storage
* Persistence
* Networking fundamentals

**Repository →** https://github.com/kunal-1207/redis-personal-project

---

# 🏥 Healthcare RCM Data Platform

### AWS · Terraform · ETL · Cloud Data Engineering

A production-oriented cloud data platform developed around healthcare Revenue Cycle Management workflows.

### Engineering Areas

* AWS
* Terraform
* ETL pipelines
* Data processing
* Cloud storage
* Medallion architecture
* Infrastructure automation

**Repository →** https://github.com/kunal-1207/rcm-data-platform

---

# 🔭 Observability & Reliability

I treat observability as an engineering capability rather than simply a monitoring stack.

### Signals

**Latency · Traffic · Errors · Saturation**

### Telemetry

**Metrics · Logs · Traces**

### Tooling

**Prometheus · Grafana · Loki · OpenTelemetry · Alertmanager · CloudWatch**

### Reliability Model

```text
SLI
 ↓
SLO
 ↓
Error Budget
 ↓
Burn Rate
 ↓
Alert
 ↓
Incident
 ↓
Investigation
 ↓
Recovery
 ↓
Improvement
```

---

# 🔐 Security & DevSecOps

Security is integrated into infrastructure, delivery, Kubernetes, and runtime operations.

### Security Practices

* Vulnerability scanning
* Container image scanning
* Infrastructure configuration scanning
* IAM
* RBAC
* Least-privilege access
* NetworkPolicies
* SecurityContexts
* Kubernetes security
* Runtime visibility
* eBPF

### Tooling

**Trivy · IAM · RBAC · Cilium Tetragon · eBPF**

---

# 🧪 Failure Engineering

Reliable systems should be tested under failure, not only demonstrated during successful deployments.

OpsForge explores:

```text
Application Failure
       ↓
Detection
       ↓
Recovery

Queue Overload
       ↓
KEDA Scaling
       ↓
Queue Drain

Bad Deployment
       ↓
Error Detection
       ↓
Investigation
       ↓
Rollback

Pod Failure
       ↓
Rescheduling
       ↓
Service Recovery
```

Chaos Mesh is used for controlled Kubernetes failure experiments.

---

# 🛠️ Technology Stack

### Cloud & Infrastructure

`AWS` · `Amazon EKS` · `EC2` · `VPC` · `IAM` · `RDS` · `S3` · `CloudWatch` · `GCP`

### Infrastructure as Code & Configuration

`Terraform` · `Ansible`

### Containers & Kubernetes

`Docker` · `Kubernetes` · `Amazon EKS` · `Helm` · `Kustomize`

### CI/CD & GitOps

`GitHub Actions` · `Jenkins` · `GitLab CI` · `Argo CD`

### Observability & Monitoring

`Prometheus` · `Grafana` · `Loki` · `Alertmanager` · `OpenTelemetry` · `ELK` · `CloudWatch` · `Jaeger`

### Security & DevSecOps

`Trivy` · `IAM` · `RBAC` · `NetworkPolicies` · `SecurityContexts` · `Secrets Management` · `eBPF` · `Cilium Tetragon`

### Reliability & Platform Engineering

`SRE` · `SLI` · `SLO` · `Error Budgets` · `Burn Rate` · `Incident Response` · `Runbooks` · `Chaos Engineering` · `Chaos Mesh` · `KEDA` · `Crossplane`

### Programming & Automation

`Python` · `Go` · `Bash` · `PowerShell` · `TypeScript` · `Node.js` · `Groovy`

### Operating Systems

`Linux` · `Ubuntu` · `RHEL` · `Windows Server`


---

# 🏅 Google Cloud

Google Cloud skill-badge experience includes:

* Terraform infrastructure
* Kubernetes application deployment
* DevOps workflows
* Cloud Operations monitoring and logging
* Managed Service for Prometheus

---

# 🔬 Currently Exploring

My current engineering focus is expanding from traditional DevOps into **Platform Engineering and advanced SRE**.

* Kubernetes networking
* Kubernetes controllers and operators
* Internal Developer Platforms
* Platform APIs
* eBPF
* Runtime security
* Service mesh
* Distributed systems
* Advanced observability
* Event-driven architecture
* Multi-cluster Kubernetes
* Cloud security
* Chaos engineering
* Reliability automation

---

# 🎯 Open to Opportunities

I'm interested in:

**DevOps Engineer · Site Reliability Engineer · Platform Engineer · Cloud Infrastructure Engineer · DevSecOps Engineer**

Particularly within teams building and operating:

**AWS · Kubernetes · Terraform · CI/CD · GitOps · Cloud Infrastructure · Observability · Platform Engineering**

I bring a combination of:

```text
Infrastructure Automation
        +
Kubernetes Operations
        +
CI/CD & GitOps
        +
Observability
        +
Security
        +
Reliability Engineering
        +
Hands-on Troubleshooting
```

---

# 📊 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kunal-1207&show_icons=true&hide_border=true&rank_icon=github&theme=transparent"/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kunal-1207&layout=compact&hide_border=true&theme=transparent"/>

</div>

---

# 📫 Connect

<div align="center">

<a href="https://devops-portfolio-chi.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-Visit-111111?style=for-the-badge&logo=vercel&logoColor=white"/>
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

### **Automate the infrastructure. Observe the system. Engineer the reliability.**

**DevOps · SRE · Platform Engineering · Cloud Infrastructure**

</div>
