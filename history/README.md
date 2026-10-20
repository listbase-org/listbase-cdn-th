# ประวัติศาสตร์ (History)

2 datasets — 18 records

> Browse at [listbase.org/th/history/](https://listbase.org/th/history/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [พระมหากษัตริย์ในราชวงศ์จักรี](thai-kings.json) | 10 | 7 KB | [CSV](thai-kings_TH.csv) | [Excel](thai-kings_TH.xlsx) | [View](https://listbase.org/th/history/thai-kings/) |
| [ยุคต่างๆ ทางประวัติศาสตร์ไทย](thai-eras.json) | 8 | 7 KB | [CSV](thai-eras_TH.csv) | [Excel](thai-eras_TH.xlsx) | [View](https://listbase.org/th/history/thai-eras/) |

## Quick Start

```bash
# List all history datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="history") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/history/thai-kings.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/history/)
