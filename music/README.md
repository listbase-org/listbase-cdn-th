# ดนตรี (Music)

1 datasets — 38 records

> Browse at [listbase.org/th/music/](https://listbase.org/th/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [โน้ตดนตรี ความถี่ และช่วงโน้ต](music-notes.json) | 38 | 14 KB | [CSV](music-notes_TH.csv) | [Excel](music-notes_TH.xlsx) | [View](https://listbase.org/th/music/music-notes/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.th.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.th.listbase.org/music/music-notes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/th/music/)
