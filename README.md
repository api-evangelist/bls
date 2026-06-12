# Bureau of Labor Statistics (bls)

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
