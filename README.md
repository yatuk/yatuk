<!-- ╔══════════════════════════════════════════════════════════════════╗ -->
<!-- ║              FATIH SERDAR ÇAKMAK · PROFILE README                  ║ -->
<!-- ╚══════════════════════════════════════════════════════════════════╝ -->

<!-- ============================ HEADER ============================ -->
<div align="center">

<h1>Fatih Serdar Çakmak</h1>
<h3>SOC Analyst Intern · Blue Team · Detection &amp; Incident Response</h3>
<p>Triaging alerts, chasing true positives · Building open-source AI security tooling · Computer Engineering @ ITU, Class of 2027</p>

<a href="https://linkedin.com/in/fatihserdar"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="linkedin"/></a>
<a href="https://fscakmak.com"><img src="https://img.shields.io/badge/Portfolio-fscakmak.com-00F5A0?style=flat-square&amp;logo=vercel&amp;logoColor=white" alt="portfolio"/></a>
<img src="https://img.shields.io/badge/Based%20in-T%C3%BCrkiye-E30A17?style=flat-square&amp;logo=googlemaps&amp;logoColor=white" alt="location"/>

</div>

<!-- ============================ ABOUT ============================ -->
## `~/whoami`

```yaml
name:         Fatih Serdar Çakmak
role:         SOC Analyst Intern  ·  Computer Engineering Student
focus:        [ SOC Operations, Alert Triage, Incident Response, Detection ]
currently:    SOC Intern @ Fibabanka (BDDK-regulated banking SOC)
building:     [ Tamga - LLM security proxy, SOC n8n playbooks, MCPRadar - MCP scanner ]
education:    B.Sc. Computer Engineering @ ITU (expected 2027)
```

I'm a Computer Engineering student who spends most of his time inside a SOC. Day to day that means triaging alerts, killing false positives, and tweaking SOAR playbooks so the signal surfaces faster. Mostly I'm learning what incidents actually look like before they reach an analyst, and how much of a working SOC quietly runs on automation.

Off the clock I build security tooling for AI systems: a proxy that sits in front of LLM traffic, a scanner for MCP servers, and n8n playbooks that handle the repetitive half of SOC work. Everything is open source and linked below.

<!-- ============================ EXPERIENCE ============================ -->
## `~/experience`

```text
[ Mar 2026 -> Present ]  Fibabanka          ·  Cybersecurity Operations (SOC) Intern
                         └─ SIEM/EDR alert triage · CTI review · incident docs · AI-assisted triage

[ Jul 2025 -> Mar 2026 ]  Doğuş Teknoloji   ·  Cybersecurity and Incident Response Intern
                         └─ SIEM/SOAR/EDR/NDR triage · phishing playbooks · L1 IR · AD and log monitoring
```

<!-- ============================ STACK ============================ -->
## `~/tech-stack`

<p><img src="https://img.shields.io/badge/SIEM-000000?style=for-the-badge&amp;logo=splunk&amp;logoColor=white" alt="SIEM"/> <img src="https://img.shields.io/badge/SOAR-FA582D?style=for-the-badge&amp;logo=paloaltonetworks&amp;logoColor=white" alt="SOAR"/> <img src="https://img.shields.io/badge/EDR%20%2F%20NDR-1A2B4A?style=for-the-badge&amp;logo=fsecure&amp;logoColor=white" alt="EDR / NDR"/> <img src="https://img.shields.io/badge/MITRE_ATT%26CK-C00?style=for-the-badge&amp;logo=mitre&amp;logoColor=white" alt="MITRE ATT&amp;CK"/> <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&amp;logo=wireshark&amp;logoColor=white" alt="Wireshark"/> <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&amp;logo=n8n&amp;logoColor=white" alt="n8n"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&amp;logo=go&amp;logoColor=white" alt="Go"/> <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&amp;logo=c&amp;logoColor=black" alt="C"/> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&amp;logo=cplusplus&amp;logoColor=white" alt="C++"/> <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white" alt="SQL"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&amp;logo=nextdotjs&amp;logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&amp;logo=linux&amp;logoColor=black" alt="Linux"/> <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&amp;logo=microsoft&amp;logoColor=white" alt="Active Directory"/> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git"/> <img src="https://img.shields.io/badge/BDDK-Regulatory_Awareness-0D1117?style=for-the-badge" alt="BDDK"/> <img src="https://img.shields.io/badge/ISO%2FIEC_27001-Awareness-00B4D8?style=for-the-badge" alt="ISO 27001"/></p>

<!-- ============================ PROJECTS ============================ -->
## `~/projects`

| Project | What it does | Stack |
|---|---|---|
| ![stars](https://img.shields.io/github/stars/yatuk/tamga?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🛡️ **[Tamga](https://github.com/yatuk/tamga)** | Self-hosted proxy that redacts PII, blocks leaked secrets, and catches prompt injection before it hits your LLM provider. Sub-millisecond scanning, KVKK/BDDK/GDPR/PCI-DSS mappings. | `Go` `Python` `Next.js` |
| ![stars](https://img.shields.io/github/stars/yatuk/soc-n8n-workflows?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) ⚙️ **[SOC n8n Workflows](https://github.com/yatuk/soc-n8n-workflows)** | Ten import-ready n8n playbooks for alert triage, phishing analysis, IOC enrichment, and CVE watch. No secrets baked in. | `n8n` `JSON` |
| ![stars](https://img.shields.io/github/stars/yatuk/itu-mcp?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🎓 **[İTÜ MCP](https://github.com/yatuk/itu-mcp)** | MCP server that connects İTÜ's Ninova and OBS to Claude, Cursor, and other AI clients. Course files, grades, deadlines, transcript, all queryable in plain language. | `Python` `FastMCP` |
| ![stars](https://img.shields.io/github/stars/yatuk/itu-archive?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🗂️ **[İTÜ Archive](https://github.com/yatuk/itu-archive)** | OBS only keeps the current term online, so this pulls the course schedule and academic calendar daily and keeps it. 27 terms, 64k+ section records since 2016. | `Go` `JSON/CSV` |
| ![stars](https://img.shields.io/github/stars/yatuk/soc-simulation?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🎯 **[SOC Simulation](https://github.com/yatuk/soc-simulation)** | A simulated SOC shift: 127 alerts, 126 false positives, 1 real threat, 6 coffees. SIEM/SOAR/EDR triage with MITRE ATT&amp;CK mapping. [Live demo](https://yatuk.github.io/soc-simulation/). | `Python` |
| ![stars](https://img.shields.io/github/stars/yatuk/mcpradar?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 📡 **[MCPRadar](https://github.com/yatuk/mcpradar)** | Scans MCP servers for tool poisoning, prompt injection, and supply-chain rug pulls before your agent runs them. SARIF output, [public leaderboard](https://yatuk.github.io/mcpradar). | `Python` |

<!-- ============================ STATS ============================ -->
## `~/github-stats`

<div align="center">

<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=yatuk&amp;theme=github_dark" alt="stats"/>
<img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=yatuk&amp;theme=github_dark" alt="top langs"/>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yatuk/yatuk/output/snake-dark.svg"/>
  <img width="95%" src="https://raw.githubusercontent.com/yatuk/yatuk/output/snake.svg" alt="contribution snake"/>
</picture>

</div>
