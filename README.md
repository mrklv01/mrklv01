<h1 align="center">Hi, I'm Denis 👋</h1>
<h3 align="center">🖥️ Monitoring & Infrastructure Engineer · Astana, Kazakhstan</h3>
<p align="center"><i>"If it isn't monitored, it isn't in production."</i></p>

---

## 👨‍💻 About Me

* System administrator for a large organization (1000+ users): Active Directory, VMware, Veeam, mixed Linux / Windows server fleet
* Keeping infrastructure observable: servers, services, network, logs and security events
* Digging into incidents down to the root cause, not just the symptoms
* Turning manual routine into scripts, bots and alerts

---

## 🚀 Tech Stack

### Monitoring & Logging

* Zabbix 7.x (PostgreSQL / MySQL)
* Graylog 7.1 (OpenSearch + MongoDB)
* Winlogbeat
* Grafana (dashboard templates)
* Prometheus & Alertmanager
* SNMP (Cisco, Huawei)

### Virtualization & Backup

* VMware vSphere / vCenter
* Veeam Backup & Replication

### Systems & Services

* Windows Server
* Active Directory, Group Policy
* Windows DHCP (IP reservations)
* WSUS
* AD Certificate Services
* Microsoft Exchange 2016
* Oracle Linux / RHEL / Rocky Linux
* Debian / Ubuntu
* Apache HTTP Server, Nginx
* FreePBX / Asterisk
* Cisco CUCM (AXL / SOAP)
* ServiceDesk (ITSM)

### Automation & Scripting

* PowerShell (WinRM / PS Remoting, CIM / WMI, WinForms)
* Bash
* Python (pandas, openpyxl, BeautifulSoup, Telethon, zeep)
* JavaScript (Node.js)

### Networking

* MikroTik RouterOS 6 / 7 (LTE, L2TP/IPsec, DHCP, NAT)
* Cisco Catalyst, H3C Comware, VLAN / Voice VLAN
* TCP/IP fundamentals

---

## 🔐 Security & Access

* Active Directory security event detection (Event ID 4625, 4740, 4771)
* Account lockout and password expiry alerting
* Kaspersky Security Center, ESET PROTECT
* SSL/TLS and internal PKI (AD CS), JVM truststore management
* SSH key-only authentication (ed25519), PAM and sudo access via groups
* SELinux, firewalld
* Remote access rollout (UltraVNC via KSC)

---

## ☁️ Infrastructure & DevOps

* Linux Server Administration (systemd, cron, logrotate, LVM, chrony / NTP)
* Local package mirrors (dnf reposync, createrepo, GPG keys)
* Docker & Docker Compose
* Configuration as Code (provisioning)
* VPS Deployment
* Git
* Telegram-based alerting

---

## 🏗️ Engineering Experience

* Administered production **Zabbix** (92 hosts, ~26,000 metrics, ~11,500 triggers) and **Graylog** (~7 GB of logs per day)
* Performed sequential **Zabbix** (7.4.11 → 7.4.13) and **Graylog** (7.0.3 → 7.1.6) upgrades in production
* Built an automated patch updater for Graylog (service stop, update, datanode readiness wait, certificate reimport, cleanup)
* Found and fixed a local package mirror whose Oracle Linux repos had silently stopped syncing for over a year; rewrote the sync script, added Zabbix 7.4 repos, status logging and log rotation
* Moved 5 Linux servers to SSH key-only authentication with group-based PAM / sudo access
* Configured **Veeam** backup jobs, including application-aware guest processing for domain controllers
* Tuned Zabbix server caches after value cache overflow alerts
* Investigated recurring nightly server hangs and traced the root cause to the hypervisor level
* Wrote CPU / memory watchdog scripts based on CIM when standard perfmon counters were broken
* Ran a hardware audit of **~380 workstations** with PowerShell data collection and Excel reporting
* Deployed remote access software to user workstations via Kaspersky Security Center
* Built Telegram alert routing for Zabbix and Graylog with topic-based threads
* Migrated MikroTik configurations from RouterOS 6 to 7

---

## 📦 Featured Projects

* **[zabbix-telegram-router](https://github.com/mrklv01/zabbix-telegram-router)** - Zabbix webhook that routes alerts to Telegram topics based on tags, with a default fallback topic
* **[graylog-windows-security-detections](https://github.com/mrklv01/graylog-windows-security-detections)** - catalog of Windows Security detections in Graylog with Telegram notifications
* **[monitoring-stand](https://github.com/mrklv01/monitoring-stand)** - Prometheus + Grafana + Alertmanager stand in Docker (Windows + Linux VPS) with Telegram alerts
* **[support-toolkit](https://github.com/mrklv01/support-toolkit)** - PowerShell/WinForms GUI with 12 remote workstation admin operations (WinRM) and an audit log
* **[master-hr-predictive-analytics](https://github.com/mrklv01/master-hr-predictive-analytics)** - HR-Agent: burnout risk prediction from ITSM data (Next.js, TypeScript, LLM, PDF reports). Master's thesis project

---

## 🎓 Education & Certifications

* Master's degree, Esil University - thesis on intelligent predictive HR management agents using ITSM data
* Bachelor's degree in IT and Data Protection
* Cisco CCNA: Introduction to Networks

---

## 🎯 Areas of Interest

* Infrastructure Monitoring
* SIEM & Log Management
* Blue Team / Security Detections
* System Administration
* Automation
* Networking

---

## 📈 Currently Focused On

* Linux Administration
* VMware & Veeam
* Docker & Containerized Deployments
* Prometheus Stack
* SIEM & Observability

---

## 🌐 Connect with Me

💬 Telegram
https://t.me/mrklv_vn

💻 GitHub
https://github.com/mrklv01

---

> Always open to interesting infrastructure challenges, monitoring and SIEM projects, and opportunities to grow as an engineer.
