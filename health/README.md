# สุขภาพ (Health)

1 datasets — 18 records

> Browse at [listbase.org/th/health/](https://listbase.org/th/health/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [วิตามินและแร่ธาตุจำเป็น](vitamins.json) | 18 | 14 KB | [View](https://listbase.org/th/health/vitamins/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/health/vitamins.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/health/)
