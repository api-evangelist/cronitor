# Cronitor (cronitor)

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

Cronitor is a cron job and scheduled task monitoring platform that provides developers with instant alerts when jobs fail, run too long, or don't run at all. The platform exposes a versioned REST API for creating and managing monitors, recording job telemetry events, and configuring alert policies. Cronitor supports job monitoring, heartbeat monitoring, website uptime checks, and Real User Monitoring (RUM), with SDKs available for Python, Node.js, Ruby, PHP, Java, Go, and other languages.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/cronitor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cronitor/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cronitor-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cronitor-api-evangelist&utm_content=repo)

## Tags

- Monitoring
- Cron Jobs
- Scheduled Tasks
- Alerting
- Uptime
- Telemetry
- Status Pages

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Cronitor Monitors API | Create, update, retrieve, delete, clone, and pause monitors for cron jobs, heartbeats, uptime checks, and sites. | [Docs](https://cronitor.io/docs/monitors-api) |
| Cronitor Telemetry API | Record job execution events (run, complete, fail, ok) to monitors via lightweight HTTP pings. | [Docs](https://cronitor.io/docs/telemetry-api) |
| Cronitor Sites API | Manage Real User Monitoring (RUM) sites for end-user browser session performance tracking. | [Docs](https://cronitor.io/docs/sites-api) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/cronitor-plans-pricing.yml](plans/cronitor-plans-pricing.yml) |
| Rate Limits | [rate-limits/cronitor-rate-limits.yml](rate-limits/cronitor-rate-limits.yml) |
| FinOps | [finops/cronitor-finops.yml](finops/cronitor-finops.yml) |

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://cronitor.io |
| Documentation | https://cronitor.io/docs |
| GitHub Organization | https://github.com/cronitorio |
| LinkedIn | https://www.linkedin.com/company/cronitor |
| Blog / Newsletter | https://cronitor.io/cronicle |
| Pricing | https://cronitor.io/pricing |
| Status Page | https://status.cronitor.io |
| X (Twitter) | https://x.com/cronitorio |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
