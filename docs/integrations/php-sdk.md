---
title: PHP SDK
parent: Integrations
nav_order: 4
---

# PHP SDK
{: .no_toc }

The official PHP SDK for BatteryIncluded. It syncs your products and content to a collection and gives you typed access
to search, suggestions and recommendations – for every PHP application, framework or not.

[Documentation](https://sdk.batteryincluded.eiling.io){: .btn .btn-primary .mr-2 }
[GitHub](https://github.com/eiling-io/batteryincluded-php-sdk){: .btn }

```bash
composer require batteryincluded/batteryincluded-php-sdk
```

```php
$apiClient = new ApiClient(new CurlHttpClient(), 'https://api.batteryincluded.io/api/v1/collections/', $collection, $apiKey);

// 1. sync a product
$product = new ProductBaseDto('1002');
$product->setName('Ultra HD LED TV 65"');
$product->setPrice(699);
(new SyncService($apiClient))->syncOneOrManyElements($product);

// 2. search for it
$searchStruct = new BrowseSearchStruct();
$searchStruct->setQuery('TV');
$result = (new BrowseService($apiClient))->browse($searchStruct);
```

## Features

- DTOs for products and blog posts, full and batched imports, partial updates
- Translations and availability per country or sales channel
- Search with filters, sorting, pagination and facets
- Suggestions, similar searches and highlights
- Product and cart recommendations, presets
- Demo shop built with the SDK

## Requirements

- PHP 8.2 or higher with the `curl` and `mbstring` extensions
- A BatteryIncluded collection and its API key

Start with [Getting started](https://sdk.batteryincluded.eiling.io/getting-started). AI coding agents read
[`llms-full.txt`](https://sdk.batteryincluded.eiling.io/llms-full.txt).
