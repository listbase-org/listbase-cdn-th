# การเงินและการค้า (Finance & Trade)

4 datasets — 377 records

> Browse at [listbase.org/th/finance/](https://listbase.org/th/finance/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [รหัส SWIFT/BIC — ประเทศไทย](th-swift-code.json) | 282 | 44 KB | [View](https://listbase.org/th/finance/th-swift-code/) |
| [สกุลเงินนานาชาติ 50 ประเทศ](world-currencies.json) | 50 | 15 KB | [View](https://listbase.org/th/finance/world-currencies/) |
| [ธนาคารและสถาบันการเงินในประเทศไทย (Thailand Banks)](th-banks.json) | 34 | 12 KB | [View](https://listbase.org/th/finance/th-banks/) |
| [เงื่อนไขการส่งมอบสินค้า (Incoterms 2020)](incoterms-2020.json) | 11 | 10 KB | [View](https://listbase.org/th/finance/incoterms-2020/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/finance/th-swift-code.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/finance/)
