# เทคโนโลยี (Technology)

2 datasets — 74 records

> Browse at [listbase.org/th/tech/](https://listbase.org/th/tech/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [พอร์ตเครือข่ายทั่วไป](common-ports.json) | 60 | 14 KB | [View](https://listbase.org/th/tech/common-ports/) |
| [รหัสสถานะ HTTP](http-status-codes.json) | 14 | 6 KB | [View](https://listbase.org/th/tech/http-status-codes/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/tech/common-ports.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/tech/)
