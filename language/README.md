# ภาษา (Language)

5 datasets — 308 records

> Browse at [listbase.org/th/language/](https://listbase.org/th/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ฮิรางะนะ](hiragana.json) | 96 | 21 KB | [CSV](hiragana_TH.csv) | [Excel](hiragana_TH.xlsx) | [View](https://listbase.org/th/language/hiragana/) |
| [กะตะกะนะ](katakana.json) | 96 | 22 KB | [CSV](katakana_TH.csv) | [Excel](katakana_TH.xlsx) | [View](https://listbase.org/th/language/katakana/) |
| [พยัญชนะไทย 44 ตัว](thai-consonants.json) | 44 | 12 KB | [CSV](thai-consonants_TH.csv) | [Excel](thai-consonants_TH.xlsx) | [View](https://listbase.org/th/language/thai-consonants/) |
| [ฮังกุลเกาหลี](korean-hangul.json) | 40 | 10 KB | [CSV](korean-hangul_TH.csv) | [Excel](korean-hangul_TH.xlsx) | [View](https://listbase.org/th/language/korean-hangul/) |
| [สระภาษาไทย 21 รูป 32 เสียง](thai-vowels.json) | 32 | 9 KB | [CSV](thai-vowels_TH.csv) | [Excel](thai-vowels_TH.xlsx) | [View](https://listbase.org/th/language/thai-vowels/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/language/hiragana.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/language/)
