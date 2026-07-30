# Hi, I'm Onyedika 👋

### Platform & Cloud Engineer — building the paved roads other engineers ship through

I design and operate production-grade platforms on AWS: self-service delivery, GitOps, and the reliability practices that keep systems running. I don't just follow tutorials — I build real infrastructure end to end. DevOps is the foundation I work from; platform engineering is the direction I'm building toward.

---

## 🛠️ Core Stack

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🚀 What I'm Building

My portfolio runs on two tracks — **platform** (the systems engineers deliver through) and **reliability** (making sure those systems hold up).

### Platform

**TaskFlow — Multi-Environment CI/CD Platform**
A self-service deployment platform on Amazon EKS: one Helm chart promoted across dev, staging, and production through an ArgoCD ApplicationSet, with GitHub Actions CI (OIDC, no long-lived keys), Trivy image scanning, OPA policy gates, and automated rollback. All AWS infrastructure — VPC, EKS, ExternalDNS, ACM, Route 53 — provisioned with Terraform. Not a pipeline for one app: a templated, guardrailed delivery road other engineers can follow.
`Terraform` · `EKS` · `ArgoCD` · `Helm` · `GitHub Actions` · `OPA` · `Trivy`

### Reliability

**Kubernetes Incident Response Lab**
Eight production-realistic failure scenarios — ImagePullBackOff, CrashLoopBackOff, OOMKilled, CPU throttling, network latency, DNS failure, node loss, and a compound cascading failure — each run through a Break → Detect → Fix → Improve loop with Chaos Mesh, Prometheus, and Grafana. Along the way I found and fixed a real PromQL label bug in a Grafana dashboard that had been silently reporting wrong data.
`Chaos Mesh` · `Prometheus` · `Grafana` · `EKS`

**Full Observability Stack** *(in progress)*
End-to-end observability with OpenTelemetry instrumentation, the Grafana LGTM stack (Loki, Tempo, Mimir), and SLO-based burn-rate alerting routed to Slack and email.
`OpenTelemetry` · `Grafana LGTM` · `Prometheus` · `Terraform`

**Next up:** a Backstage Internal Developer Portal, then self-service infrastructure with Crossplane — completing the internal developer platform story.

---

## ✍️ I Write About What I Build

I document each project in depth — architecture, decisions, and the things that broke along the way.

📝 **Hashnode:** [onyiglobal2025.hashnode.dev](https://onyiglobal2025.hashnode.dev)

---

## 📫 Connect

🔗 **LinkedIn:** [linkedin.com/in/onyedika-okoro](https://www.linkedin.com/in/onyedika-okoro/)
🌐 **Portfolio:** [onyiglobal2025.github.io](https://onyiglobal2025.github.io)

*Open to Platform Engineer, Cloud Engineer, SRE, and DevOps roles — remote-friendly.*
