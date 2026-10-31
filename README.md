# Pulse

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ivanti's secure-access product family, formerly Pulse Secure, acquired by Ivanti in 2020. Three administrator-facing REST APIs configure and observe it: Ivanti Connect Secure for SSL VPN remote access, Ivanti Policy Secure for 802.1X and RADIUS/TACACS+ network access control, and Ivanti Neurons for Zero Trust Access for per-application ZTNA. Connect Secure and Policy Secure are customer-run appliances whose management API is reached at the customer's own host; nZTA is a hosted tenant. All three are configuration and management interfaces rather than data-plane APIs — they change who can reach what on a corporate network. Ivanti publishes no OpenAPI and no SDK for any of them; the published contract is prose documentation with worked curl examples plus a customer-portal Postman collection.

**Areas:** Ivanti · Network Security · Secure Access · SSL VPN · VPN · Zero Trust · ZTNA · Network Access Control · Remote Access · Identity and Access Management · Security · Pulse Secure

## Pulse on APIs.io

Everything profiled for Pulse is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/pulse/](https://apis.io/providers/pulse/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Ivanti Connect Secure REST API](https://apis.io/apis/pulse/ivanti-connect-secure-rest-api/) — REST API for managing Ivanti Connect Secure (formerly Pulse Connect Secure) VPN appliances. Provides endpoints for system configuration, user and role…
- [Ivanti Policy Secure REST API](https://apis.io/apis/pulse/ivanti-policy-secure-rest-api/) — REST API for managing Ivanti Policy Secure (formerly Pulse Policy Secure) network access control appliances.
- [Ivanti Neurons for Zero Trust Access REST API](https://apis.io/apis/pulse/ivanti-neurons-zero-trust-rest-api/) — REST API for managing Ivanti Neurons for Zero Trust Access (nZTA), providing endpoints for managing zero trust access policies, gateways, and user access.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Pulse Authentication](https://apis.io/security/pulse/pulse-authentication/)
- [Pulse Domain Security](https://apis.io/security/pulse/pulse-domain-security/)
- [Pulse Trust Center](https://apis.io/security/pulse/pulse-trust-center/)
- [Pulse Vulnerability Disclosure](https://apis.io/security/pulse/pulse-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Pulse Plans Pricing](https://apis.io/plans/pulse/pulse-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Pulse Rate Limits](https://apis.io/rate-limits/pulse/pulse-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Pulse Finops](https://apis.io/finops/pulse/pulse-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ivanti.com/products/connect-secure-vpn)
- [Documentation](https://www.ivanti.com/support/product-documentation)
- [Getting started](https://help.ivanti.com/ps/help/en_US/ICS/22.x/apig/rest_api_soln_guide/ovw.htm)
- [API reference](https://help.ivanti.com/ps/help/en_US/ICS/22.x/apig/rest_api_soln_guide/landingpage.htm)
- [Support](https://www.ivanti.com/support)
- [Blog](https://www.ivanti.com/blog)
- [Terms of service](https://www.ivanti.com/company/legal)
- [Privacy policy](https://www.ivanti.com/company/legal/privacy-policy)
- [Status](https://status.ivanticloud.com/)

## API Evangelist rating

**Kin Score 38.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 50.0 |
| Developer ergonomics | 61.9 |
| Access clarity | 43.4 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/pulse/](https://apis.io/providers/pulse/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Pulse: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/pulse/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
