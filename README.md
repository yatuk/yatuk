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

<!-- ============================ STACK ============================ -->
## `~/tech-stack`

<p align="center">
  <a href="https://skillicons.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,go,c,cpp,postgres,docker,fastapi,nextjs,linux,git&theme=dark"/>
      <img src="https://skillicons.dev/icons?i=py,go,c,cpp,postgres,docker,fastapi,nextjs,linux,git&theme=light" alt="Python, Go, C, C++, PostgreSQL, Docker, FastAPI, Next.js, Linux, Git"/>
    </picture>
  </a>
</p>

<p align="center"><b>Security ops</b> · SIEM · SOAR · EDR / NDR · MITRE ATT&amp;CK · Wireshark · Active Directory · n8n<br/>
<b>Compliance</b> · BDDK · ISO/IEC 27001</p>

<!-- ============================ PROJECTS ============================ -->
## `~/projects`

| Project | What it does | Stack |
|---|---|---|
| ![stars](https://img.shields.io/github/stars/yatuk/tamga?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🛡️ **[Tamga](https://github.com/yatuk/tamga)** | Self-hosted proxy that redacts PII, blocks leaked secrets, and catches prompt injection before it hits your LLM provider. Sub-millisecond scanning, KVKK/BDDK/GDPR/PCI-DSS mappings. | `Go` `Python` `Next.js` |
| ![stars](https://img.shields.io/github/stars/yatuk/itu-mcp?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🎓 **[İTÜ MCP](https://github.com/yatuk/itu-mcp)** | MCP server that connects İTÜ's Ninova and OBS to Claude, Cursor, and other AI clients. Course files, grades, deadlines, transcript, all queryable in plain language. | `Python` `FastMCP` |
| ![stars](https://img.shields.io/github/stars/yatuk/soc-n8n-workflows?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) ⚙️ **[SOC n8n Workflows](https://github.com/yatuk/soc-n8n-workflows)** | Ten import-ready n8n playbooks for alert triage, phishing analysis, IOC enrichment, and CVE watch. No secrets baked in. | `n8n` `JSON` |
| ![stars](https://img.shields.io/github/stars/yatuk/mcpradar?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 📡 **[MCPRadar](https://github.com/yatuk/mcpradar)** | Scans MCP servers for tool poisoning, prompt injection, and supply-chain rug pulls before your agent runs them. SARIF output, [public leaderboard](https://yatuk.github.io/mcpradar). | `Python` |
| ![stars](https://img.shields.io/github/stars/yatuk/soc-simulation?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🎯 **[SOC Simulation](https://github.com/yatuk/soc-simulation)** | A simulated SOC shift: 127 alerts, 126 false positives, 1 real threat, 6 coffees. SIEM/SOAR/EDR triage with MITRE ATT&amp;CK mapping. [Live demo](https://yatuk.github.io/soc-simulation/). | `Python` |
| ![stars](https://img.shields.io/github/stars/yatuk/itu-archive?style=flat-square&amp;label=%E2%98%85&amp;color=00F5A0&amp;labelColor=0D1117) 🗂️ **[İTÜ Archive](https://github.com/yatuk/itu-archive)** | OBS only keeps the current term online, so this pulls the course schedule and academic calendar daily and keeps it. 27 terms, 64k+ section records since 2016. | `Go` `JSON/CSV` |

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
