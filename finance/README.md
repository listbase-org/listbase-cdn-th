# การเงินและการค้า (Finance & Trade)

16 datasets — 1,940 records

> Browse at [listbase.org/th/finance/](https://listbase.org/th/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [บริษัทจดทะเบียนในตลาด SET](finance-set-stocks.json) | 703 | 266 KB | [CSV](finance-set-stocks_TH.csv) | [Excel](finance-set-stocks_TH.xlsx) | [View](https://listbase.org/th/finance/finance-set-stocks/) |
| [รหัส SWIFT/BIC — ประเทศไทย](th-swift-code.json) | 282 | 44 KB | [CSV](th-swift-code_TH.csv) | [Excel](th-swift-code_TH.xlsx) | [View](https://listbase.org/th/finance/th-swift-code/) |
| [บริษัทจดทะเบียนในตลาด mai](finance-mai-stocks.json) | 229 | 74 KB | [CSV](finance-mai-stocks_TH.csv) | [Excel](finance-mai-stocks_TH.xlsx) | [View](https://listbase.org/th/finance/finance-mai-stocks/) |
| [ชุดข้อมูลรหัสประเทศและรหัสบาร์โค้ด GS1](finance-gs1-codes.json) | 126 | 25 KB | [CSV](finance-gs1-codes_TH.csv) | [Excel](finance-gs1-codes_TH.xlsx) | [View](https://listbase.org/th/finance/finance-gs1-codes/) |
| [รายชื่อหุ้น SET100 ในตลาดหลักทรัพย์แห่งประเทศไทย](finance-set100.json) | 100 | 50 KB | [CSV](finance-set100_TH.csv) | [Excel](finance-set100_TH.xlsx) | [View](https://listbase.org/th/finance/finance-set100/) |
| [ชุดข้อมูลบท HS Code (Harmonized System)](finance-hs-codes.json) | 98 | 34 KB | [CSV](finance-hs-codes_TH.csv) | [Excel](finance-hs-codes_TH.xlsx) | [View](https://listbase.org/th/finance/finance-hs-codes/) |
| [รายชื่อประเทศเรียงตามจำนวนเศรษฐีพันล้าน](finance-countries-by-billionaires.json) | 75 | 24 KB | [CSV](finance-countries-by-billionaires_TH.csv) | [Excel](finance-countries-by-billionaires_TH.xlsx) | [View](https://listbase.org/th/finance/finance-countries-by-billionaires/) |
| [ชุดข้อมูลอัตรา VAT/GST โดยประเทศที่ครอบคลุม](finance-vat-rates.json) | 75 | 23 KB | [CSV](finance-vat-rates_TH.csv) | [Excel](finance-vat-rates_TH.xlsx) | [View](https://listbase.org/th/finance/finance-vat-rates/) |
| [กองทุนรวมอสังหาริมทรัพย์และ REITs ไทย](finance-reit-thailand.json) | 64 | 35 KB | [CSV](finance-reit-thailand_TH.csv) | [Excel](finance-reit-thailand_TH.xlsx) | [View](https://listbase.org/th/finance/finance-reit-thailand/) |
| [รายชื่อหุ้น SET50 ในตลาดหลักทรัพย์แห่งประเทศไทย](finance-set50.json) | 50 | 27 KB | [CSV](finance-set50_TH.csv) | [Excel](finance-set50_TH.xlsx) | [View](https://listbase.org/th/finance/finance-set50/) |
| [สกุลเงินนานาชาติ 50 ประเทศ](world-currencies.json) | 50 | 15 KB | [CSV](world-currencies_TH.csv) | [Excel](world-currencies_TH.xlsx) | [View](https://listbase.org/th/finance/world-currencies/) |
| [ธนาคารและสถาบันการเงินในประเทศไทย (Thailand Banks)](th-banks.json) | 34 | 12 KB | [CSV](th-banks_TH.csv) | [Excel](th-banks_TH.xlsx) | [View](https://listbase.org/th/finance/th-banks/) |
| [รายชื่อธนาคารพาณิชย์ในประเทศไทย](finance-thai-banks.json) | 18 | 10 KB | [CSV](finance-thai-banks_TH.csv) | [Excel](finance-thai-banks_TH.xlsx) | [View](https://listbase.org/th/finance/finance-thai-banks/) |
| [ชุดข้อมูลรหัสคอนเทนเนอร์และข้อมูลจำเพาะ ISO 6346](finance-container-codes.json) | 14 | 11 KB | [CSV](finance-container-codes_TH.csv) | [Excel](finance-container-codes_TH.xlsx) | [View](https://listbase.org/th/finance/finance-container-codes/) |
| [ชุดข้อมูลกฎและคำจำกัดความ Incoterms 2020](finance-incoterms.json) | 11 | 13 KB | [CSV](finance-incoterms_TH.csv) | [Excel](finance-incoterms_TH.xlsx) | [View](https://listbase.org/th/finance/finance-incoterms/) |
| [เงื่อนไขการส่งมอบสินค้า (Incoterms 2020)](incoterms-2020.json) | 11 | 10 KB | [CSV](incoterms-2020_TH.csv) | [Excel](incoterms-2020_TH.xlsx) | [View](https://listbase.org/th/finance/incoterms-2020/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/finance/finance-set-stocks.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/finance/)
