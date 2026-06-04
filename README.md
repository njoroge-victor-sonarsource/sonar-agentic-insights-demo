# SC-47867 Agentic Insights Demo

SC-47867 Agentic Insights demo — SonarQube Cloud Portfolio skills.

This demo showcases the History Retrieval Skills feature (MMF-5571) — O&R data exposed to AI agents via SonarQube Cloud.

## Live Demo

https://njoroge-victor-sonarsource.github.io/sonar-agentic-insights-demo

## Personas

- **Engineering Manager** — surface security debt trends across the org
- **Tech Lead** — rank quality gate failures by impact for sprint planning
- **Platform Engineer** — pull compliance metrics into BI dashboards as structured JSON

## Skills Invoked

- `sonar-measures` (router) — classifies intent, dispatches to sub-skills
- `sonar-measures-history` — time-series metric data
- `sonar-issue-count-history` — issue trend velocity
- `sonar-portfolio-measures` — org-level portfolio aggregates

