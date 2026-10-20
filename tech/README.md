# เทคโนโลยี (Technology)

15 datasets — 999 records

> Browse at [listbase.org/th/tech/](https://listbase.org/th/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ชุดข้อมูลรหัสภาษา ISO 639 และชื่อพื้นเมือง](tech-language-codes.json) | 183 | 29 KB | [CSV](tech-language-codes_TH.csv) | [Excel](tech-language-codes_TH.xlsx) | [View](https://listbase.org/th/tech/tech-language-codes/) |
| [ชุดข้อมูลตารางอักขระ ASCII และรหัสอ้างอิงที่สมบูรณ์](tech-ascii-table.json) | 128 | 35 KB | [CSV](tech-ascii-table_TH.csv) | [Excel](tech-ascii-table_TH.xlsx) | [View](https://listbase.org/th/tech/tech-ascii-table/) |
| [ชุดข้อมูลคีย์ลัดสากลสำหรับ Windows และ macOS](tech-keyboard-shortcuts.json) | 77 | 21 KB | [CSV](tech-keyboard-shortcuts_TH.csv) | [Excel](tech-keyboard-shortcuts_TH.xlsx) | [View](https://listbase.org/th/tech/tech-keyboard-shortcuts/) |
| [ชุดข้อมูล HTML Character Entities และสัญลักษณ์พิเศษ](tech-html-entities.json) | 75 | 24 KB | [CSV](tech-html-entities_TH.csv) | [Excel](tech-html-entities_TH.xlsx) | [View](https://listbase.org/th/tech/tech-html-entities/) |
| [ชุดข้อมูลหมายเลขพอร์ตเครือข่ายและบริการทั่วไป](tech-port-numbers.json) | 73 | 21 KB | [CSV](tech-port-numbers_TH.csv) | [Excel](tech-port-numbers_TH.xlsx) | [View](https://listbase.org/th/tech/tech-port-numbers/) |
| [ชุดข้อมูลประเภท MIME และนามสกุลไฟล์ทั่วไป](tech-mime-types.json) | 70 | 17 KB | [CSV](tech-mime-types_TH.csv) | [Excel](tech-mime-types_TH.xlsx) | [View](https://listbase.org/th/tech/tech-mime-types/) |
| [ชุดข้อมูลสัญลักษณ์ Unicode และ HTML Entities ทั่วไป](tech-unicode-symbols.json) | 70 | 19 KB | [CSV](tech-unicode-symbols_TH.csv) | [Excel](tech-unicode-symbols_TH.xlsx) | [View](https://listbase.org/th/tech/tech-unicode-symbols/) |
| [HTTP Status Codes Dataset](tech-http-codes.json) | 62 | 25 KB | [CSV](tech-http-codes_TH.csv) | [Excel](tech-http-codes_TH.xlsx) | [View](https://listbase.org/th/tech/tech-http-codes/) |
| [พอร์ตเครือข่ายทั่วไป](common-ports.json) | 60 | 14 KB | [CSV](common-ports_TH.csv) | [Excel](common-ports_TH.xlsx) | [View](https://listbase.org/th/tech/common-ports/) |
| [ชุดข้อมูลรูปแบบ Regular Expression ที่จำเป็น](tech-regex-patterns.json) | 45 | 17 KB | [CSV](tech-regex-patterns_TH.csv) | [Excel](tech-regex-patterns_TH.xlsx) | [View](https://listbase.org/th/tech/tech-regex-patterns/) |
| [ชุดข้อมูลขนาดและสัดส่วนรูปภาพโซเชียลมีเดีย](tech-social-media-sizes.json) | 42 | 16 KB | [CSV](tech-social-media-sizes_TH.csv) | [Excel](tech-social-media-sizes_TH.xlsx) | [View](https://listbase.org/th/tech/tech-social-media-sizes/) |
| [Screen Resolutions & Aspect Ratios Dataset](tech-screen-resolutions.json) | 35 | 11 KB | [CSV](tech-screen-resolutions_TH.csv) | [Excel](tech-screen-resolutions_TH.xlsx) | [View](https://listbase.org/th/tech/tech-screen-resolutions/) |
| [ชุดข้อมูลขนาดกระดาษและพิกเซล](tech-paper-sizes.json) | 33 | 16 KB | [CSV](tech-paper-sizes_TH.csv) | [Excel](tech-paper-sizes_TH.xlsx) | [View](https://listbase.org/th/tech/tech-paper-sizes/) |
| [ชุดข้อมูลตารางความจริงลอจิกเกต](tech-logic-gates.json) | 32 | 13 KB | [CSV](tech-logic-gates_TH.csv) | [Excel](tech-logic-gates_TH.xlsx) | [View](https://listbase.org/th/tech/tech-logic-gates/) |
| [รหัสสถานะ HTTP](http-status-codes.json) | 14 | 6 KB | [CSV](http-status-codes_TH.csv) | [Excel](http-status-codes_TH.xlsx) | [View](https://listbase.org/th/tech/http-status-codes/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/tech/tech-language-codes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/tech/)
