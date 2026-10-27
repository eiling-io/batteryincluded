---
title: Sylius
parent: Integrations
nav_order: 3
---

# Sylius Plugin
{: .no_toc }

BatteryIncluded in your Sylius 2 shop: a search page with filters and sorting, search-as-you-type suggestions in the
header, category pages served by BatteryIncluded and product recommendations on the product page and in the cart. The
plugin exports the products of every channel into its collection and is built on the
[Symfony Bundle](symfony).

[Documentation](https://sylius.batteryincluded.eiling.io){: .btn .btn-primary .mr-2 }
[GitHub](https://github.com/eiling-io/batteryincluded-sylius){: .btn }

```bash
composer require eiling-io/sylius-battery-included-plugin:dev-main
bin/console bi:export --force
```

## Features

- Search page with facets, sorting and pagination
- Suggestions in the header while typing
- Category pages served by BatteryIncluded
- Recommendations on the product page and in the cart, preset sliders
- Channel to collection mapping, export and sync with `bi:export` and `bi:sync`
- Extensible through template overrides, Twig hooks and events

## Requirements

- PHP 8.2 or higher (8.3 with Sylius 2.3)
- Sylius 2.2 or 2.3, Symfony 7.4
- A BatteryIncluded collection and its API key

Start with [Getting started](https://sylius.batteryincluded.eiling.io/getting-started). AI coding agents read
[`llms-full.txt`](https://sylius.batteryincluded.eiling.io/llms-full.txt).
