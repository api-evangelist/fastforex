# FastForex

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

FastForex is a fast, reliable REST API providing real-time and historical currency exchange rates for 160+ world currencies, 500+ cryptocurrencies, and 2,300+ FX trading pairs.

**Website:** https://www.fastforex.io  
**Documentation:** https://www.fastforex.io/docs  
**GitHub:** https://github.com/fastforex  
**Blog:** https://www.fastforex.io/hub  
**X:** https://x.com/fastforex_io  

## APIs.json

This repository contains an [APIs.json 0.19](https://apisjson.org) profile for FastForex, cataloging its public API surface, plans, rate limits, and FinOps guidance.

- `apis.yml` - Main APIs.json index
- `plans/fastforex-plans-pricing.yml` - Pricing plans (One, Extra, Premium)
- `rate-limits/fastforex-rate-limits.yml` - API call quotas and rate limit details
- `finops/fastforex-finops.yml` - Cost optimization and budget planning guidance

## Key Features

- 160+ world currencies with real-time mid-market rates
- 500+ cryptocurrencies with live pricing
- 2,300+ FX trading pairs with bid/ask quotes
- OHLC candlestick data for trading applications
- WebSocket streaming (Premium plan)
- Up to 55 years of historical exchange rate data
- Average API response time of 21ms
- Base URL: `https://api.fastforex.io`
- Authentication via `X-API-Key` header
