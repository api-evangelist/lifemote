# Lifemote

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

Lifemote Networks is an Istanbul-based provider of AI-driven home Wi-Fi analytics and experience management for broadband ISPs and network operators. A software agent running on the subscriber gateway or access point streams detailed in-home Wi-Fi performance telemetry to Lifemote's cloud, which scores quality of experience per household and per device and isolates root causes such as poor coverage, misplaced repeaters, congested or co-channel Wi-Fi, legacy client devices, and non-Wi-Fi interference.

Operators consume the results through a web application for first-line support, proactive maintenance, churn detection and mesh/gateway upselling, plus quarterly expert-reviewed QoE reports. Publicly named customers include A1, Community Fibre, Online.nl, and Tusass.

## API surface

Lifemote markets a "full-featured API" for integrating its analytics with in-house OSS/BSS systems, but as of 2026-07-19 that API is **not publicly documented**. Enrichment found no developer portal, API reference, machine-readable specification, SDK, package, sandbox, status page, or self-service sign-up. Access is arranged through direct enterprise engagement via https://www.lifemote.com/contact.

## Artifacts

| Artifact | Path | Method | Result |
|---|---|---|---|
| Domain security | `security/lifemote-domain-security.yml` | probed | TLS 1.3 + HSTS; no DNSSEC, CAA, SPF, or DMARC |
| Well-known index | `well-known/lifemote-well-known.yml` | searched | No discovery documents published |
| Packages | `packages/lifemote-packages.yml` | searched | No public SDKs in any registry |
| llms.txt | `llms/lifemote-llms.txt` | generated | Generated from `apis.yml` |

Backed by: 500 Global — https://lifemote.com
