# หน่วยวัด (Units & Measurements)

6 datasets — 281 records

> Browse at [listbase.org/th/units/](https://listbase.org/th/units/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ชุดข้อมูลปัจจัยการแปลงหน่วยที่ครอบคลุม](units-conversions.json) | 83 | 21 KB | [CSV](units-conversions_TH.csv) | [Excel](units-conversions_TH.xlsx) | [View](https://listbase.org/th/units/units-conversions/) |
| [Temperature Conversion Matrix Dataset](units-temperatures.json) | 55 | 14 KB | [CSV](units-temperatures_TH.csv) | [Excel](units-temperatures_TH.xlsx) | [View](https://listbase.org/th/units/units-temperatures/) |
| [หน่วย SI](si-units.json) | 52 | 23 KB | [CSV](si-units_TH.csv) | [Excel](si-units_TH.xlsx) | [View](https://listbase.org/th/units/si-units/) |
| [ชุดข้อมูลตารางแปลงไซส์รองเท้าสากล](units-shoe-sizes.json) | 43 | 11 KB | [CSV](units-shoe-sizes_TH.csv) | [Excel](units-shoe-sizes_TH.xlsx) | [View](https://listbase.org/th/units/units-shoe-sizes/) |
| [Clothing Size Standards Dataset](units-clothing-sizes.json) | 35 | 11 KB | [CSV](units-clothing-sizes_TH.csv) | [Excel](units-clothing-sizes_TH.xlsx) | [View](https://listbase.org/th/units/units-clothing-sizes/) |
| [หน่วยวัดไทยดั้งเดิม](thai-traditional-units.json) | 13 | 7 KB | [CSV](thai-traditional-units_TH.csv) | [Excel](thai-traditional-units_TH.xlsx) | [View](https://listbase.org/th/units/thai-traditional-units/) |

## Quick Start

```bash
# List all units & measurements datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="units") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/units/units-conversions.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/units/)
