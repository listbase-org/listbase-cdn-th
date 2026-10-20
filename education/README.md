# การศึกษา (Education)

5 datasets — 161 records

> Browse at [listbase.org/th/education/](https://listbase.org/th/education/)

## Datasets

| Name | Records | Size | Preview |
|------|---------|------|---------|
| [ประเทศไทย — มหาวิทยาลัยและสถาบันอุดมศึกษา](th-mahawitthayalai.json) | 67 | 23 KB | [View](https://listbase.org/th/education/th-mahawitthayalai/) |
| [มหาวิทยาลัยราชภัฏ](rajabhat-universities.json) | 38 | 14 KB | [View](https://listbase.org/th/education/rajabhat-universities/) |
| [มหาวิทยาลัยรัฐในประเทศไทย](public-universities.json) | 32 | 15 KB | [View](https://listbase.org/th/education/public-universities/) |
| [Military and Police Educational Institutions in Thailand](military-academies.json) | 15 | 10 KB | [View](https://listbase.org/th/education/military-academies/) |
| [มหาวิทยาลัยเทคโนโลยีราชมงคล](rajamangala-universities.json) | 9 | 7 KB | [View](https://listbase.org/th/education/rajamangala-universities/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/education/th-mahawitthayalai.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/education/)
