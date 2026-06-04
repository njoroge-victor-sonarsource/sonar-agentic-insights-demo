# SC-47867 — Agentic Insights for SonarQube Cloud

**MMF-5571** · Enhance MCP/Sonar-CLI for AI-powered insights & reporting

Live demo: [GitHub Pages link below]

## What this shows

Five new history-retrieval skills that expose SonarQube Cloud's O&R (Organization & Reporting) data layer to AI agents — enabling portfolio audits, trend analysis, and automated reporting without manual data exports.

### Skills

| Skill | Scope | Persona |
|---|---|---|
| `sonar-measures` | Router | All |
| `sonar-measures-history` | Project · Branch | EM · Tech Lead · Platform Eng |
| `sonar-issue-count-history` | Project · Branch · **Portfolio** | EM · Tech Lead |
| `sonar-portfolio-measures` | Portfolio aggregate | EM · Platform Eng |
| `sonar-portfolio-rankings` | Portfolio → ranked projects | EM · Tech Lead |
| `sonar-portfolio-project-measures` | Portfolio → individual project | Tech Lead |

### Personas

- **Engineering Manager** — Portfolio security debt audit, executive reporting
- **Tech Lead** — Sprint prioritization from QG failures, AI-scored backlog
- **Platform Engineer** — Schema discovery, structured JSON export for BI tools

## Branch

[`SC-47867-add-history-retrieval-skills`](https://github.com/SonarSource/sonarqube-agent-plugins/tree/SC-47867-add-history-retrieval-skills)

---
Made by the O&R squad · SonarSource
