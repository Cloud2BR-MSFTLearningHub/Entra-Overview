# Applications and Single Sign-On

Atlanta, USA

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR OSS - Learning Hub](https://github.com/Cloud2BR-MSFTLearningHub)

Last updated: 2026-08-04

----------

<details markdown>
<summary>References</summary>

- [Software as a service application guides](https://learn.microsoft.com/en-us/entra/identity/saas-apps/tutorial-list)
- [Deployment plans: applications and devices](https://learn.microsoft.com/en-us/entra/architecture/deployment-plans)

</details>

## Objective

Deliver secure, low-friction application access with consistent authentication and
authorization behavior.

## Integration pathways

| Pathway | Typical scenario |
| --- | --- |
| Gallery integration | Preintegrated software as a service application onboarding |
| Custom enterprise application | Application not yet in gallery or custom internal integration |
| Provisioning integration | Lifecycle automation for account create, update, and deprovision |

## Protocol considerations

- Security assertion markup language (SAML (security assertion markup language)).
- Open identifier connect (OIDC (open identifier connect)).
- System for cross-domain identity management (SCIM (system for cross-domain identity management)).

## Deployment sequence

1. Prioritize critical applications by business impact.
2. Configure single sign-on with pilot users and fallback validation.
3. Add provisioning where supported.
4. Apply conditional access and session controls.
5. Validate deprovision and access revocation behavior.

## Operational controls

- [ ] Owner and support contact assigned per application.
- [ ] Access model and emergency bypass pathway documented.
- [ ] Provisioning failures feed alerting and remediation workflow.