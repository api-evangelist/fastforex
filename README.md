# FastForex

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
