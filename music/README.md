# ดนตรี (Music)

3 datasets — 200 records

> Browse at [listbase.org/th/music/](https://listbase.org/th/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ชุดข้อมูลอ้างอิงตารางคอร์ดเปียโนที่จำเป็น](music-piano-chords.json) | 84 | 27 KB | [CSV](music-piano-chords_TH.csv) | [Excel](music-piano-chords_TH.xlsx) | [View](https://listbase.org/th/music/music-piano-chords/) |
| [ชุดข้อมูลคอร์ดกีตาร์ฉบับสมบูรณ์](music-guitar-chords.json) | 78 | 30 KB | [CSV](music-guitar-chords_TH.csv) | [Excel](music-guitar-chords_TH.xlsx) | [View](https://listbase.org/th/music/music-guitar-chords/) |
| [โน้ตดนตรี ความถี่ และช่วงโน้ต](music-notes.json) | 38 | 14 KB | [CSV](music-notes_TH.csv) | [Excel](music-notes_TH.xlsx) | [View](https://listbase.org/th/music/music-notes/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/music/music-piano-chords.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/music/)
