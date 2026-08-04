# Devices and Identity Signals

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [Device identity overview](https://learn.microsoft.com/en-us/entra/identity/devices/overview)
- [Conditional Access overview](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview)

</details>

## Objective

Use device identity state as a policy signal for stronger identity-centered access
controls.

![Microsoft Entra device identity view from Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/devices/media/overview/azure-entra-devices-all-devices.png)

*Source: [Device identity overview](https://learn.microsoft.com/en-us/entra/identity/devices/overview).* 

## Device identity pathways

| Pathway | Typical use |
| --- | --- |
| Device registration | Personal device access scenarios |
| Device join | Organization-managed device access scenarios |
| Hybrid device join | Transitional enterprise scenario during modernization |

## Policy usage

1. Combine user and device conditions in conditional access policies.
2. Require compliant device states for sensitive applications.
3. Segment application access by managed and unmanaged device posture.

## Deployment checks

- [ ] Device identity path is defined per platform and ownership model.
- [ ] Compliance and enrollment dependencies are documented.
- [ ] Support workflow exists for device registration and join failures.