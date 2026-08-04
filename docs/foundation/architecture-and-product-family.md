# Microsoft Entra Architecture and Product Family

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [What is Microsoft Entra?](https://learn.microsoft.com/en-us/entra/fundamentals/whatis)
- [Microsoft Entra deployment plans](https://learn.microsoft.com/en-us/entra/architecture/deployment-plans)

</details>

## Purpose

Microsoft Entra is a family of identity and network access products that supports
modern identity, access, governance, and protection requirements across cloud and
hybrid estates.

## Core architecture model

1. Identity authority and authentication.
2. Access control and policy evaluation.
3. Application integration and authorization.
4. Governance and lifecycle management.
5. Monitoring and operations.

## Product family view

| Area | Primary capability |
| --- | --- |
| Identity and access management | User and workload identity authentication and authorization |
| External identities | Customer and partner access models |
| Governance | Access lifecycle, reviews, and privileged control |
| Identity protection | Risk-aware protections and policy response |
| Network access | Secure access to private and internet resources |

## Setup implications

- Product decisions should map directly to business scenarios, not feature lists.
- Security and governance should be designed early, not appended post deployment.
- Hybrid and cloud-only paths require different sequencing, especially for identity
  synchronization and application access cutover.

## Success criteria

- Every identity type has a defined control model.
- Every critical application has a documented access model.
- Every privileged path has lifecycle and review controls.
- Monitoring signals are available to support and security teams.