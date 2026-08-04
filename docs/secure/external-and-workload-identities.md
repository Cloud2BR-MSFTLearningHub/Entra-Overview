# External and Workload Identities

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [What is Microsoft Entra?](https://learn.microsoft.com/en-us/entra/fundamentals/whatis)
- [Identity governance overview](https://learn.microsoft.com/en-us/entra/id-governance/identity-governance-overview)

</details>

## Objective

Establish secure and governed access patterns for partner, customer, and workload
identities in addition to employee identities.

## Identity categories

| Identity type | Typical controls |
| --- | --- |
| External collaboration identities | Invitation, conditional access, periodic review, and lifecycle removal |
| Customer identities | Registration, authentication journey, and application policy controls |
| Workload identities | App registration governance, credential hygiene, and scoped permissions |
| Agent identities | Sponsor ownership, policy inheritance, and lifecycle controls |

## Setup priorities

1. Define identity inventory and ownership model.
2. Apply access package or request workflow where possible.
3. Require periodic access reviews for external and privileged pathways.
4. Enforce nonhuman identity credential and permission standards.

## Risk patterns

- Orphaned external users with stale access.
- Workload identities with broad, long-lived permissions.
- Missing accountability for autonomous or semi-autonomous agents.