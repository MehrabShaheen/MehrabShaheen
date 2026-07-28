# Mehrab-Shaheen-Portfolio
<!--
=====================================================================
MEHRAB SHAHEEN — ANIMATED GITHUB PROFILE README (TEMPLATE)
Fill in every [ ] placeholder with your real information.
GitHub renders: capsule-render banners, typing SVG, skillicons.dev,
Mermaid diagrams, and shields.io badges — all officially supported.
=====================================================================
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:d99058,100:c261a0&height=100&section=header" width="100%"/>

<br/>

<!-- Stacked badge-style link rows (label + value blocks) -->
<table>
<tr><td align="right"><img src="https://img.shields.io/badge/LINKEDIN-4a4a4a?style=for-the-badge" /></td><td><a href="[YOUR_LINKEDIN_URL]"><img src="https://img.shields.io/badge/MEHRAB%20SHAHEEN-0A66C2?style=for-the-badge" /></a></td></tr>
<tr><td align="right"><img src="https://img.shields.io/badge/TRYHACKME-4a4a4a?style=for-the-badge&logo=tryhackme&logoColor=red" /></td><td><a href="[YOUR_TRYHACKME_URL]"><img src="https://img.shields.io/badge/MEHRAB.SHAHEEN-212C42?style=for-the-badge" /></a></td></tr>
<tr><td align="right"><img src="https://img.shields.io/badge/GITHUB-4a4a4a?style=for-the-badge&logo=github&logoColor=white" /></td><td><a href="[YOUR_GITHUB_URL]"><img src="https://img.shields.io/badge/MEHRABSHAHEEN-181717?style=for-the-badge" /></a></td></tr>
<tr><td align="right"><img src="https://img.shields.io/badge/PROFILE%20VIEWS-4a4a4a?style=for-the-badge" /></td><td><img src="https://komarev.com/ghpvc/?username=[YOUR_GITHUB_USERNAME]&style=for-the-badge&color=05CFEA&label=" /></td></tr>
</table>

<hr/>

<!-- Big rounded gradient name banner (pill style) -->
<img src="https://capsule-render.vercel.app/api?type=rounded&color=0:ff00cc,100:00e0ff&height=140&section=header&text=Mehrab%20Shaheen&fontSize=52&fontColor=00faff&fontAlignY=55&animation=fadeIn" width="100%"/>

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=SOC+Analyst+in+the+making;Malware+Analysis+%7C+Detection+Engineering;Building+AI-Assisted+Security+Tools;Blue+Team+%7C+DFIR+%7C+Threat+Hunting" alt="Typing SVG" />
</a>

</div>

<br/>

## 🧑 A Bit More About Me

```yaml
name: Mehrab Shaheen
role: Aspiring SOC Analyst | Blue Team Enthusiast
degree: BS Information Technology, University of Chakwal (2022 - 2026)
cgpa: 3.48 / 4.0
focus: SOC Operations · Malware Analysis · Detection Engineering · DFIR
current_project: "AI-Assisted SOC — Agentic RAG for Alert Triage"
location: Punjab, Pakistan
fun_fact: "[optional — add something personal/fun here]"
```

---

## 🧠 What I Do

<table>
<tr>
<td width="50%" valign="top">

### 🔎 SOC & Blue Team
- Alert triage & investigation
- SIEM log analysis (Wazuh, Suricata)
- Incident documentation & escalation
- False positive / true positive verdicting

</td>
<td width="50%" valign="top">

### 🦠 Malware Analysis
- Static & dynamic analysis
- String/IOC extraction
- Sandbox analysis (Any.Run, Hybrid Analysis)
- Report writing (Agent Tesla, Remcos, LockBit, Emotet-style)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 AI for Security
- Agentic RAG pipelines (LangGraph + ChromaDB)
- LLM-based alert classification
- RAGAS evaluation of RAG systems
- Prompt engineering for SOC use cases

</td>
<td width="50%" valign="top">

### 📄 Documentation
- Professional analysis reports
- Architecture diagrams
- Clean, structured technical writing
- [Add more]

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,react,postgres,linux,bash,git,github,docker" />

<br/><br/>

![Wazuh](https://img.shields.io/badge/Wazuh-1A73E8?style=for-the-badge&logo=wazuh&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-D2232A?style=for-the-badge&logo=suricata&logoColor=white)
![LangChain](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white)

</div>

---

## 🏗️ Featured Project — AI-Assisted SOC (Agentic RAG)

**Final Year Project · University of Chakwal · Dept. of CS & IT**
Supervisor: Ms. Zainab Nawab · Team: Mehrab Shaheen, Amna Nisar, Hira Ghous

An agentic RAG-based system that ingests SOC alerts and uses retrieval + LLM reasoning to reduce analyst fatigue
from false positives.

```mermaid
flowchart LR
    A[Wazuh / Suricata Alerts] --> B[FastAPI Ingestion Layer]
    B --> C[ChromaDB Vector Store]
    C --> D[LangGraph Agentic RAG]
    D --> E{LLM Classification}
    E -->|TRUE_POSITIVE| F[Escalate to Analyst]
    E -->|FALSE_POSITIVE| G[Auto-Close + Log]
    E -->|AMBIGUOUS| H[Flag for Manual Review]
    D --> I[React.js SOC Dashboard]
```

**Tech:** LangGraph · ChromaDB · FastAPI · React.js · Wazuh · Suricata · PostgreSQL
**Repo:** [LINK]

---

## 🧪 More Projects

<table>
<tr>
<td width="33%" valign="top">

### 🔹 SOC Alert Classifier
LLM-based TRUE_POSITIVE / FALSE_POSITIVE / AMBIGUOUS verdict engine with 6 behavioral indicator categories.

**Repo:** [LINK]

</td>
<td width="33%" valign="top">

### 🔹 Malware Analysis Reports
Static/dynamic writeups — Agent Tesla, Remcos, LockBit, Emotet-style samples with IOCs & MITRE mapping.

**Repo:** [LINK]

</td>
<td width="33%" valign="top">

### 🔹 Portfolio Website
Dark terminal/SOC-themed single-file site with a live simulated alert feed.

**Repo:** [LINK] · **Demo:** [LINK]

</td>
</tr>
</table>

---

## 📜 Certifications

<!-- Only list what you actually hold. Delete row if none yet. -->

| Certification | Issuer | Year |
|---|---|---|
| [Cert Name] | [Issuer] | [Year] |
| *Currently pursuing:* [Cert Name] | [Issuer] | — |

---

## 📊 GitHub Analytics

<div align="center">
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=[YOUR_GITHUB_USERNAME]&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=[YOUR_GITHUB_USERNAME]&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
<img width="60%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=[YOUR_GITHUB_USERNAME]&layout=compact&theme=tokyonight&hide_border=true" />
</div>

---

## 📫 Let's Connect

<div align="center">

[YOUR_EMAIL] · [YOUR_LINKEDIN_URL] · [YOUR_GITHUB_URL] · Punjab, Pakistan

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%"/>

</div>
