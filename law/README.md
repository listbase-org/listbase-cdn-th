# กฎหมาย (Law)

3 datasets — 47 records

> Browse at [listbase.org/th/law/](https://listbase.org/th/law/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [รัฐธรรมนูญแห่งราชอาณาจักรไทย](thai-constitutions.json) | 20 | 12 KB | [View](https://listbase.org/th/law/thai-constitutions/) |
| [วันหยุดราชการไทย](legal-holidays.json) | 17 | 8 KB | [View](https://listbase.org/th/law/legal-holidays/) |
| [ค่าปรับจราจร](traffic-fines.json) | 10 | 5 KB | [View](https://listbase.org/th/law/traffic-fines/) |

## Quick Start

```bash
# List all law datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="law") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/law/thai-constitutions.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/law/)
