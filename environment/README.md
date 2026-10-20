# สิ่งแวดล้อม (Environment)

1 datasets — 196 records

> Browse at [listbase.org/th/environment/](https://listbase.org/th/environment/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [โรงไฟฟ้าในประเทศไทย](th-rong-fai-fa.json) | 196 | 82 KB | [View](https://listbase.org/th/environment/th-rong-fai-fa/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/environment/th-rong-fai-fa.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/environment/)
