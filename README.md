# Bureau of Labor Statistics (bls)

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

The Bureau of Labor Statistics (BLS) is the principal statistical agency of the U.S. federal government for labor economics and employment data. The BLS Public Data API provides developers programmatic access to the full catalog of official federal labor and economic statistics, including employment figures, unemployment rates, Consumer Price Index (CPI), Producer Price Index (PPI), wages and earnings, and broader economic productivity indicators. Two API tiers are available: an unauthenticated Version 1.0 for lightweight exploration and a free-registered Version 2.0 that unlocks higher rate limits, catalog metadata, and statistical calculations. All API access is free of charge as a public-sector data service.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/bls/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=bls-api-evangelist&utm_content=repo

---

## Tags

Bureau of Labor Statistics, BLS, Employment, Unemployment, CPI, Consumer Price Index, PPI, Producer Price Index, Wages, Labor Statistics, Economic Indicators, Federal Government, Open Data

---

## APIs

### BLS Public Data API

The BLS Public Data API is the primary REST interface for retrieving published historical time-series data across all BLS statistical programs. Version 1.0 requires no registration; Version 2.0 uses a free API key for higher limits and richer features.

- **Documentation:** https://www.bls.gov/developers/home.htm
- **Base URL:** https://api.bls.gov/publicAPI/v2
- **Registration:** https://data.bls.gov/registrationEngine/
- **FAQ:** https://www.bls.gov/developers/api_faqs.htm

---

## Plans, Rate Limits, and FinOps

### Plans

| Plan | Cost | Daily Queries | Series/Request | Years/Request |
|------|------|--------------|----------------|--------------|
| Unregistered (v1.0) | Free | 25 | 25 | 10 |
| Registered (v2.0) | Free | 500 | 50 | 20 |

Full plan details: [plans/bls-plans-pricing.yml](plans/bls-plans-pricing.yml)

### Rate Limits

The API enforces daily query quotas per IP (unregistered) or per API key (registered). There are no documented per-second burst limits.

Full rate limit details: [rate-limits/bls-rate-limits.yml](rate-limits/bls-rate-limits.yml)

### FinOps

The BLS API carries no direct monetary cost. FinOps considerations center on operational efficiency — caching frequently requested series, batching multi-series POST requests, and aligning refresh cadence to the BLS release calendar.

Full FinOps details: [finops/bls-finops.yml](finops/bls-finops.yml)

---

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

---

## Common

| Type | URL |
|------|-----|
| Website | https://www.bls.gov |
| Documentation | https://www.bls.gov/developers/home.htm |
| GitHub Topics | https://github.com/topics/bureau-of-labor-statistics |
| LinkedIn | https://www.linkedin.com/company/bureau-of-labor-statistics |
| Blog | https://www.bls.gov/bls/news.htm |
| Pricing | https://www.bls.gov/developers/home.htm |
| Status / FAQ | https://www.bls.gov/developers/api_faqs.htm |
| X / Twitter | https://x.com/BLS_gov |

---

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
