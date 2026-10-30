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

FastForex is a fast, reliable REST API providing real-time and historical currency exchange rates for 160+ world currencies, 500+ cryptocurrencies, and 2,300+ FX trading pairs. Features include currency conversion, many-to-one and multi-rate lookups, OHLC candlestick data, bid/ask pricing, WebSocket streaming, and up to 55 years of historical data. Average response time of 21ms with 100% uptime SLA.

**Areas:** Foreign Exchange · Financial Data · Exchange Rates · Cryptocurrency · FX Trading · Historical Data · Real-Time Data

## FastForex on APIs.io

Everything profiled for FastForex is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fastforex/](https://apis.io/providers/fastforex/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [FastForex Admin API](https://apis.io/apis/fastforex/fastforex-admin-api/) — Account admin
- [FastForex Crypto API](https://apis.io/apis/fastforex/fastforex-crypto-api/) — Digital currencies, pairs & prices
- [FastForex Currency API](https://apis.io/apis/fastforex/fastforex-currency-api/) — Physical currencies, rates and conversions
- [FastForex Fx API](https://apis.io/apis/fastforex/fastforex-fx-api/) — Realtime FX trading pairs - instruments, prices and history

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [fastforex](https://apis.io/servers/fastforex/fastforex/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Fastforex Agentic Access](https://apis.io/agentic-access/fastforex/fastforex-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [ConvertResponse](https://apis.io/schemas/fastforex/convert-response/)
- [Currency](https://apis.io/schemas/fastforex/currency/)
- [FetchMultiResponse](https://apis.io/schemas/fastforex/fetch-multi-response/)
- [FetchOneResponse](https://apis.io/schemas/fastforex/fetch-one-response/)
- [FxQuoteResponse](https://apis.io/schemas/fastforex/fx-quote-response/)
- [OhlcTimeSeriesResponse](https://apis.io/schemas/fastforex/ohlc-time-series-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Fastforex Context](https://apis.io/jsonld/fastforex/fastforex-context/)

#### Examples (6)

Example requests and responses.

- [Convert](https://apis.io/examples/fastforex/convert/)
- [Fetch Multi](https://apis.io/examples/fastforex/fetch-multi/)
- [Fetch One](https://apis.io/examples/fastforex/fetch-one/)
- [Fx Quote](https://apis.io/examples/fastforex/fx-quote/)
- [Historical](https://apis.io/examples/fastforex/historical/)
- [Ohlc Time Series](https://apis.io/examples/fastforex/ohlc-time-series/)

#### Collections (7)

Postman and Open Collection request collections.

- [fastFOREX.io admin API](https://apis.io/collections/fastforex/open-fastforex-admin-api/)
- [fastFOREX.io admin crypto API](https://apis.io/collections/fastforex/open-fastforex-crypto-api/)
- [fastFOREX.io admin currency API](https://apis.io/collections/fastforex/open-fastforex-currency-api/)
- [fastFOREX.io admin fx API](https://apis.io/collections/fastforex/open-fastforex-fx-api/)
- [fastFOREX.io admin plan-extra API](https://apis.io/collections/fastforex/open-fastforex-plan-extra-api/)
- [fastFOREX.io admin plan-one API](https://apis.io/collections/fastforex/open-fastforex-plan-one-api/)
- [fastFOREX.io admin plan-premium API](https://apis.io/collections/fastforex/open-fastforex-plan-premium-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [FastForex — jsonschema rules](https://apis.io/rules/fastforex/fastforex-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Fastforex Authentication](https://apis.io/security/fastforex/fastforex-authentication/)
- [Fastforex Domain Security](https://apis.io/security/fastforex/fastforex-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Fastforex Plans Pricing](https://apis.io/plans/fastforex/fastforex-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Fastforex Rate Limits](https://apis.io/rate-limits/fastforex/fastforex-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Fastforex Finops](https://apis.io/finops/fastforex/fastforex-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.fastforex.io)
- [Documentation](https://www.fastforex.io/docs)
- [Pricing](https://www.fastforex.io/hub/2026-new-plans-new-features-new-data)
- [Blog](https://www.fastforex.io/hub)

## API Evangelist rating

**Kin Score 31.5** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 54.7 |
| Contract governance | 9.8 |
| Operational transparency | 13.2 |
| Developer ergonomics | 21.4 |
| Access clarity | 18.4 |

**Agent readiness 40.5** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/fastforex/](https://apis.io/providers/fastforex/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for FastForex: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fastforex/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
