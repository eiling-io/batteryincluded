---
title: Integrations
nav_order: 3
has_children: true
permalink: /integrations/
---

# Integrations
{: .no_toc }

1. TOC
{:toc}

## Which integration fits?

| You run… | Use | You get out of the box |
|---|---|---|
| Shopware 6.5 or newer | [Shopware 6 plugin](shopware) | Search, suggestions, filters, listings, recommendations, merchandising in the Shopware admin |
| Sylius 2.2 or 2.3 | [Sylius Plugin](sylius) | Search page, suggestions, category pages, recommendations, sliders, channel export |
| A Symfony application | [Symfony Bundle](symfony) | Configuration, export, sync, Doctrine and Messenger support, search arguments in controllers, profiler |
| Any other PHP application | [PHP SDK](php-sdk) | Typed API client, DTOs, sync, search, suggestions and recommendations services |
| Another language or platform | [API & data feed](api) | The REST API, documented in Postman |

Rule of thumb: take the most specific package for your stack. Anything a plugin does not cover can still be added with
the package below it.

## How the PHP packages fit together

The open source packages by [eiling.io](https://eiling.io) build on each other:

| Package | Builds on | Responsibility |
|---|---|---|
| [Sylius Plugin](https://sylius.batteryincluded.eiling.io) | Symfony Bundle | Products of a channel as documents, shop pages, Twig components |
| [Symfony Bundle](https://bundle.batteryincluded.eiling.io) | PHP SDK | Configuration, collections, console commands, events, profiler |
| [PHP SDK](https://sdk.batteryincluded.eiling.io) | – | API client, DTOs, search structs and responses |

The [Shopware 6 plugin](shopware) is developed by BatteryIncluded and its partner Elio Systems and does not depend on
these packages.

## Help with your integration

{: .note }
No matter which way you choose, I'm happy to help – from the first export to the last template.
[Get help](../support).
