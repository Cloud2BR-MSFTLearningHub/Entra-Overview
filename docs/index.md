# Microsoft Entra Setup and Overview Hub

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

This repository provides practical guidance for Microsoft Entra architecture,
setup, governance, and operations across cloud-only and hybrid environments.

![Conditional Access signal and policy enforcement diagram from Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/conditional-access/media/common-conditional-access-media/conditional-access-signal-decision-enforcement.png)

*Source: [What is Microsoft Entra?](https://learn.microsoft.com/en-us/entra/fundamentals/whatis).* 

!!! warning
    These demos and guides are intended as a practical learning reference.
    For official guidance, support, or deeper implementation details, use the
    Microsoft documentation set and Microsoft support channels.

<div class="guide-grid">
  <a class="guide-card" href="overview/"><strong>Overview</strong><br>Start with architecture, setup model, and deployment flow.</a>
  <a class="guide-card" href="foundation/licensing-and-prerequisites/"><strong>Plan</strong><br>Define licensing, dependencies, and rollout readiness.</a>
  <a class="guide-card" href="secure/conditional-access-and-authentication/"><strong>Secure</strong><br>Implement authentication and policy enforcement controls.</a>
  <a class="guide-card" href="implementation/applications-and-single-sign-on/"><strong>Integrate</strong><br>Configure application access and lifecycle automation pathways.</a>
  <a class="guide-card" href="govern/identity-governance-and-lifecycle/"><strong>Govern</strong><br>Automate access lifecycle and governance operations.</a>
  <a class="guide-card" href="operations/monitoring-and-health/"><strong>Operate</strong><br>Run monitoring, reporting, and continuous improvement loops.</a>
</div>

## Recommended setup sequence

1. Establish tenant baseline and identity architecture decisions.
2. Configure authentication and Conditional Access policy rings.
3. Integrate applications, provisioning, and device identity controls.
4. Enable governance lifecycle, reviews, and privileged access controls.
5. Operationalize monitoring, support, and staged production rollout.

## Use this hub for

| Scenario | Start page |
| --- | --- |
| New Microsoft Entra deployment | [Overview](overview.md) |
| Hybrid identity modernization | [Hybrid identity design](foundation/hybrid-identity-design.md) |
| Conditional Access and authentication hardening | [Conditional Access and authentication](secure/conditional-access-and-authentication.md) |
| Governance and audit improvement | [Identity governance and lifecycle](govern/identity-governance-and-lifecycle.md) |
