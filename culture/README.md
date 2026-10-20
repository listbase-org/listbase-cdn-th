# วัฒนธรรมและศาสนา (Culture & Religion)

2 datasets — 140 records

> Browse at [listbase.org/th/culture/](https://listbase.org/th/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [พิพิธภัณฑ์ในประเทศไทย (Museums in Thailand)](th-phiphithaphan.json) | 135 | 35 KB | [CSV](th-phiphithaphan_TH.csv) | [Excel](th-phiphithaphan_TH.xlsx) | [View](https://listbase.org/th/culture/th-phiphithaphan/) |
| [แหล่งมรดกโลกในประเทศไทย](th-maradok-lok-unesco.json) | 5 | 7 KB | [CSV](th-maradok-lok-unesco_TH.csv) | [Excel](th-maradok-lok-unesco_TH.xlsx) | [View](https://listbase.org/th/culture/th-maradok-lok-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/culture/th-phiphithaphan.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/culture/)
