# 👋 Hello, I'm Alex

IAM Engineer focused on **Identity, Security Engineering, and Infrastructure Automation**.

I enjoy building systems that are **secure, observable, and reproducible** using tools like Terraform, Linux, and modern cloud platforms.

Outside of work I build **homelab infrastructure, SIEM systems, and developer tools** to explore security, monitoring, and automation.

---

# 🔐 Areas of Focus

- Identity & Access Management
- Security Engineering
- Detection Engineering / SIEM
- Infrastructure as Code
- Homelab Automation
- Backend Development (Go)

---

# 🧰 Technology Stack

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash)

### Infrastructure

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux)

### IAM & Security

![Okta](https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta)
![Azure](https://img.shields.io/badge/Microsoft%20Entra-0078D4?style=for-the-badge)
![Active Directory](https://img.shields.io/badge/Active%20Directory-003366?style=for-the-badge)
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-blue?style=for-the-badge)

### Observability

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus)
![Loki](https://img.shields.io/badge/Loki-000000?style=for-the-badge)

---

# 🚀 Featured Projects

### 📚 Chronicle
Go CLI tool that collects **book metadata via ISBN** and stores it in a database used for **Grafana dashboards and reading analytics**.

Features:

- ISBN normalization
- Metadata ingestion
- PostgreSQL storage
- Grafana visualization

---

### 🔍 SIEM Project

Personal **Wazuh-based SIEM lab** used to explore:

- detection engineering
- log ingestion
- security monitoring
- alert pipelines

---

### 🧠 Terraform Homelab Infrastructure

Infrastructure-as-Code driven homelab split across multiple roles:

- **Domhain (Raspberry Pi):** lightweight edge services such as AdGuard and Caddy
- **Drassil:** main hybrid machine acting as media server, Steam machine, and sandbox host
- **Ardan (VPS):** monitoring, security, and operational tooling such as Grafana, Wazuh, Dozzle, and Beszel

This allows me to separate:

- network edge services
- monitoring and security tooling
- media and experimental workloads

All infrastructure is designed to be reproducible and easy to evolve over time.
---

# 🖥 Homelab Architecture

```mermaid
flowchart LR

Internet --> Cloudflare

Cloudflare --> Ardan
Cloudflare --> Domhain

subgraph ArdanVPS["Ardan · VPS / Monitoring & Security"]
    Ardan[Ardan]
    Ardan --> Grafana
    Ardan --> Wazuh
    Ardan --> Dozzle
    Ardan --> Beszel
    Ardan --> OtherOps[Other Ops Services]
end

subgraph DomhainPi["Domhain · Raspberry Pi / Edge Services"]
    Domhain[Domhain]
    Domhain --> AdGuard
    Domhain --> Caddy
end

subgraph DrassilHost["Drassil · Main Host / Media & Sandbox"]
    Drassil[Drassil]
    Drassil --> MediaServer[Media Services]
    Drassil --> SteamMachine[Steam Machine]
    Drassil --> BookSandbox[Book DB Sandbox]
    Drassil --> DockerSandbox[Additional Docker Services]
end

Domhain --> Drassil
Ardan --> Drassil
```

---

# 📈 Security & Monitoring Stack

My monitoring and detection pipeline includes:

| Component | Purpose |
|--------|--------|
| Wazuh | SIEM / Threat Detection |
| Grafana | Observability dashboards |
| Prometheus | Metrics collection |
| Loki | Log aggregation |
| Terraform | Infrastructure provisioning |
| Docker | Service orchestration |

---

# 📊 Development Activity

<p align="center">
<a href="https://github.com/anuraghazra/github-readme-stats">
<img src="https://github-readme-stats.vercel.app/api?username=avoinescu&show_icons=true&theme=tokyonight" />
</a>
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=avoinescu&theme=tokyonight" />
</p>

---

# ⚡ Coding Activity

<p align="center">
<a href="https://wakatime.com/@anubis619">
<img width="500" src="https://wakatime.com/share/@anubis619/d62dfefc-3dee-4d20-8681-d38b8d88bdee.svg" />
</a>
</p>

---

# 🌱 Currently Learning

- Go development for CLI tools
- Detection engineering
- Security architecture
- Advanced Terraform workflows

---

# 🐍 Contribution Graph

<p align="center">
  <img src="https://github.com/anubis619/anubis619/blob/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>

---

# 📫 Connect With Me

GitHub:  
https://github.com/anubis619
