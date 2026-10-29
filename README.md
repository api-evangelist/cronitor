# Cronitor

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

Cronitor is a cron job and scheduled task monitoring platform that provides developers with instant alerts when jobs fail, run too long, or don't run at all. The platform offers a REST API for creating and managing monitors, recording job telemetry events, and configuring alert policies across teams. Cronitor supports job monitoring, heartbeat monitoring, website uptime checks, and Real User Monitoring (RUM), all accessible via a versioned HTTP API using Basic Auth with scoped API keys. SDKs are available for Python, Node.js, Ruby, PHP, Java, Go, and other languages through the cronitorio GitHub organization.

**Areas:** Monitoring · Cron Jobs · Scheduled Tasks · Alerting · Uptime · Telemetry · Status Pages · Scheduling

## Cronitor on APIs.io

Everything profiled for Cronitor is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cronitor/](https://apis.io/providers/cronitor/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Cronitor Telemetry API](https://apis.io/apis/cronitor/cronitor-cronitor-telemetry-api-api/) — The Cronitor Telemetry API API from Cronitor — 1 operation(s) for cronitor telemetry api.
- [Cronitor Groups API](https://apis.io/apis/cronitor/cronitor-groups-api/) — The Groups API from Cronitor — 3 operation(s) for groups.
- [Cronitor Notifications API](https://apis.io/apis/cronitor/cronitor-notifications-api/) — The Notifications API from Cronitor — 2 operation(s) for notifications.
- [Cronitor P API](https://apis.io/apis/cronitor/cronitor-p-api/) — The P API from Cronitor — 1 operation(s) for p.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [cronitor](https://apis.io/servers/cronitor/cronitor/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cronitor Agentic Access](https://apis.io/agentic-access/cronitor/cronitor-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Cronitor Monitor](https://apis.io/schemas/cronitor/cronitor-monitor/)
- [Cronitor Notification List](https://apis.io/schemas/cronitor/cronitor-notification-list/)
- [Cronitor Telemetry Event](https://apis.io/schemas/cronitor/cronitor-telemetry-event/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cronitor Context](https://apis.io/jsonld/cronitor/cronitor-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cronitor Vocabulary](https://apis.io/vocabularies/cronitor/cronitor-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Cronitor Create Monitor Example](https://apis.io/examples/cronitor/cronitor-create-monitor-example/)
- [Cronitor List Monitors Example](https://apis.io/examples/cronitor/cronitor-list-monitors-example/)
- [Cronitor Telemetry Event Example](https://apis.io/examples/cronitor/cronitor-telemetry-event-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Cronitor Groups and Notifications Cronitor Telemetry API API](https://apis.io/collections/cronitor/open-cronitor-cronitor-telemetry-api-api/)
- [Cronitor and Notifications Cronitor Telemetry API Groups API](https://apis.io/collections/cronitor/open-cronitor-groups-api/)
- [Cronitor Groups and Notifications Cronitor Telemetry API Monitors API](https://apis.io/collections/cronitor/open-cronitor-monitors-api/)
- [Cronitor Groups and Cronitor Telemetry API Notifications API](https://apis.io/collections/cronitor/open-cronitor-notifications-api/)
- [Cronitor Groups and Notifications Cronitor Telemetry API P API](https://apis.io/collections/cronitor/open-cronitor-p-api/)
- [Cronitor Groups and Notifications Cronitor Telemetry API Search API](https://apis.io/collections/cronitor/open-cronitor-search-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cronitor — jsonschema rules](https://apis.io/rules/cronitor/cronitor-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cronitor Authentication](https://apis.io/security/cronitor/cronitor-authentication/)
- [Cronitor Domain Security](https://apis.io/security/cronitor/cronitor-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cronitor Plans Pricing](https://apis.io/plans/cronitor/cronitor-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cronitor Rate Limits](https://apis.io/rate-limits/cronitor/cronitor-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cronitor Finops](https://apis.io/finops/cronitor/cronitor-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cronitor.io)
- [Documentation](https://cronitor.io/docs)
- [Pricing](https://cronitor.io/pricing)
- [Blog](https://cronitor.io/cronicle)
- [GitHub](https://github.com/cronitorio)
- [Status](https://status.cronitor.io)

## API Evangelist rating

**Kin Score 33.6** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 53.2 |
| Contract governance | 23.5 |
| Operational transparency | 18.4 |
| Developer ergonomics | 25.0 |
| Access clarity | 18.4 |

**Agent readiness 40.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | mostly |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cronitor/](https://apis.io/providers/cronitor/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cronitor: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cronitor/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
