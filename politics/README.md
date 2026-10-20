# การเมือง (Politics)

8 datasets — 362 records

> Browse at [listbase.org/th/politics/](https://listbase.org/th/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [พรรคการเมืองไทย (Thai Political Parties — 2019)](th-political-parties.json) | 104 | 190 KB | [CSV](th-political-parties_TH.csv) | [Excel](th-political-parties_TH.xlsx) | [View](https://listbase.org/th/politics/th-political-parties/) |
| [พรรคการเมืองไทยที่ยังคงอยู่ (Active Thai Political Parties — 2019)](th-political-parties-active.json) | 103 | 187 KB | [CSV](th-political-parties-active_TH.csv) | [Excel](th-political-parties-active_TH.xlsx) | [View](https://listbase.org/th/politics/th-political-parties-active/) |
| [แคนดิเดตนายกรัฐมนตรีของแต่ละพรรค (PM Candidates by Thai Political Party — 2019)](th-political-party-pm-candidates.json) | 69 | 39 KB | [CSV](th-political-party-pm-candidates_TH.csv) | [Excel](th-political-party-pm-candidates_TH.xlsx) | [View](https://listbase.org/th/politics/th-political-party-pm-candidates/) |
| [นายกรัฐมนตรีของไทย](prime-ministers.json) | 31 | 8 KB | [CSV](prime-ministers_TH.csv) | [Excel](prime-ministers_TH.xlsx) | [View](https://listbase.org/th/politics/prime-ministers/) |
| [กระทรวงในประเทศไทย](ministries.json) | 20 | 6 KB | [CSV](ministries_TH.csv) | [Excel](ministries_TH.xlsx) | [View](https://listbase.org/th/politics/ministries/) |
| [พรรคการเมืองไทย เลือกตั้ง 2569 (Thai Political Parties — 2026 Election)](th-parties-2569.json) | 18 | 21 KB | [CSV](th-parties-2569_TH.csv) | [Excel](th-parties-2569_TH.xlsx) | [View](https://listbase.org/th/politics/th-parties-2569/) |
| [ศาลในประเทศไทย](courts.json) | 12 | 6 KB | [CSV](courts_TH.csv) | [Excel](courts_TH.xlsx) | [View](https://listbase.org/th/politics/courts/) |
| [องค์กรอิสระตามรัฐธรรมนูญ](independent-organizations.json) | 5 | 4 KB | [CSV](independent-organizations_TH.csv) | [Excel](independent-organizations_TH.xlsx) | [View](https://listbase.org/th/politics/independent-organizations/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/politics/th-political-parties.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/politics/)
