# Lancope

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

Lancope was an Atlanta, Georgia based network security company best known for **StealthWatch**, a NetFlow-based network visibility and security analytics platform that used flow telemetry from existing routers and switches to detect internal threats, lateral movement, and anomalous behavior without deploying inline sensors.

## Status: acquired

Cisco Systems acquired Lancope on **December 22, 2015** for approximately **$452.5 million**, to advance its "Security Everywhere" strategy. StealthWatch was folded into Cisco's security portfolio, rebranded **Cisco Stealthwatch Enterprise** and later — from version 7.4.0 — **Cisco Secure Network Analytics**.

Lancope no longer operates as an independent company. `lancope.com` redirects to the Cisco Secure Network Analytics product page, and there is no Lancope developer portal, API, SDK, or package surface to catalog.

## Where the API surface lives now

The programmable surface descended from StealthWatch — the Secure Network Analytics REST APIs, plus the deprecated SOAP Web Services API — is documented by Cisco:

- Product: https://www.cisco.com/site/us/en/products/security/security-analytics/secure-network-analytics/index.html
- Developer docs: https://developer.cisco.com/docs/stealthwatch/enterprise/

Those APIs are catalogued in the API Evangelist network under the **Cisco** provider repositories, not here. This repo is retained as an identity/lineage record.

Backed by: canaan-partners
