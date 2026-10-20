# วัฒนธรรมและศาสนา (Culture & Religion)

2 datasets — 140 records

> Browse at [listbase.org/th/culture/](https://listbase.org/th/culture/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [พิพิธภัณฑ์ในประเทศไทย (Museums in Thailand)](th-phiphithaphan.json) | 135 | 35 KB | [View](https://listbase.org/th/culture/th-phiphithaphan/) |
| [แหล่งมรดกโลกในประเทศไทย](th-maradok-lok-unesco.json) | 5 | 7 KB | [View](https://listbase.org/th/culture/th-maradok-lok-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/culture/th-phiphithaphan.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/culture/)
