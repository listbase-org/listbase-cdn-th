# คณิตศาสตร์ (Mathematics)

3 datasets — 152 records

> Browse at [listbase.org/th/math/](https://listbase.org/th/math/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ชุดข้อมูลสูตรการหาอนุพันธ์ที่พบบ่อย](math-derivative-formulas.json) | 57 | 18 KB | [CSV](math-derivative-formulas_TH.csv) | [Excel](math-derivative-formulas_TH.xlsx) | [View](https://listbase.org/th/math/math-derivative-formulas/) |
| [ชุดข้อมูลสูตรอินทิเกรตสามัญ](math-integral-formulas.json) | 56 | 17 KB | [CSV](math-integral-formulas_TH.csv) | [Excel](math-integral-formulas_TH.xlsx) | [View](https://listbase.org/th/math/math-integral-formulas/) |
| [ชุดข้อมูลตารางแปลงลาปลาซที่ครอบคลุม](math-laplace-transform.json) | 39 | 12 KB | [CSV](math-laplace-transform_TH.csv) | [Excel](math-laplace-transform_TH.xlsx) | [View](https://listbase.org/th/math/math-laplace-transform/) |

## Quick Start

```bash
# List all mathematics datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="math") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/math/math-derivative-formulas.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/math/)
