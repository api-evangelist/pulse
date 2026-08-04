# Pulse (pulse)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs for Ivanti Pulse Secure (formerly Pulse Secure), providing secure remote access VPN, network access control, and zero trust access solutions.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/pulse/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Ivanti, Network Security, Secure Access, SSL VPN, VPN, Zero Trust

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Ivanti Connect Secure REST API
REST API for managing Ivanti Connect Secure (formerly Pulse Connect Secure) VPN appliances. Provides endpoints for system configuration, user and role management, authentication server configuration, license management, network settings, resource policies, and system maintenance operations.

**Human URL:** [https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm](https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm)

#### Tags:

 - Authentication, Configuration, Network Security, Secure Access, SSL VPN, VPN

#### Properties

- [Documentation](https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm)

### Ivanti Policy Secure REST API
REST API for managing Ivanti Policy Secure (formerly Pulse Policy Secure) network access control appliances.

**Human URL:** [https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm](https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm)

#### Tags:

 - NAC, Network Access Control, Policy, Security

#### Properties

- [Documentation](https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm)

### Ivanti Neurons for Zero Trust Access REST API
REST API for managing Ivanti Neurons for Zero Trust Access (nZTA), providing endpoints for managing zero trust access policies, gateways, and user access.

**Human URL:** [https://help.ivanti.com/ps/help/en_US/nSA/22.x/nsa-zta/api/landingpage.htm](https://help.ivanti.com/ps/help/en_US/nSA/22.x/nsa-zta/api/landingpage.htm)

#### Tags:

 - Secure Access, Zero Trust, ZTNA

#### Properties

- [Documentation](https://help.ivanti.com/ps/help/en_US/nSA/22.x/nsa-zta/api/landingpage.htm)

## Common Properties

- [Documentation](https://www.ivanti.com/support/product-documentation)
- [PrivacyPolicy](https://www.ivanti.com/company/legal/privacy-policy)
- [TermsOfService](https://www.ivanti.com/company/legal)
- [StatusPage](https://status.ivanticloud.com/)
- [Blog](https://www.ivanti.com/blog)
- [Support](https://forums.ivanti.com/s/welcome-pulse-secure?language=en_US)

## Features

| Name | Description |
|------|-------------|
| SSL VPN Remote Access | Secure remote access to corporate resources through SSL VPN tunnels with granular access policies. |
| Zero Trust Network Access | Identity-aware, application-level access control without exposing network resources. |
| Network Access Control | Enforce security policies on endpoints before granting network access with 802.1X and agent-based checks. |
| Multi-Factor Authentication | Integrate with MFA providers for strong authentication on VPN and network access. |
| Host Checker | Validate endpoint compliance with security policies before granting access. |
| Role-Based Access Control | Define granular access policies based on user roles, device type, and compliance status. |

## Use Cases

| Name | Description |
|------|-------------|
| Remote Workforce Access | Provide secure remote access to corporate applications and resources for distributed teams. |
| Zero Trust Architecture | Implement zero trust security with per-application access controls and continuous verification. |
| BYOD Management | Securely enable bring-your-own-device access with endpoint compliance checking. |
| Partner and Contractor Access | Grant controlled, time-limited access to third-party partners and contractors. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft Active Directory | Authenticate users against Active Directory for single sign-on and role mapping. |
| RADIUS Servers | Integrate with RADIUS for centralized authentication and accounting. |
| SIEM Platforms | Forward access logs and security events to SIEM platforms for monitoring and analysis. |
| MDM Solutions | Integrate with mobile device management solutions for endpoint compliance verification. |
| Identity Providers | Connect with SAML and OIDC identity providers for federated authentication. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
