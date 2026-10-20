# เวลาและปฏิทิน (Time & Calendar)

3 datasets — 36 records

> Browse at [listbase.org/th/time/](https://listbase.org/th/time/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [นักษัตร (จักรราศี)](chinese-zodiac.json) | 12 | 9 KB | [View](https://listbase.org/th/time/chinese-zodiac/) |
| [เดือนไทย](thai-months.json) | 12 | 7 KB | [View](https://listbase.org/th/time/thai-months/) |
| [ราศีสัตว์ (12 ราศี)](zodiac-signs.json) | 12 | 7 KB | [View](https://listbase.org/th/time/zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/time/chinese-zodiac.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/time/)
