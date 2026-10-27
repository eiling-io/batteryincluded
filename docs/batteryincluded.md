---
title: What is BatteryIncluded?
nav_order: 2
---

# What is BatteryIncluded?
{: .no_toc }

1. TOC
{:toc}

[BatteryIncluded](https://batteryincluded.ai) is a German SaaS for onsite search, merchandising and product
recommendations. Your shop sends its catalog to a BatteryIncluded *collection*, the shop asks the API for search
results, suggestions and recommendations and renders them – the heavy lifting happens outside of your shop system.

## Modules

| Module | What it does |
|---|---|
| [Volt Search®](https://batteryincluded.ai/framework/volt-search) | Hybrid LLM search: understands intent, typos, synonyms and complex queries, search-as-you-type suggestions |
| [Volt Merchandising](https://batteryincluded.ai/framework/volt-merchandising) | Steer listings and search results: boost and bury, pinning, redirects, banners, promotions |
| [AI Recommendations](https://batteryincluded.ai/framework/ai-recommendations) | Similar products, cross- and upselling on the product page and in the cart – without user tracking |
| [Reasoning](https://batteryincluded.ai/framework/reasoning) | Analyses search terms, clicks, carts and orders and proposes synonyms, redirects or boosts – live only after your approval |

## Why BatteryIncluded

- **Cookieless and GDPR compliant** – no tracking, no consent banner needed for search and recommendations.
- **Fast** – answers in well under a second, even with tens of thousands of products, because search runs decoupled
  from your shop.
- **In the hands of your team** – marketing and sales configure filters, relevance and merchandising in the
  [portal](https://portal.batteryincluded.io/), results stay traceable.
- **Any platform** – the integration is a data feed plus API calls, so it works with every shop system and headless
  setups.
- **Fixed price** – package based licences instead of per-request billing, see
  [pricing](https://batteryincluded.ai/pricing).

## How an integration works

Every integration, whether a plugin or your own code, does the same three things:

1. **Export** – products (and optionally content like blog posts or categories) are sent to the collection, once in
   full and then kept in sync on every change.
2. **Configure** – filterable fields, filters, suggest fields and relevance are set up in the BatteryIncluded portal,
   see [backend configuration](https://sdk.batteryincluded.eiling.io/backend-configuration).
3. **Render** – the shop calls the API for search results, facets, suggestions and recommendations and shows them in
   its own templates.

The plugins do all three for you, the [PHP SDK](integrations/php-sdk) and the [API](integrations/api) let you build
each step yourself. Continue with [choosing your integration](integrations/).

## Try it

BatteryIncluded offers a [live demo with your own data](https://batteryincluded.ai/demo) and a free trial. You need a
collection and its API key for every integration on this site.
