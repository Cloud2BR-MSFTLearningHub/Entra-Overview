# Privileged Access and Role Governance

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [Role-based access control overview](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/custom-overview)
- [Identity governance overview](https://learn.microsoft.com/en-us/entra/id-governance/identity-governance-overview)

</details>

## Objective

Apply least-privilege administration through explicit role definition, scoped
assignment, and recurring access governance.

![Role assignment model from Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/media/custom-overview/rbac-overview.png)

*Source: [Role-based access control overview](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/custom-overview).* 

## Role model fundamentals

A role assignment combines:

1. Security principal.
2. Role definition.
3. Scope.

## Governance controls

| Control area | Guidance |
| --- | --- |
| Role baseline | Use built-in roles where possible before custom roles |
| Scope discipline | Scope roles to administrative units or resources when possible |
| Time bounds | Use privileged identity activation instead of permanent standing access |
| Review cycle | Recertify high-privilege assignments on a recurring schedule |

## Implementation checklist

- [ ] Define role taxonomy and ownership.
- [ ] Document assignment approval flow.
- [ ] Enforce activation and review controls for high-privilege roles.
- [ ] Export and review role assignment evidence regularly.