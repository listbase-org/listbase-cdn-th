# อาหารและโภชนาการ (Food & Nutrition)

3 datasets — 527 records

> Browse at [listbase.org/th/food/](https://listbase.org/th/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ร้านอาหารมิชลินไกด์ในประเทศไทย](th-ran-ahan-michelin.json) | 485 | 477 KB | [CSV](th-ran-ahan-michelin_TH.csv) | [Excel](th-ran-ahan-michelin_TH.xlsx) | [View](https://listbase.org/th/food/th-ran-ahan-michelin/) |
| [อาหารไทย พร้อมแฟลกแพ้อาหาร แคลอรี่ และส่วนผสม (33 เมนู)](th-ahan-thai-flags.json) | 33 | 15 KB | [CSV](th-ahan-thai-flags_TH.csv) | [Excel](th-ahan-thai-flags_TH.xlsx) | [View](https://listbase.org/th/food/th-ahan-thai-flags/) |
| [ประเภทเครื่องแกงและพริกแกงไทย](thai-curry-pastes.json) | 9 | 10 KB | [CSV](thai-curry-pastes_TH.csv) | [Excel](thai-curry-pastes_TH.xlsx) | [View](https://listbase.org/th/food/thai-curry-pastes/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/food/th-ran-ahan-michelin.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/food/)
