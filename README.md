# ValueRay (valueray)

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

AI-ready financial data API for stocks and ETFs. ValueRay aggregates technical, quantitative, and sentiment data with risk metrics, peer percentiles, and market regime signals into AI/LLM-friendly responses optimized for agents that need explainable financial overviews of specific symbols.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/valueray/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/valueray/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI/LLM
- ETF
- Financial Data
- Quantitative
- Stocks
- Technical Analysis

## Timestamps

- **Created:** 2026-05-06
- **Modified:** 2026-05-19

## APIs

### ValueRay Symbol Data API

Returns a comprehensive AI-ready snapshot of a single stock or ETF symbol, aggregating core identifiers (code, ISIN, exchange, sector, industry, peer group), market data (market cap, last price, 52-week range), dividend information (rate, yield, payout, growth, streak), technical indicators (EMA, SMA, ATR, RSI, volatility, volume), risk metrics (safety score, beta, alpha, Sharpe ratio, max drawdown, VaR, tail risk), sentiment (VRO score, buy signals, sector and industry rotation), support and resistance levels, zigzag pivot points, change points, and performance returns from 1d through 5y. Responses include field explanation pointers so AI agents can ground their analysis in published metric definitions.

- **Human URL:** [https://www.valueray.com/api](https://www.valueray.com/api)
- **Base URL:** `https://www.valueray.com/api/v1`

#### Tags

- AI/LLM
- ETF
- Quantitative
- Sentiment
- Stocks
- Symbol Data
- Technical Analysis

#### Properties

- [OpenAPI](openapi/valueray-symbol-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/valueray-symbol-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/valueray-symbol-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://www.valueray.com/api)
- [Field Definitions](https://www.valueray.com/prompts/_explanations.md)

## Common Properties

- [Website](https://www.valueray.com/)
- [Documentation](https://www.valueray.com/api)
- [Field Definitions](https://www.valueray.com/prompts/_explanations.md)
- [Screener](https://www.valueray.com/presets/long-setups)
- [Plans](plans/valueray-plans-pricing.yml)
- [Rate Limits](rate-limits/valueray-rate-limits.yml)
- [Fin Ops](finops/valueray-finops.yml)
- [Vocabulary](vocabulary/valueray-vocabulary.yml)
- [JSON-LD](json-ld/valueray-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [L L Ms Txt](https://www.valueray.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
