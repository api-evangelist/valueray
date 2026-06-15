# ValueRay (valueray)

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
