# ภาษา (Language)

10 datasets — 901 records

> Browse at [listbase.org/th/language/](https://listbase.org/th/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ตารางพยางค์พินอินจีนฉบับสมบูรณ์พร้อมคู่มือการออกเสียง](lang-pinyin-table.json) | 408 | 112 KB | [CSV](lang-pinyin-table_TH.csv) | [Excel](lang-pinyin-table_TH.xlsx) | [View](https://listbase.org/th/language/lang-pinyin-table/) |
| [ฮิรางะนะ](hiragana.json) | 96 | 21 KB | [CSV](hiragana_TH.csv) | [Excel](hiragana_TH.xlsx) | [View](https://listbase.org/th/language/hiragana/) |
| [กะตะกะนะ](katakana.json) | 96 | 22 KB | [CSV](katakana_TH.csv) | [Excel](katakana_TH.xlsx) | [View](https://listbase.org/th/language/katakana/) |
| [ชุดข้อมูลตารางการจำแนกคำสรรพนามภาษาอังกฤษ](lang-english-pronouns.json) | 69 | 29 KB | [CSV](lang-english-pronouns_TH.csv) | [Excel](lang-english-pronouns_TH.xlsx) | [View](https://listbase.org/th/language/lang-english-pronouns/) |
| [ชุดข้อมูลตารางฮิรางานะญี่ปุ่นและการจับคู่โรมาจิ](lang-hiragana-table.json) | 46 | 13 KB | [CSV](lang-hiragana-table_TH.csv) | [Excel](lang-hiragana-table_TH.xlsx) | [View](https://listbase.org/th/language/lang-hiragana-table/) |
| [ชุดข้อมูลตารางตัวอักษรคะตะคะนะญี่ปุ่นฉบับสมบูรณ์](lang-katakana-table.json) | 46 | 13 KB | [CSV](lang-katakana-table_TH.csv) | [Excel](lang-katakana-table_TH.xlsx) | [View](https://listbase.org/th/language/lang-katakana-table/) |
| [พยัญชนะไทย 44 ตัว](thai-consonants.json) | 44 | 12 KB | [CSV](thai-consonants_TH.csv) | [Excel](thai-consonants_TH.xlsx) | [View](https://listbase.org/th/language/thai-consonants/) |
| [ฮังกุลเกาหลี](korean-hangul.json) | 40 | 10 KB | [CSV](korean-hangul_TH.csv) | [Excel](korean-hangul_TH.xlsx) | [View](https://listbase.org/th/language/korean-hangul/) |
| [สระภาษาไทย 21 รูป 32 เสียง](thai-vowels.json) | 32 | 9 KB | [CSV](thai-vowels_TH.csv) | [Excel](thai-vowels_TH.xlsx) | [View](https://listbase.org/th/language/thai-vowels/) |
| [ชุดข้อมูลอักษรกรีกพร้อมรายละเอียด](lang-greek-alphabet.json) | 24 | 13 KB | [CSV](lang-greek-alphabet_TH.csv) | [Excel](lang-greek-alphabet_TH.xlsx) | [View](https://listbase.org/th/language/lang-greek-alphabet/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/language/lang-pinyin-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/language/)
