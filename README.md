# Entra Overview

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

Guides and demos for Microsoft Entra architecture, deployment, governance, and
operations across cloud and hybrid environments.

These demos and guides are intended as a practical learning reference. For
official guidance, support, or detailed implementation coverage, use Microsoft
Learn and Microsoft support channels.

## Documentation site (GitHub Pages)

- Site URL: https://cloud2br-msftlearninghub.github.io/Entra-Overview/

## Scope

- Microsoft Entra overview and architecture
- Tenant setup and deployment planning
- Conditional access and authentication strategy
- Application integration and single sign-on design
- Hybrid identity, governance, and privileged access controls
- Monitoring, reporting, and rollout operations

## Repository layout

| File or folder | Purpose |
| --- | --- |
| `mkdocs.yml` | Documentation site metadata and navigation. |
| `docs/` | Published GitHub Pages content for Microsoft Entra setup and operations. |
| `requirements.txt` | Build dependencies for MkDocs Material. |
| `.github/workflows/deploy-github-pages.yml` | Build and deploy workflow for GitHub Pages. |

## Local validation

```bash
pip install -r requirements.txt
mkdocs build --strict
mkdocs serve
```

## Authoring standards

- Keep the required Markdown header block in all tracked pages.
- Use authoritative Microsoft documentation references.
- Keep acronym expansions explicit in parentheses.
- Update `mkdocs.yml` navigation when adding new pages.

<!-- START BADGE -->
<div align="center">
  <img src="https://img.shields.io/badge/Total%20views-40-limegreen" alt="Total views">
  <p>Refresh Date: 2026-04-07</p>
</div>
<!-- END BADGE -->
