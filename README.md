# sobat-krl-master-data

Public master data for KRL Jabodetabek (Commuter Line), LRT, and MRT — served as raw JSON via GitHub.

## Data Source

This data is collected by [sobat-krl-scraper](https://github.com/kangfarih/sobat-krl-scraper), an automated scraper that extracts transit schedules and station information from the following official sources:

| Mode | Source |
|------|--------|
| **KRL** (Commuter Line) | `kci.id` API |
| **MRT Jakarta** | `jakartamrt.co.id` |
| **LRT Jabodebek** | `lrtjabodebek.kai.id` |
| **TransJakarta** | Official GTFS feed |

## Data Files

| File | Description |
|------|-------------|
| `data/krl/stations.json` | All active KRL stations |
| `data/krl/schedules-per-station.json` | Schedules grouped by station |
| `data/krl/routes.json` | Full reconstructed train routes |
| `data/krl/summary.json` | Metadata (last updated, counts) |

## Raw JSON Access

Base URL:
```
https://raw.githubusercontent.com/kangfarih/sobat-krl-master-data/main/
```

Example:
```
https://raw.githubusercontent.com/kangfarih/sobat-krl-master-data/main/data/krl/stations.json
https://raw.githubusercontent.com/kangfarih/sobat-krl-master-data/main/data/krl/routes.json
https://raw.githubusercontent.com/kangfarih/sobat-krl-master-data/main/data/krl/schedules-per-station.json
```

## Data Update

Data is updated daily via an automated pipeline powered by the scraper. See the raw JSON links above for the latest data.
