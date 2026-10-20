# วิทยาศาสตร์ (Science)

17 datasets — 1,269 records

> Browse at [listbase.org/th/science/](https://listbase.org/th/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [รายชื่อประเทศตามอัตราการเสียชีวิต](science-countries-death-rate.json) | 224 | 44 KB | [CSV](science-countries-death-rate_TH.csv) | [Excel](science-countries-death-rate_TH.xlsx) | [View](https://listbase.org/th/science/science-countries-death-rate/) |
| [รายชื่อประเทศเรียงตามอัตราภาวะการตายของทารก](science-country-infant-mortality-rate.json) | 223 | 27 KB | [CSV](science-country-infant-mortality-rate_TH.csv) | [Excel](science-country-infant-mortality-rate_TH.xlsx) | [View](https://listbase.org/th/science/science-country-infant-mortality-rate/) |
| [รายชื่อประเทศตามจำนวนผู้ป่วยโรคเอดส์](science-countries-by-aids-patients.json) | 164 | 27 KB | [CSV](science-countries-by-aids-patients_TH.csv) | [Excel](science-countries-by-aids-patients_TH.xlsx) | [View](https://listbase.org/th/science/science-countries-by-aids-patients/) |
| [ตารางธาตุ](periodic-table.json) | 118 | 39 KB | [CSV](periodic-table_TH.csv) | [Excel](periodic-table_TH.xlsx) | [View](https://listbase.org/th/science/periodic-table/) |
| [ชุดข้อมูลตารางธาตุเคมีที่สมบูรณ์](science-periodic-table.json) | 118 | 45 KB | [CSV](science-periodic-table_TH.csv) | [Excel](science-periodic-table_TH.xlsx) | [View](https://listbase.org/th/science/science-periodic-table/) |
| [รายชื่อโรงพยาบาลรัฐในประเทศไทย](science-thai-government-hospitals.json) | 99 | 31 KB | [CSV](science-thai-government-hospitals_TH.csv) | [Excel](science-thai-government-hospitals_TH.xlsx) | [View](https://listbase.org/th/science/science-thai-government-hospitals/) |
| [ชุดข้อมูลตารางโคดอน RNA ฉบับสมบูรณ์](science-codon-table.json) | 64 | 17 KB | [CSV](science-codon-table_TH.csv) | [Excel](science-codon-table_TH.xlsx) | [View](https://listbase.org/th/science/science-codon-table/) |
| [ชุดข้อมูลตารางค่าอิเล็กโทรเนกาทิวิตี (Pauling Scale)](science-electronegativity.json) | 62 | 23 KB | [CSV](science-electronegativity_TH.csv) | [Excel](science-electronegativity_TH.xlsx) | [View](https://listbase.org/th/science/science-electronegativity/) |
| [ชุดข้อมูลระบบหน่วยวัดระหว่างประเทศ (SI Units)](science-si-units.json) | 53 | 17 KB | [CSV](science-si-units_TH.csv) | [Excel](science-si-units_TH.xlsx) | [View](https://listbase.org/th/science/science-si-units/) |
| [ชุดข้อมูลอ้างอิงมาตราส่วน pH และคุณสมบัติทางเคมี](science-ph-scale.json) | 33 | 12 KB | [CSV](science-ph-scale_TH.csv) | [Excel](science-ph-scale_TH.xlsx) | [View](https://listbase.org/th/science/science-ph-scale/) |
| [ชุดข้อมูลตารางกฎการละลายที่ครอบคลุม](science-solubility-rules.json) | 31 | 18 KB | [CSV](science-solubility-rules_TH.csv) | [Excel](science-solubility-rules_TH.xlsx) | [View](https://listbase.org/th/science/science-solubility-rules/) |
| [ชุดข้อมูลคุณสมบัติกรดอะมิโนที่ครอบคลุม](science-amino-acids.json) | 22 | 13 KB | [CSV](science-amino-acids_TH.csv) | [Excel](science-amino-acids_TH.xlsx) | [View](https://listbase.org/th/science/science-amino-acids/) |
| [กรดอะมิโนมาตรฐาน](amino-acids.json) | 20 | 10 KB | [CSV](amino-acids_TH.csv) | [Excel](amino-acids_TH.xlsx) | [View](https://listbase.org/th/science/amino-acids/) |
| [ชุดข้อมูลแผนภูมิความเข้ากันได้ของกรุ๊ปเลือดที่ครอบคลุม](science-blood-types.json) | 11 | 9 KB | [CSV](science-blood-types_TH.csv) | [Excel](science-blood-types_TH.xlsx) | [View](https://listbase.org/th/science/science-blood-types/) |
| [ชุดข้อมูลดาวเคราะห์และวัตถุท้องฟ้าในระบบสุริยะ](science-planet-data.json) | 11 | 13 KB | [CSV](science-planet-data_TH.csv) | [Excel](science-planet-data_TH.xlsx) | [View](https://listbase.org/th/science/science-planet-data/) |
| [กรุ๊ปเลือด ABO และ Rh](blood-types.json) | 8 | 6 KB | [CSV](blood-types_TH.csv) | [Excel](blood-types_TH.xlsx) | [View](https://listbase.org/th/science/blood-types/) |
| [ดาวเคราะห์ 8 ดวง](planets.json) | 8 | 7 KB | [CSV](planets_TH.csv) | [Excel](planets_TH.xlsx) | [View](https://listbase.org/th/science/planets/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/science/science-countries-death-rate.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/science/)
