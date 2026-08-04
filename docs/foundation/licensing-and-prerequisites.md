# Licensing and Prerequisites

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [Microsoft Entra licensing](https://learn.microsoft.com/en-us/entra/fundamentals/licensing)
- [What is Microsoft Entra?](https://learn.microsoft.com/en-us/entra/fundamentals/whatis)

</details>

## Objective

Align feature adoption with licensing and technical dependencies before broad
rollout.

## Licensing checkpoints

| Capability | Typical license dependency |
| --- | --- |
| Conditional Access | Microsoft Entra identifier Plan 1 license (P1 (Plan 1)) |
| Risk-based protections | Microsoft Entra identifier Plan 2 license (P2 (Plan 2)) |
| Identity governance features | Microsoft Entra identifier governance licensing tier |
| Privileged controls | Privileged identity management feature licensing |

## Technical prerequisites

1. Verified domains and tenant naming standards.
2. Group strategy for user, device, and workload targeting.
3. Role model for administrators and support teams.
4. Baseline logging, retention, and monitoring integration.

## Readiness checklist

- [ ] Required licenses are confirmed for all in-scope users and administrators.
- [ ] Security and compliance owners approve baseline controls.
- [ ] Change management and support model are documented.
- [ ] Pilot group and rollback strategy are defined.

## Common mistakes

- Enabling policies that require licenses before licensing assignment is complete.
- Expanding privileged roles before role governance is ready.
- Rolling out governance workflows without business owner alignment.