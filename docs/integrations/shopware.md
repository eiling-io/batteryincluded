---
title: Shopware 6
parent: Integrations
nav_order: 4
---

# Shopware 6 plugin
{: .no_toc }

1. TOC
{:toc}

The native Shopware plugin by BatteryIncluded, developed together with
[Elio Systems](https://www.elio-systems.com/batteryincluded-partner). It replaces the Shopware search and listings with
BatteryIncluded and is configured completely in the Shopware administration.

[Plugin page on batteryincluded.ai](https://batteryincluded.ai/partner/shopware/shopware-6-plugin){: .btn .btn-primary }

## Features

- AI search with search-as-you-type suggestions
- Relevance control by weighting of fields
- Content search next to the products
- Dynamic filters based on the live shop data
- Own sortings and positioning of products
- Promotions, banners and SEO markers
- Display and grouping of variants
- Dynamic product streams
- AI recommendations
- Multilingual and multi sales channel configuration
- Configurable sync and response behaviour

## Requirements

- Shopware 6.5 or newer, the Community Edition included
- Composer
- Access to the private BatteryIncluded Composer registry
- A BatteryIncluded collection and its API key

## Installation

The plugin is not distributed through the Shopware Store but through a private Composer registry:

1. Add the BatteryIncluded registry to the `composer.json` of your shop.
2. Add the authentication for the registry.
3. Install the plugin with Composer.
4. Install and activate both plugins, **Data Discovery Core** and **BatteryIncluded: AI-Suche und AI-Recommendations**.

{: .important }
The registry URL, its credentials and the configuration guide are listed on the
[plugin page](https://batteryincluded.ai/partner/shopware/shopware-6-plugin) of BatteryIncluded.

## Pricing and trial

The plugin comes with your BatteryIncluded licence. A free trial and a demo with your own data are available, see
[pricing](https://batteryincluded.ai/pricing) and [demo](https://batteryincluded.ai/demo).
