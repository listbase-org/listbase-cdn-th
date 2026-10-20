# คมนาคม (Transport)

2 datasets — 247 records

> Browse at [listbase.org/th/transport/](https://listbase.org/th/transport/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [รหัสสถานที่ UN/LOCODE — ประเทศไทย (ท่าเรือ สนามบิน เทอร์มินัล)](th-unlocode.json) | 203 | 134 KB | [CSV](th-unlocode_TH.csv) | [Excel](th-unlocode_TH.xlsx) | [View](https://listbase.org/th/transport/th-unlocode/) |
| [ท่าอากาศยานในประเทศไทย](th-airports.json) | 44 | 23 KB | [CSV](th-airports_TH.csv) | [Excel](th-airports_TH.xlsx) | [View](https://listbase.org/th/transport/th-airports/) |

## Quick Start

```bash
# List all transport datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="transport") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/transport/th-unlocode.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/transport/)
