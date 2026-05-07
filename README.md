# ValueRay (valueray)

AI-ready financial data API for stocks and ETFs. ValueRay aggregates technical, quantitative, and sentiment data with risk metrics, peer percentiles, and market regime signals into AI/LLM-friendly responses optimized for agents that need explainable financial overviews of specific symbols.

- **Source:** https://www.valueray.com/
- **API Documentation:** https://www.valueray.com/api
- **Field Definitions:** https://www.valueray.com/prompts/_explanations.md
- **Inbox issue:** [#898](https://github.com/api-evangelist/inbox/issues/898)

## APIs

- **ValueRay Symbol Data API** — Returns aggregated AI-ready technical, quantitative, sentiment, risk, and performance data for a single stock or ETF symbol. See [`openapi/valueray-symbol-data-openapi.yml`](openapi/valueray-symbol-data-openapi.yml).

## Tags

`AI/LLM`, `ETF`, `Financial Data`, `Quantitative`, `Stocks`, `Technical Analysis`

## Artifacts

| Artifact | Path |
|---|---|
| OpenAPI | [`openapi/valueray-symbol-data-openapi.yml`](openapi/valueray-symbol-data-openapi.yml) |
| Examples | [`examples/valueray-getSymbolData-example.json`](examples/valueray-getSymbolData-example.json) |
| Spectral Rules | [`rules/valueray-rules.yml`](rules/valueray-rules.yml) |
| Naftiko Capability | [`capabilities/valueray-symbol-data-capability.yaml`](capabilities/valueray-symbol-data-capability.yaml) |
| JSON Schema | [`json-schema/valueray-symbol-data-schema.json`](json-schema/valueray-symbol-data-schema.json) |
| JSON Structure | [`json-structure/valueray-symbol-data-structure.json`](json-structure/valueray-symbol-data-structure.json) |
| JSON-LD Context | [`json-ld/valueray-context.jsonld`](json-ld/valueray-context.jsonld) |
| Vocabulary | [`vocabulary/valueray-vocabulary.yml`](vocabulary/valueray-vocabulary.yml) |
| Plans and Pricing | [`plans/valueray-plans-pricing.yml`](plans/valueray-plans-pricing.yml) |
| Rate Limits | [`rate-limits/valueray-rate-limits.yml`](rate-limits/valueray-rate-limits.yml) |
| FinOps | [`finops/valueray-finops.yml`](finops/valueray-finops.yml) |

## Plans, Rate Limits, and FinOps

ValueRay currently exposes a free public tier of the Symbol Data API throttled at one request per minute. A premium tier has been signaled but is not yet published. Plans, rate limits, and FinOps profiles are marked `reconciled: false` until ValueRay publishes formal pricing and rate-limit documentation.
