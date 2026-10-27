---
title: Symfony
parent: Integrations
nav_order: 2
---

# Symfony Bundle
{: .no_toc }

The Symfony integration of the [PHP SDK](php-sdk). It configures the SDK from the environment, exports your catalog
with one command, keeps the collection in sync when your entities change and puts every API call into the Symfony web
profiler. The right choice for Symfony based shops and applications without a ready-made plugin.

[Documentation](https://bundle.batteryincluded.eiling.io){: .btn .btn-primary .mr-2 }
[GitHub](https://github.com/eiling-io/batteryincluded-bundle){: .btn }

```bash
composer require batteryincluded/batteryincluded-bundle
bin/console bi:status             # check configuration and connection
bin/console bi:export --force     # full import of all data providers
```

## Features

- Configuration from the environment, several collections
- Data providers and own document types for the export
- Sync of single documents, after Doctrine flush or asynchronous with Messenger
- `BrowseSearchStruct` as controller argument, built from the request
- Events and extension points for every step
- Web profiler panel and own log channel
- Demo shop to get started

## Requirements

- PHP 8.2 or higher, Symfony 7 or 8
- A BatteryIncluded collection and its API key

Start with [Getting started](https://bundle.batteryincluded.eiling.io/getting-started). AI coding agents read
[`llms-full.txt`](https://bundle.batteryincluded.eiling.io/llms-full.txt).
