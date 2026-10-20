# ListBase CDN — ไทย (th)

Open dataset collection for **ไทย** (Thai).
726 datasets across 21 categories with 270,890 total records.

> Browse and download at [https://listbase.org/th/](https://listbase.org/th/)

## Categories

| Category | Datasets |
|----------|----------|
| [เกษตรกรรม (Agriculture)](agriculture/) | 3 |
| [ธุรกิจ (Business)](business/) | 1 |
| [วัฒนธรรมและศาสนา (Culture & Religion)](culture/) | 2 |
| [การศึกษา (Education)](education/) | 5 |
| [สิ่งแวดล้อม (Environment)](environment/) | 1 |
| [การเงินและการค้า (Finance & Trade)](finance/) | 16 |
| [อาหารและโภชนาการ (Food & Nutrition)](food/) | 3 |
| [ภูมิศาสตร์ (Geography)](geography/) | 179 |
| [สุขภาพ (Health)](health/) | 1 |
| [ประวัติศาสตร์ (History)](history/) | 2 |
| [ภาษา (Language)](language/) | 10 |
| [กฎหมาย (Law)](law/) | 3 |
| [คณิตศาสตร์ (Mathematics)](math/) | 3 |
| [ดนตรี (Music)](music/) | 3 |
| [การเมือง (Politics)](politics/) | 8 |
| [อ้างอิง (Reference)](reference/) | 436 |
| [วิทยาศาสตร์ (Science)](science/) | 17 |
| [เทคโนโลยี (Technology)](tech/) | 15 |
| [เวลาและปฏิทิน (Time & Calendar)](time/) | 5 |
| [คมนาคม (Transport)](transport/) | 7 |
| [หน่วยวัด (Units & Measurements)](units/) | 6 |

## Usage

### Browse on the web
Visit [listbase.org/th/](https://listbase.org/th/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.th.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.th.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.th.listbase.org/geography/th-central-provinces_TH.xlsx
curl -O https://cdn.th.listbase.org/geography/th-central-provinces_TH.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.th.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.th.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_TH.csv   # CSV download
│   └── {dataset}_TH.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
