# วิทยาศาสตร์ (Science)

4 datasets — 154 records

> Browse at [listbase.org/th/science/](https://listbase.org/th/science/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [ตารางธาตุ](periodic-table.json) | 118 | 39 KB | [View](https://listbase.org/th/science/periodic-table/) |
| [กรดอะมิโนมาตรฐาน](amino-acids.json) | 20 | 10 KB | [View](https://listbase.org/th/science/amino-acids/) |
| [กรุ๊ปเลือด ABO และ Rh](blood-types.json) | 8 | 6 KB | [View](https://listbase.org/th/science/blood-types/) |
| [ดาวเคราะห์ 8 ดวง](planets.json) | 8 | 7 KB | [View](https://listbase.org/th/science/planets/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/science/periodic-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/science/)
