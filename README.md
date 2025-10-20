# 🛡️ Cybersecurity Projects Portfolio

Welcome! This is a hands-on portfolio showcasing real-world cybersecurity labs focused on **blue team automation**, **log parsing**, **SIEM simulation**, and **threat response** — all built in Python and Bash/PowerShell.

Each project reflects common tasks that SOC Analysts or Security Engineers might perform in live environments.

---

## 📁 Project Structure
cybersecurity-projects/
├── log-parser-alert/ # Detects brute force & suspicious activity in log files
├── siem-log-simulator/ # Generates fake Apache & auth logs for SIEM training
├── auto-ip-blocker/ # Automatically blocks IPs using system firewalls
├── screenshots/ # (Optional) Lab results, graphs, terminal views
└── README.md # Project index and overview


---

## 🔍 Project Descriptions

### 1. `log-parser-alert`
- 📚 Parses Apache or SSH logs
- 🔍 Detects brute-force attempts, suspicious URL access, or 404 anomalies
- 🛠️ Outputs alerts or suspicious IPs to file

### 2. `siem-log-simulator`
- 🎲 Simulates fake logs to feed into a SIEM (like Wazuh, Splunk, ELK)
- 🧪 Includes attack-mode for brute force, recon behavior
- 🔧 Great for testing alerting pipelines

### 3. `auto-ip-blocker`
- 🚫 Reads list of suspicious IPs and auto-blocks them via:
  - Linux `iptables`
  - Windows Firewall (PowerShell)
- 🧠 Designed for integration with log parser or threat intel feeds

---

## ⚙️ Tools & Languages
- 🐍 Python 3.11+
- 🐚 Bash scripting (Linux)
- 🪟 PowerShell scripting (Windows)
- 📄 Apache access logs, syslogs
- (Optional): Threat intel APIs (AbuseIPDB, VirusTotal)

---

## 🚀 Roadmap (Coming Soon)
- [ ] Add CLI options to all Python scripts (`argparse`)
- [ ] Create test logs and sample datasets
- [ ] Add Slack/email notification integration
- [ ] Dockerize SIEM simulator for quick labs
- [ ] Include YAML-based config for log simulator

---

## 👩🏽‍💻 About the Author

**Jennai Jordan** — Navy Veteran & Aspiring Cybersecurity Analyst  
Transitioning from Help Desk → Blue Team SOC | Passionate about automation, incident response, and hands-on learning.  
📍 Texas | [LinkedIn →](https://www.linkedin.com/in/jenjordan96)

---

## 🧠 Purpose of This Repo

To demonstrate the practical, real-world skills needed in roles like:

- SOC Analyst / Jr. Security Analyst
- Blue Team Engineer
- Cybersecurity Intern (Ops-focused)
- Security Automation Engineer (entry level)

---

## 🏷️ Tags

`#cybersecurity` `#python` `#SIEM` `#log-parsing` `#SOC` `#blue-team` `#automation` `#threat-detection`

---

> 💡 Tip: Keep each project self-contained with its own README, input files, and `requirements.txt` if needed.





