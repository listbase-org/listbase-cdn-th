# เกษตรกรรม (Agriculture)

3 datasets — 28 records

> Browse at [listbase.org/th/agriculture/](https://listbase.org/th/agriculture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ตารางผลไม้ไทยตามฤดูกาล](thai-fruits-seasons.json) | 12 | 9 KB | [CSV](thai-fruits-seasons_TH.csv) | [Excel](thai-fruits-seasons_TH.xlsx) | [View](https://listbase.org/th/agriculture/thai-fruits-seasons/) |
| [พืชเศรษฐกิจที่สำคัญของไทย](economic-crops.json) | 10 | 9 KB | [CSV](economic-crops_TH.csv) | [Excel](economic-crops_TH.xlsx) | [View](https://listbase.org/th/agriculture/economic-crops/) |
| [ข้อมูลและภูมิศาสตร์ 6 สายพันธุ์ข้าวไทยระดับโลก (Thai Rice Varieties)](thai-rice-varieties.json) | 6 | 13 KB | [CSV](thai-rice-varieties_TH.csv) | [Excel](thai-rice-varieties_TH.xlsx) | [View](https://listbase.org/th/agriculture/thai-rice-varieties/) |

## Quick Start

```bash
# List all agriculture datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="agriculture") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/agriculture/thai-fruits-seasons.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/agriculture/)
