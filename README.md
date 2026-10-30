# Netography

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

Netography Fusion is a SaaS network defense and observability platform (now Vectra Fusion) that ingests cloud VPC flow logs, DNS, and NetFlow/sFlow from AWS, Azure, GCP, IBM, and Oracle to deliver real-time network detection and response without sensors or agents. Its REST API (base https://api.netography.com) exposes analytics and NQL raw-record search, IP/port context labels, threat intelligence lookups, MITRE ATT&CK mapped detection models, response policies and block lists, cloud traffic sources, and context/response integrations. Authentication is a JWT bearer token minted from a NETOSECRET API key. An official MCP server (neto-mcp) exposes the query endpoints to agents.

**Areas:** Network Security · Network Detection and Response · Cloud Security · Network Observability · Flow Data · Threat Intelligence · DDoS · Cybersecurity · MITRE ATT&CK · Company

## Netography on APIs.io

Everything profiled for Netography is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/netography/](https://apis.io/providers/netography/)** — or go straight to one of the APIs or properties below.

### APIs (28)

- [Netography Analytics API](https://apis.io/apis/netography/netography-analytics-api/) — The Analytics API from Netography — 5 operation(s) for analytics.
- [Netography API Keys API](https://apis.io/apis/netography/netography-api-keys-api/) — The API Keys API from Netography — 3 operation(s) for api keys.
- [Netography Authentication API](https://apis.io/apis/netography/netography-authentication-api/) — The Authentication API from Netography — 3 operation(s) for authentication.
- [Netography Auto Thresholds API](https://apis.io/apis/netography/netography-auto-thresholds-api/) — The Auto Thresholds API from Netography — 3 operation(s) for auto thresholds.
- [Netography Configuration API](https://apis.io/apis/netography/netography-configuration-api/) — The Configuration API from Netography — 1 operation(s) for configuration.
- [Netography Detect and Respond - Context Creation Models API](https://apis.io/apis/netography/netography-detect-and-respond-context-creation-models-api/) — The Detect and Respond - Context Creation Models API from Netography — 6 operation(s) for detect and respond - context creation models.
- [Netography Detect and Respond - Detection Categories API](https://apis.io/apis/netography/netography-detect-and-respond-detection-categories-api/) — The Detect and Respond - Detection Categories API from Netography — 2 operation(s) for detect and respond - detection categories.
- [Netography Detect and Respond - Response Policies API](https://apis.io/apis/netography/netography-detect-and-respond-response-policies-api/) — The Detect and Respond - Response Policies API from Netography — 5 operation(s) for detect and respond - response policies.
- [Netography Detect and Respond - Threshold Overrides API](https://apis.io/apis/netography/netography-detect-and-respond-threshold-overrides-api/) — The Detect and Respond - Threshold Overrides API from Netography — 4 operation(s) for detect and respond - threshold overrides.
- [Netography Detect and Respond - Traffic Detection Models API](https://apis.io/apis/netography/netography-detect-and-respond-traffic-detection-models-api/) — The Detect and Respond - Traffic Detection Models API from Netography — 6 operation(s) for detect and respond - traffic detection models.
- [Netography Integrations - Context API](https://apis.io/apis/netography/netography-integrations-context-api/) — The Integrations - Context API from Netography — 4 operation(s) for integrations - context.
- [Netography Integrations - Response API](https://apis.io/apis/netography/netography-integrations-response-api/) — The Integrations - Response API from Netography — 3 operation(s) for integrations - response.
- [Netography Intelligence API](https://apis.io/apis/netography/netography-intelligence-api/) — The Intelligence API from Netography — 3 operation(s) for intelligence.
- [Netography Labels - IPs API](https://apis.io/apis/netography/netography-labels-ips-api/) — The Labels - IPs API from Netography — 6 operation(s) for labels - ips.
- [Netography Labels - Ports API](https://apis.io/apis/netography/netography-labels-ports-api/) — The Labels - Ports API from Netography — 10 operation(s) for labels - ports.
- [Netography MITRE ATT&CK API](https://apis.io/apis/netography/netography-mitre-att-ck-api/) — The MITRE ATT&CK API from Netography — 2 operation(s) for mitre att&ck.
- [Netography Raw Records - Fetch API](https://apis.io/apis/netography/netography-raw-records-fetch-api/) — The Raw Records - Fetch API from Netography — 1 operation(s) for raw records - fetch.
- [Netography Raw Records - Search API](https://apis.io/apis/netography/netography-raw-records-search-api/) — The Raw Records - Search API from Netography — 2 operation(s) for raw records - search.
- [Netography Resellers API](https://apis.io/apis/netography/netography-resellers-api/) — The Resellers API from Netography — 4 operation(s) for resellers.
- [Netography Roles API](https://apis.io/apis/netography/netography-roles-api/) — The Roles API from Netography — 3 operation(s) for roles.
- [Netography Settings - Security API](https://apis.io/apis/netography/netography-settings-security-api/) — The Settings - Security API from Netography — 1 operation(s) for settings - security.
- [Netography Settings - Traffic Classification API](https://apis.io/apis/netography/netography-settings-traffic-classification-api/) — The Settings - Traffic Classification API from Netography — 4 operation(s) for settings - traffic classification.
- [Netography Tags API](https://apis.io/apis/netography/netography-tags-api/) — The Tags API from Netography — 5 operation(s) for tags.
- [Netography Traffic Sources - Devices API](https://apis.io/apis/netography/netography-traffic-sources-devices-api/) — The Traffic Sources - Devices API from Netography — 11 operation(s) for traffic sources - devices.
- [Netography Traffic Sources - DNS Devices API](https://apis.io/apis/netography/netography-traffic-sources-dns-devices-api/) — The Traffic Sources - DNS Devices API from Netography — 5 operation(s) for traffic sources - dns devices.
- [Netography Traffic Sources - VPCs API](https://apis.io/apis/netography/netography-traffic-sources-vpcs-api/) — The Traffic Sources - VPCs API from Netography — 8 operation(s) for traffic sources - vpcs.
- [Netography Users API](https://apis.io/apis/netography/netography-users-api/) — The Users API from Netography — 3 operation(s) for users.
- [Netography Blocklist API](https://apis.io/apis/netography/netography-blocklist-api/) — The Blocklist API from Netography — 1 operation(s) for blocklist.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Netography Webhooks](https://apis.io/asyncapis/netography/netography-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [netography](https://apis.io/servers/netography/netography/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Netography Agentic Access](https://apis.io/agentic-access/netography/netography-agentic-access/)

#### Collections (28)

Postman and Open Collection request collections.

- [Netography (Vectra Fusion) Analytics API](https://apis.io/collections/netography/open-netography-analytics-api/)
- [Netography (Vectra Fusion) Analytics API Keys API](https://apis.io/collections/netography/open-netography-api-keys-api/)
- [Netography (Vectra Fusion) Analytics Authentication API](https://apis.io/collections/netography/open-netography-authentication-api/)
- [Netography (Vectra Fusion) Analytics Auto Thresholds API](https://apis.io/collections/netography/open-netography-auto-thresholds-api/)
- [Netography (Vectra Fusion) Analytics Block List API](https://apis.io/collections/netography/open-netography-block-list-api/)
- [Netography (Vectra Fusion) Analytics Configuration API](https://apis.io/collections/netography/open-netography-configuration-api/)
- [Netography (Vectra Fusion) Analytics Detect and Respond - Context Creation Models API](https://apis.io/collections/netography/open-netography-detect-and-respond-context-creation-models-api/)
- [Netography (Vectra Fusion) Analytics Detect and Respond - Detection Categories API](https://apis.io/collections/netography/open-netography-detect-and-respond-detection-categories-api/)
- [Netography (Vectra Fusion) Analytics Detect and Respond - Response Policies API](https://apis.io/collections/netography/open-netography-detect-and-respond-response-policies-api/)
- [Netography (Vectra Fusion) Analytics Detect and Respond - Threshold Overrides API](https://apis.io/collections/netography/open-netography-detect-and-respond-threshold-overrides-api/)
- [Netography (Vectra Fusion) Analytics Detect and Respond - Traffic Detection Models API](https://apis.io/collections/netography/open-netography-detect-and-respond-traffic-detection-models-api/)
- [Netography (Vectra Fusion) Analytics Integrations - Context API](https://apis.io/collections/netography/open-netography-integrations-context-api/)
- [Netography (Vectra Fusion) Analytics Integrations - Response API](https://apis.io/collections/netography/open-netography-integrations-response-api/)
- [Netography (Vectra Fusion) Analytics Intelligence API](https://apis.io/collections/netography/open-netography-intelligence-api/)
- [Netography (Vectra Fusion) Analytics Labels - IPs API](https://apis.io/collections/netography/open-netography-labels-ips-api/)
- [Netography (Vectra Fusion) Analytics Labels - Ports API](https://apis.io/collections/netography/open-netography-labels-ports-api/)
- [Netography (Vectra Fusion) Analytics MITRE ATT&CK API](https://apis.io/collections/netography/open-netography-mitre-att-ck-api/)
- [Netography (Vectra Fusion) Analytics Raw Records - Fetch API](https://apis.io/collections/netography/open-netography-raw-records-fetch-api/)
- [Netography (Vectra Fusion) Analytics Raw Records - Search API](https://apis.io/collections/netography/open-netography-raw-records-search-api/)
- [Netography (Vectra Fusion) Analytics Resellers API](https://apis.io/collections/netography/open-netography-resellers-api/)
- [Netography (Vectra Fusion) Analytics Roles API](https://apis.io/collections/netography/open-netography-roles-api/)
- [Netography (Vectra Fusion) Analytics Settings - Security API](https://apis.io/collections/netography/open-netography-settings-security-api/)
- [Netography (Vectra Fusion) Analytics Settings - Traffic Classification API](https://apis.io/collections/netography/open-netography-settings-traffic-classification-api/)
- [Netography (Vectra Fusion) Analytics Tags API](https://apis.io/collections/netography/open-netography-tags-api/)
- [Netography (Vectra Fusion) Analytics Traffic Sources - Devices API](https://apis.io/collections/netography/open-netography-traffic-sources-devices-api/)
- …and 3 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Netography Openapi Overlay](https://apis.io/overlays/netography/netography-openapi-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Netography Authentication](https://apis.io/security/netography/netography-authentication/)
- [Netography Domain Security](https://apis.io/security/netography/netography-domain-security/)
- [Netography Vulnerability Disclosure](https://apis.io/security/netography/netography-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://netography.com/)
- [Documentation](https://docs.fusion.vectra.ai/)
- [Getting started](https://docs.fusion.vectra.ai/readme.md)
- [API reference](https://docs.fusion.vectra.ai/api-reference)
- [GitHub](https://github.com/netography)

## API Evangelist rating

**Kin Score 37.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 54.4 |
| Contract governance | 4.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 58.9 |
| Access clarity | 0.0 |

**Agent readiness 29.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/netography/](https://apis.io/providers/netography/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Netography: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/netography/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
