# เวลาและปฏิทิน (Time & Calendar)

5 datasets — 60 records

> Browse at [listbase.org/th/time/](https://listbase.org/th/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [นักษัตร (จักรราศี)](chinese-zodiac.json) | 12 | 9 KB | [CSV](chinese-zodiac_TH.csv) | [Excel](chinese-zodiac_TH.xlsx) | [View](https://listbase.org/th/time/chinese-zodiac/) |
| [เดือนไทย](thai-months.json) | 12 | 7 KB | [CSV](thai-months_TH.csv) | [Excel](thai-months_TH.xlsx) | [View](https://listbase.org/th/time/thai-months/) |
| [ชุดข้อมูลนักษัตรจีน 12 ราศี (12 สัตว์ประจำปีเกิด)](time-chinese-zodiac.json) | 12 | 15 KB | [CSV](time-chinese-zodiac_TH.csv) | [Excel](time-chinese-zodiac_TH.xlsx) | [View](https://listbase.org/th/time/time-chinese-zodiac/) |
| [ชุดข้อมูลราศีตะวันตกฉบับสมบูรณ์](time-zodiac-signs.json) | 12 | 12 KB | [CSV](time-zodiac-signs_TH.csv) | [Excel](time-zodiac-signs_TH.xlsx) | [View](https://listbase.org/th/time/time-zodiac-signs/) |
| [ราศีสัตว์ (12 ราศี)](zodiac-signs.json) | 12 | 7 KB | [CSV](zodiac-signs_TH.csv) | [Excel](zodiac-signs_TH.xlsx) | [View](https://listbase.org/th/time/zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/time/chinese-zodiac.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/time/)
