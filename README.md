# sobat-krl-master-data

Public master data for KRL Jabodetabek (Commuter Line), LRT, and MRT — served as raw JSON via GitHub.

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

Data is updated daily via an automated pipeline. See the raw JSON links above for the latest data.
