# 🛠️ Jeevan S | Systems, Cloud & DevOps Infrastructure Engineer

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Jeev15offx&style=flat-square&color=blue&label=Profile+Views" alt="Visitor Count" />
  <img src="https://img.shields.io/badge/Status-Actively+Seeking+Internships-brightgreen?style=flat-square" alt="Status" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Kernel+Diagnostics+%7C+Docker+%7C+Prometheus;Automating+Bare-Metal+%26+Cloud+Labs;Building+Resilient+High-Availability+Labs;Linux+Systems+%26+Network+Engineer" alt="Typing SVG" /></a>
</p>

<p align="center">
  <strong>Targeting: Cloud Engineer Intern | DevOps Engineer Intern | Platform Engineer Intern | SRE Intern</strong>
</p>

<p align="center">
  <a href="https://linkedin.com/in/jeevan-s" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:jeevan.s.devops@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Jeev15offx">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

## 👤 Executive Profile & Core Philosophy

I am a systems-focused infrastructure engineer based in **Tamil Nadu, India**. My technical journey is anchored in the belief that software is only as good as the runtime infrastructure supporting it. I specialize in bare-metal hypervisors, container boundaries, local and cloud networks, and deep-dive operating system diagnostics.

*   🎯 **Aspiration:** To design, build, monitor, and scale infrastructure platforms that achieve 99.99% availability.
*   📖 **Daily Routine:** Writing automation scripts, simulating kernel crash recovery scenarios, tracing TCP packets, and building decoupled application platforms.
*   🛡️ **Key Principle:** Zero-Trust networking, declarative infrastructure definitions, and high-fidelity observability pipelines.

---

## 🛠️ Unified Technology Index

<table align="center" width="100%">
  <tr>
    <td align="center" width="20%" bgcolor="#0f172a">
      <strong>💻 Linux & Systems</strong>
    </td>
    <td align="center" width="20%" bgcolor="#0f172a">
      <strong>📦 Containers & IaC</strong>
    </td>
    <td align="center" width="20%" bgcolor="#0f172a">
      <strong>☁️ Cloud Platforms</strong>
    </td>
    <td align="center" width="20%" bgcolor="#0f172a">
      <strong>📊 Observability</strong>
    </td>
    <td align="center" width="20%" bgcolor="#0f172a">
      <strong>🛠️ CI/CD & Languages</strong>
    </td>
  </tr>
  <tr>
    <td align="left" valign="top">
      • Linux kernel tuning<br/>
      • Systemd unit design<br/>
      • Bash automation<br/>
      • LVM & filesystem mgmt<br/>
      • Process limits (`ulimit`)
    </td>
    <td align="left" valign="top">
      • Docker runtime boundary<br/>
      • Docker Compose stacks<br/>
      • Kubernetes (kubeadm)<br/>
      • Network policies (Calico)<br/>
      • Terraform providers
    </td>
    <td align="left" valign="top">
      • AWS Core (VPC subnets)<br/>
      • Route53 DNS configurations<br/>
      • AWS IAM role matrices<br/>
      • AWS EC2/S3 lifecycle policies<br/>
      • Hybrid cloud endpoints
    </td>
    <td align="left" valign="top">
      • Prometheus TSDB scaling<br/>
      • Grafana dashboards<br/>
      • cAdvisor runtime metrics<br/>
      • Node Exporter configurations<br/>
      • Alertmanager pipelines
    </td>
    <td align="left" valign="top">
      • Python automation scripts<br/>
      • Git version trees<br/>
      • GitHub Actions workflows<br/>
      • Cron automation<br/>
      • REST APIs integration
    </td>
  </tr>
</table>

---

## 🗄️ Deep Dive: Comprehensive Project Registry & Runbooks

Here are complete technical rundowns of the infrastructure stacks, monitoring topologies, and troubleshooting configurations I have actively designed, implemented, and verified.

### 🖥️ Stack 1: Home Server DevOps Lab (Local Infrastructure Engine)
A bare-metal development environment hosted locally, configured using containerized stacks, virtual network bridges, and persistent storage layers.

```text
                               +----------------------------------------+
                               |              Physical Host             |
                               |          OS: Ubuntu Server LTS         |
                               +----------------------------------------+
                                                   |
                                                   v
                            +----------------------------------------------+
                            |       Docker Engine Daemon Layer (Bridge)    |
                            +----------------------------------------------+
                                |                  |                 |
                                v                  v                 v
                    +--------------------+ +---------------+ +-----------------+
                    | Private DNS Engine | | Web Interface | | Storage Volumes |
                    |      Pi-hole       | |   Portainer   | | Local Bind/NFS  |
                    +--------------------+ +---------------+ +-----------------+
