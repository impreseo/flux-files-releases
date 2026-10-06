# Master Format Support Matrix

## Overview
Complete support matrix across all registered formats in Flux Files.

## Support Matrix Table
| Format / Ext | Category | In-App Preview | In-App Editor | Metadata | Hash Check |
|---|---|---|---|---|---|
| **.md** | Document | Yes (Live GFM) | Yes (Split) | Yes | Yes |
| **.txt** | Document | Yes | Yes | Yes | Yes |
| **.pdf** | Document | Yes (Multi-page) | No | Yes | Yes |
| **.json** | Data | Yes (Tree) | Yes (Linted) | Yes | Yes |
| **.csv, .tsv**| Data | Yes (Tabular) | Yes (Cell) | Yes | Yes |
| **.sqlite, .db**| Data | Yes (Schema) | No | Yes | Yes |
| **.png, .jpg**| Image | Yes (Zoom/Pan) | No | Yes (EXIF) | Yes |
| **.svg** | Image | Yes (Vector) | Yes (Code) | Yes | Yes |
| **.mp4, .webm**| Video | Yes (HW Accel) | No | Yes (Duration)| Yes |
| **.mp3, .flac**| Audio | Yes (Waveform) | No | Yes (ID3) | Yes |
| **.zip, .7z** | Archive | Yes (Virtual) | No | Yes (CRC32) | Yes |
| **.obj, .stl**| 3D | Yes (WebGL) | No | Yes (Polys) | Yes |
| **.ttf, .otf**| Font | Yes (Waterfall) | No | Yes (Glyphs) | Yes |
| **.ts, .py, .rs**| Code | Yes (Syntax) | Yes | Yes | Yes |
| **.exe, .dll**| Binary | Yes (PE Header)| No | Yes (PE) | Yes |

## Related
- [Universal Format Catalog](./format-catalog.md)
- [Universal Viewer Overview](../06-viewers/viewer-overview.md)
