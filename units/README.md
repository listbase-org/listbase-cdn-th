# หน่วยวัด (Units & Measurements)

2 datasets — 65 records

> Browse at [listbase.org/th/units/](https://listbase.org/th/units/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [หน่วย SI](si-units.json) | 52 | 23 KB | [CSV](si-units_TH.csv) | [Excel](si-units_TH.xlsx) | [View](https://listbase.org/th/units/si-units/) |
| [หน่วยวัดไทยดั้งเดิม](thai-traditional-units.json) | 13 | 7 KB | [CSV](thai-traditional-units_TH.csv) | [Excel](thai-traditional-units_TH.xlsx) | [View](https://listbase.org/th/units/thai-traditional-units/) |

## Quick Start

```bash
# List all units & measurements datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="units") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/units/si-units.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/units/)
