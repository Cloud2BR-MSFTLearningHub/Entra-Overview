# Hybrid Identity Design

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [What is hybrid identity?](https://learn.microsoft.com/en-us/entra/identity/hybrid/whatis-hybrid-identity)
- [Deployment plans: hybrid scenarios](https://learn.microsoft.com/en-us/entra/architecture/deployment-plans)

</details>

## Objective

Create a resilient identity model where users access cloud and on-premises
resources through a consistent authentication and authorization framework.

![Hybrid identity scenario from Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/hybrid/media/common-scenarios/scenario-1.png)

*Source: [What is hybrid identity with Microsoft Entra identifier service?](https://learn.microsoft.com/en-us/entra/identity/hybrid/whatis-hybrid-identity).* 

## Design decisions

| Decision area | Guidance |
| --- | --- |
| Identity source of truth | Define authoritative identity attributes and lifecycle source |
| Synchronization model | Define provisioning and synchronization scope and cadence |
| Authentication model | Choose cloud-native, pass-through, or federated pattern based on constraints |
| Cutover model | Pilot by cohort before large-scale authentication cutover |

## Migration stages

1. Baseline current identity dependencies.
2. Clean directory data and naming conflicts.
3. Pilot synchronization and sign-in pathways.
4. Enable policy controls and conditional access stages.
5. Decommission legacy dependencies after proof.

## Risks to control

- Duplicate identities and inconsistent immutable attributes.
- Overlapping legacy and new access policies.
- Missing rollback path for authentication changes.