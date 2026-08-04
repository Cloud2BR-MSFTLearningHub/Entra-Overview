# Conditional Access and Authentication

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [Conditional Access overview](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview)
- [Multifactor authentication overview](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks)

</details>

## Objective

Use Microsoft Entra policy controls to enforce secure access decisions based on
identity, device, application, and risk signals.

![Conditional Access signals diagram from Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/conditional-access/media/common-conditional-access-media/conditional-access-signal-decision-enforcement.png)

*Source: [Conditional Access overview](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview).* 

## Control sequence

1. Define authentication baseline.
2. Require multifactor authentication (MFA (multifactor authentication)) for
   high-value scenarios.
3. Apply Conditional Access policy rings in report-only mode first.
4. Enforce with staged rollout and monitored remediation.

## Common policy controls

| Control type | Typical use |
| --- | --- |
| Grant controls | Require multifactor authentication (MFA (multifactor authentication)) or compliant device |
| Session controls | Restrict risky sessions and apply additional controls |
| Location controls | Limit access by trusted or blocked network zones |
| Risk controls | Require stronger controls for risky sign-in states |

## Deployment checklist

- [ ] Administrative users are protected first.
- [ ] Legacy authentication pathways are identified and remediated.
- [ ] Break-glass accounts are excluded and protected separately.
- [ ] Support team has remediation instructions for policy failures.