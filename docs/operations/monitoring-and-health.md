# Monitoring, Reporting, and Health

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [Monitoring and health overview](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/overview-monitoring-health)

</details>

## Objective

Turn identity telemetry into actionable operations signals for security, support,
and platform reliability.

![Monitoring architecture decision flow from Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/media/overview-monitoring-health/deploy-reporting-flow-diagram.png)

*Source: [Monitoring and health overview](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/overview-monitoring-health).* 

## Core telemetry streams

| Stream | Typical question answered |
| --- | --- |
| Audit logs | What changed and who changed it |
| Sign-in logs | Who is signing in and from where |
| Provisioning logs | Which lifecycle operations succeeded or failed |

## Operations model

1. Route logs to analytics and security operations tooling.
2. Define alerting thresholds for high-risk events.
3. Track service and policy health indicators.
4. Review trends and tune controls iteratively.

## Key indicators

- Authentication failure trend by policy reason.
- Privileged role assignment and activation events.
- Provisioning failure rates by connector and application.
- Access review completion and denial outcomes.