<!--
=====================================================================
MEHRAB SHAHEEN — GITHUB PROFILE README (RESTRUCTURED LAYOUT)
Same dark-navy / neon-cyan HUD theme, but the STRUCTURE is different:
- Quick-facts info card instead of a plain paragraph
- Skill proficiency bars (custom SVG) instead of badge lists
- Vertical timeline visual instead of an education table
- Collapsible <details> project cards instead of a static table

SETUP:
1. Repo named exactly like your GitHub username, public.
2. Upload to repo ROOT: header-scan.svg, divider.svg, footer-scan.svg,
   skill-bars.svg, timeline.svg
3. Paste this as README.md.
4. Replace every [ ] placeholder.
=====================================================================
-->

<div align="center">
<img src="./header-scan.svg" alt="Mehrab Shaheen — Blue Team Security" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Consolas&size=17&pause=1600&color=5FD4E8&center=true&vCenter=true&width=650&lines=Fresh+IT+Graduate+%E2%80%94+University+of+Chakwal;Focused+on+SOC+Operations+%26+Threat+Detection;Open+to+SOC+Analyst+%2F+Blue+Team+Roles" alt="Typing SVG" />
</a>
</div>

<br/>

<!-- QUICK-FACTS CARD: business-card layout, two columns, no long paragraph -->
<table width="100%">
<tr>
<td width="60%" valign="top">

**Mehrab Shaheen**
Aspiring SOC Analyst · Blue Team Security

Comfortable investigating SIEM alerts, tracing malware samples through static/dynamic analysis, and building
AI-assisted tooling to make SOC triage faster and less noisy for analysts.

[Optional: 1 personal line on what drew you to blue team.]

</td>
<td width="40%" valign="top">

| | |
|---|---|
| 🎓 Degree | BS Information Technology |
| 🏫 Institution | University of Chakwal |
| 📅 Batch | 2022 – 2026 |
| 📊 CGPA | 3.48 / 4.0 |
| 📍 Location | Punjab, Pakistan |
| 🎯 Target Roles | SOC Analyst · Malware Analyst · DFIR |

</td>
</tr>
</table>

<div align="center">

<a href="mailto:[YOUR_EMAIL]"><img src="https://img.shields.io/badge/EMAIL-0D1B2A?style=flat-square&logoColor=5FD4E8" /></a>
<a href="[YOUR_LINKEDIN_URL]"><img src="https://img.shields.io/badge/LINKEDIN-0D1B2A?style=flat-square&logo=linkedin&logoColor=5FD4E8" /></a>
<a href="[YOUR_GITHUB_URL]"><img src="https://img.shields.io/badge/GITHUB-0D1B2A?style=flat-square&logo=github&logoColor=5FD4E8" /></a>
<a href="[YOUR_TRYHACKME_URL]"><img src="https://img.shields.io/badge/TRYHACKME-0D1B2A?style=flat-square&logo=tryhackme&logoColor=5FD4E8" /></a>
<img src="https://komarev.com/ghpvc/?username=[YOUR_GITHUB_USERNAME]&style=flat-square&color=0D1B2A&label=VIEWS" />

</div>

<div align="center"><img src="./divider.svg" width="100%"/></div>

## `// 01` Journey So Far

<div align="center">
<img src="./timeline.svg" alt="Career timeline" width="100%"/>
</div>

<div align="center"><img src="./divider.svg" width="100%"/></div>

## `// 02` Experience

<details>
<summary><b>[Role / Title]</b> — [Company Name] · [Start Month Year] – [End Month Year]  <i>(click to expand)</i></summary>
<br/>

- [Responsibility 1 — e.g. Monitored SIEM alerts, performed initial triage]
- [Responsibility 2 — e.g. Investigated logs across endpoints using Wazuh/Suricata]
- [Responsibility 3 — e.g. Documented findings and escalated confirmed incidents]

</details>

*(If no internship yet, replace with a "Practical Experience" entry describing home-lab/FYP work — never fabricate a role.)*

<div align="center"><img src="./divider.svg" width="100%"/></div>

## `// 03` Skill Proficiency

<div align="center">
<img src="./skill-bars.svg" alt="Skill proficiency bars" width="100%"/>
</div>

<div align="center">
<img src="https://skillicons.dev/icons?i=python,fastapi,react,postgres,linux,bash,git,github" />
</div>

<div align="center"><img src="./divider.svg" width="100%"/></div>

## `// 04` Certifications & Achievements

| Status | Title | Issuer | Year |
|---|---|---|---|
| ✅ | [Certification Name] | [Issuer] | [Year] |
| 🔄 | [Certification Name — In Progress] | [Issuer] | — |
| 🏆 | [Achievement] | [Details] | [Year] |

*(Only real, held items — delete rows that don't apply.)*

<div align="center"><img src="./divider.svg" width="100%"/></div>

## `// 05` Projects

<details open>
<summary><b>🛡️ AI-Assisted SOC — Agentic RAG Alert Triage</b> <i>(Final Year Project)</i></summary>
<br/>

Final Year Project · University of Chakwal, Dept. of CS & IT
Supervisor: Ms. Zainab Nawab · Team: Mehrab Shaheen, Amna Nisar, Hira Ghous

An agentic RAG pipeline that ingests SOC alerts from Wazuh/Suricata, retrieves relevant context from ChromaDB, and
uses LangGraph-based LLM reasoning to classify and investigate alerts — reducing analyst workload from false
positives.

```mermaid
flowchart LR
    A[Wazuh / Suricata Alerts] --> B[FastAPI Ingestion]
    B --> C[ChromaDB Vector Store]
    C --> D[LangGraph Agentic RAG]
    D --> E{LLM Verdict}
    E -->|True Positive| F[Escalate to Analyst]
    E -->|False Positive| G[Auto-Close]
    E -->|Ambiguous| H[Manual Review]
    D --> I[React.js Dashboard]
```

**Tech:** LangGraph · ChromaDB · FastAPI · React.js · Wazuh · Suricata · PostgreSQL
**Repository:** [LINK]

</details>

<details>
<summary><b>🔎 SOC Alert Classifier</b></summary>
<br/>

LLM-based TRUE_POSITIVE / FALSE_POSITIVE / AMBIGUOUS verdict engine with six formal behavioral indicator categories
and priority-ordered decision logic.

**Tech:** Python · Prompt Engineering
**Repository:** [LINK]

</details>

<details>
<summary><b>🦠 Malware Analysis Reports</b></summary>
<br/>

Static & dynamic analysis writeups — Agent Tesla, Remcos, LockBit, and Emotet-style samples — with IOCs and
behavioral indicators, written up to portfolio/CV standard.

**Tools:** PMAT-labs · Any.Run · Hybrid Analysis · theZoo
**Repository:** [LINK]

</details>

<details>
<summary><b>💻 Portfolio Website</b></summary>
<br/>

Single-file, dark SOC-themed site with a live simulated alert feed.

**Tech:** HTML · CSS · JS
**Repository:** [LINK] · **Live Demo:** [LINK]

</details>

<div align="center"><img src="./divider.svg" width="100%"/></div>

## `// 06` GitHub Activity

<div align="center">
<img width="48%" src="https://github-readme-stats.vercel.app/api?username=[YOUR_GITHUB_USERNAME]&show_icons=true&theme=dark&hide_border=true&count_private=true&title_color=5FD4E8&icon_color=00F0FF&text_color=c9d1d9&bg_color=0D1B2A" />
<img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=[YOUR_GITHUB_USERNAME]&theme=dark&hide_border=true&background=0D1B2A&ring=00F0FF&fire=00F0FF&currStreakLabel=5FD4E8" />
</div>

<div align="center"><img src="./divider.svg" width="100%"/></div>

## `// 07` Contact

[YOUR_EMAIL] · [YOUR_LINKEDIN_URL] · [YOUR_GITHUB_URL] · [YOUR_TRYHACKME_URL] · Punjab, Pakistan

<div align="center">
<img src="./footer-scan.svg" width="100%"/>
</div>
