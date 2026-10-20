# คมนาคม (Transport)

7 datasets — 648 records

> Browse at [listbase.org/th/transport/](https://listbase.org/th/transport/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [รหัสสถานที่ UN/LOCODE — ประเทศไทย (ท่าเรือ สนามบิน เทอร์มินัล)](th-unlocode.json) | 203 | 134 KB | [CSV](th-unlocode_TH.csv) | [Excel](th-unlocode_TH.xlsx) | [View](https://listbase.org/th/transport/th-unlocode/) |
| [สถานีรถไฟฟ้ากรุงเทพ (BTS/MRT/แอร์พอร์ต เรล ลิงก์)](transport-bangkok-train-stations.json) | 125 | 43 KB | [CSV](transport-bangkok-train-stations_TH.csv) | [Excel](transport-bangkok-train-stations_TH.xlsx) | [View](https://listbase.org/th/transport/transport-bangkok-train-stations/) |
| [รายชื่อถนนในจังหวัดนนทบุรี](transport-nonthaburi-roads.json) | 118 | 45 KB | [CSV](transport-nonthaburi-roads_TH.csv) | [Excel](transport-nonthaburi-roads_TH.xlsx) | [View](https://listbase.org/th/transport/transport-nonthaburi-roads/) |
| [รายชื่อสถานีรถไฟ สายตะวันออก](transport-thai-eastern-railway-stations.json) | 84 | 52 KB | [CSV](transport-thai-eastern-railway-stations_TH.csv) | [Excel](transport-thai-eastern-railway-stations_TH.xlsx) | [View](https://listbase.org/th/transport/transport-thai-eastern-railway-stations/) |
| [ท่าอากาศยานในประเทศไทย](th-airports.json) | 44 | 23 KB | [CSV](th-airports_TH.csv) | [Excel](th-airports_TH.xlsx) | [View](https://listbase.org/th/transport/th-airports/) |
| [รายชื่อทางแยกในจังหวัดนนทบุรี](transport-nonthaburi-intersections.json) | 40 | 21 KB | [CSV](transport-nonthaburi-intersections_TH.csv) | [Excel](transport-nonthaburi-intersections_TH.xlsx) | [View](https://listbase.org/th/transport/transport-nonthaburi-intersections/) |
| [รายชื่อท่าอากาศยานในประเทศไทย](transport-thai-airports.json) | 34 | 15 KB | [CSV](transport-thai-airports_TH.csv) | [Excel](transport-thai-airports_TH.xlsx) | [View](https://listbase.org/th/transport/transport-thai-airports/) |

## Quick Start

```bash
# List all transport datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="transport") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/transport/th-unlocode.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/transport/)
