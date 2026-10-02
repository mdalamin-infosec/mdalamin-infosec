<div align="center">

# MD AL AMIN

### Junior SOC Analyst | Blue Team | Detection Engineering | Network Security

CSE undergraduate at **American International University-Bangladesh (AIUB)** building hands-on defensive security projects around **SIEM monitoring, threat detection, network traffic analysis, Active Directory security, incident investigation, and detection engineering**.

I work with **Wazuh, Elastic Stack, Suricata, Sysmon, Wireshark, Sigma, Nmap, Python, Bash, Linux, and Windows telemetry** to reproduce attacks, analyze evidence, build detections, and document response workflows.

`Alert Triage` • `Log Analysis` • `PCAP Investigation` • `Threat Hunting` • `Detection Engineering` • `MITRE ATT&CK` • `Incident Response`

<br>

<a href="https://linkedin.com/in/mdalamin-infosec">
  <img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:mdalamin022612@gmail.com">
  <img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/mdalamin-infosec">
  <img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=58A6FF" />
</a>

</div>

---

## 🔬 SELECTED SECURITY PROJECTS

<table>
<tr>
<td width="50%" valign="top">

### 🏰 Active Directory Attack & Defense Lab

**GOAD • Sysmon • Wazuh • MITRE ATT&CK**

Built a **1-host, 3-VM Game of Active Directory lab** and executed **10+ controlled attack scenarios**, including:

- Kerberoasting
- Pass-the-Hash
- Privilege escalation
- Post-exploitation activity
- Windows authentication abuse

Collected and investigated telemetry using **Sysmon + Wazuh**, then mapped activity to relevant **MITRE ATT&CK** techniques.

**Evidence to include in repository**

`Attack Timeline` • `Wazuh Alerts` • `Sysmon Events` • `ATT&CK Mapping` • `Detection Logic` • `Remediation`

</td>

<td width="50%" valign="top">

### 🎯 Detection Engineering Lab

**Sigma • Suricata • SIEM Tuning**

Authored:

- **15 Sigma rules**
- **8 Suricata rules**
- **23 total custom detections**

Tested detections against simulated attacks and documented a **95% detection rate** in the lab environment.

Performed alert tuning to reduce documented false positives by **30%**.

**Evidence to include in repository**

`Detection Rules` • `Test Cases` • `True/False Positives` • `ATT&CK Mapping` • `Tuning Notes`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📡 Real-Time Network Threat Detection

**Suricata • Elastic Stack • Kibana**

Built a network monitoring pipeline for real-time security visibility:

```text
Network Traffic
      ↓
Suricata
      ↓
EVE JSON
      ↓
Elastic Stack
      ↓
Kibana
      ↓
Alert Triage
      ↓
Investigation
      ↓
Incident Response
```

Created Kibana dashboards and an incident-response workflow for investigating suspicious network activity.

Documented a **40% reduction in investigation time** within the lab workflow.

**Evidence to include in repository**

`Architecture` • `Suricata Alerts` • `Kibana Dashboard` • `PCAP Analysis` • `Incident Report`

</td>

<td width="50%" valign="top">

### 🔎 Enterprise Vulnerability Scanner

**Python • Nmap • NIST**

Built an automated Nmap/Python assessment workflow for a **4-host simulated enterprise network**.

The lab identified **70+ CVEs** and mapped findings against security-risk criteria.

**Evidence to include in repository**

`Scanner Code` • `Nmap Results` • `CVE Findings` • `Risk Prioritization` • `Remediation`

</td>
</tr>
</table>

> **Note:** Each repository should contain screenshots, logs, sample alerts, detection files, investigation notes, reproduction steps, limitations, and remediation guidance so every metric shown above is independently verifiable.

---

## 🛡️ SOC & BLUE TEAM CAPABILITIES

| Area | Hands-on Focus |
|---|---|
| **Security Monitoring** | SIEM monitoring, alert triage, log analysis, event correlation |
| **Network Security** | Packet analysis, IDS/IPS, TCP/IP analysis, traffic investigation |
| **Endpoint Telemetry** | Sysmon, Windows Event Logs, suspicious process/activity investigation |
| **Detection Engineering** | Sigma rules, Suricata rules, detection validation, alert tuning |
| **Threat Hunting** | IOC investigation, suspicious behavior analysis, ATT&CK-based hunting |
| **Incident Response** | Triage, investigation, evidence collection, response playbooks |
| **Active Directory Security** | Kerberoasting, Pass-the-Hash, privilege escalation, attack telemetry |
| **Vulnerability Management** | Network discovery, CVE identification, risk prioritization |
| **Security Automation** | Python and Bash scripts for repeatable security workflows |

---

## ⚙️ TECHNICAL STACK

### SIEM / Security Monitoring

<p>
<img src="https://img.shields.io/badge/Wazuh-Security%20Monitoring-005571?style=flat-square" />
<img src="https://img.shields.io/badge/Elastic-SIEM-0D1117?style=flat-square&logo=elastic&logoColor=00E5FF" />
<img src="https://img.shields.io/badge/Kibana-Dashboard-0D1117?style=flat-square&logo=kibana&logoColor=white" />
</p>

### Network Security & Traffic Analysis

<p>
<img src="https://img.shields.io/badge/Suricata-IDS%20%2F%20IPS-0D1117?style=flat-square" />
<img src="https://img.shields.io/badge/Wireshark-Packet%20Analysis-2563EB?style=flat-square&logo=wireshark&logoColor=white" />
<img src="https://img.shields.io/badge/tcpdump-Traffic%20Analysis-0D1117?style=flat-square" />
<img src="https://img.shields.io/badge/Nmap-Network%20Discovery-7C3AED?style=flat-square" />
<img src="https://img.shields.io/badge/iptables-Firewall-0D1117?style=flat-square&logo=linux&logoColor=F7DF1E" />
</p>

### Detection & Endpoint

<p>
<img src="https://img.shields.io/badge/Sigma-Detection%20Rules-7C3AED?style=flat-square" />
<img src="https://img.shields.io/badge/Sysmon-Windows%20Telemetry-2563EB?style=flat-square&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/MITRE%20ATT%26CK-Threat%20Mapping-0D1117?style=flat-square" />
</p>

### Scripting / Systems

<p>
<img src="https://skillicons.dev/icons?i=python,bash,linux,kali,ubuntu,git,github,cpp,rust&perline=9" />
</p>

**Also familiar with:** Active Directory • Metasploit • John the Ripper • Cisco Packet Tracer • NIST • ISO 27001

---

## 🔍 INVESTIGATION WORKFLOW

```text
TELEMETRY
    ↓
DETECT
    ↓
TRIAGE
    ↓
INVESTIGATE
    ↓
MAP TO ATT&CK
    ↓
RESPOND
    ↓
TUNE DETECTION
```

For every security lab, I aim to document:

```text
1. Scenario / Threat
2. Lab Architecture
3. Telemetry Sources
4. Event Generation
5. Alert / Detection
6. Investigation Timeline
7. Evidence & IOCs
8. MITRE ATT&CK Mapping
9. Response / Remediation
10. False Positives & Limitations
11. Detection Improvements
```

---

## 💼 EXPERIENCE

### Cyber Security Intern — CodeAlpha
**Sep 2026 – Oct 2026**

- Developed a Python network sniffer for real-time traffic capture and analysis.
- Performed secure code reviews and vulnerability assessments.
- Configured and monitored a Suricata-based IDS.
- Investigated suspicious network activity and documented security findings.

---

## 🧪 SECURITY LABS & EXPLOITATION PRACTICE

### Web & System Exploitation
- Drupal 7 / DC-1 VulnHub CTF
- Privilege escalation
- Post-exploitation analysis

### Kernel Exploitation
- Reproduced **Dirty COW — CVE-2016-5195** in a controlled Metasploitable2 lab.
- Documented root privilege escalation behavior.

### Credential & Web Security Testing
- Password-strength testing against vulnerable FTP/vsftpd services.
- Metasploit and John the Ripper practice.
- SQL injection testing and data extraction using DVWA.

> Offensive techniques shown here are performed only in controlled lab environments to understand attacker behavior and improve defensive detection.

---

## 🎓 EDUCATION

**American International University-Bangladesh (AIUB)**  
B.Sc. in Computer Science & Engineering  
Expected Graduation: **May 2027**

---

## 📚 CERTIFICATIONS & TRAINING

- **IBM Cybersecurity Assessment: CompTIA Security+ & CySA+ Prep** — Coursera, 2026
- **Fortinet NSE 1**
- **Fortinet NSE 2**
- **Fortinet NSE 3**
- **FortiGate 7.6 Operator**
- **Junior Cybersecurity Analyst Career Path** — Cisco Networking Academy, 2026
- **Mastercard Cybersecurity Job Simulation** — Forage, 2026
- **Commonwealth Bank Introduction to Cybersecurity Job Simulation** — Forage, 2026

Currently preparing for:

`CompTIA Security+` • `TryHackMe SOC Level 1`

---

## 📊 GITHUB ACTIVITY

<p align="center">
  <img
    width="68%"
    src="https://streak-stats.demolab.com?user=mdalamin-infosec&hide_border=true&background=0D1117&stroke=30363D&ring=8250DF&fire=8250DF&currStreakNum=8250DF&sideNums=0969DA&currStreakLabel=8250DF&sideLabels=0969DA&dates=238636"
  />
</p>

<details>
<summary><b>Language Statistics</b></summary>

<br>

<div align="center">

<table>
<tr>
<td width="50%" align="center">
<img
width="100%"
src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=mdalamin-infosec&theme=github_dark"
/>
</td>

<td width="50%" align="center">
<img
width="100%"
src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=mdalamin-infosec&theme=github_dark"
/>
</td>
</tr>
</table>

</div>

</details>

---

## 🌐 CONNECT

<div align="center">

<a href="https://linkedin.com/in/mdalamin-infosec">
<img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="mailto:mdalamin022612@gmail.com">
<img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://github.com/mdalamin-infosec">
<img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=58A6FF" />
</a>

<br><br>

### `TELEMETRY → DETECT → TRIAGE → INVESTIGATE → RESPOND → IMPROVE`

</div>
