# Lifemote

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
