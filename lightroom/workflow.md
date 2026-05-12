# Lightroom Classic — Workflow & Settings

## Storage Setup
- **Internal SSD:** 121GB total — keep below 80% to avoid purgeable space issues
- **Samsung PSSD T7 (4TB):** Primary working drive
  - Lightroom catalog
  - Lightroom previews
  - ACR cache
  - All Getty Submissions folders
- **Seagate Portable 4TB:**
  - Time Machine partition (2TB)
  - Samsung Backup partition (2TB)
- **Carbon Copy Cloner:** Cloning T7 to Samsung Backup partition

### If internal SSD fills up
```bash
sudo purge  # Clear purgeable space
# Then restart Mac
# Purgeable space in /private/var/folders/zz/ clears on restart
```

---

## Export Presets

### Getty Metadata Preview
*(For metadata generation app — small files)*
- Format: JPEG
- Quality: 60
- Resize to Fit: Long Edge, 1500px
- Don't Enlarge: checked
- Colour Space: sRGB
- No sharpening
- No watermark
- Export to: subfolder named `[folder] Metadata` inside Getty Submissions folder

### Getty Full Resolution
*(For DeepMeta submission)*
- Format: JPEG
- Quality: 100 (or per Getty current spec)
- No resize
- Colour Space: sRGB
- Sharpen For: Screen, Standard (optional)
- Metadata: All Metadata, Remove Person Info checked
- Export to: `[T7]/Getty Submissions/[folder name]/`

---

## LR/Transporter

### CSV Format Requirements
- Field separator: comma
- Quoting: QUOTE_MINIMAL
- Keywords: **semicolon-separated** (Transporter rejects comma-separated)
- Internal double-quotes in captions: replace with single quotes
- Caption newlines: collapse to single space

### CSV Headers (LR/Transporter format)
```
Filename,Title,Caption,Keywords
```

### Pre-import keyword requirement
All unique keywords must be imported into LR's keyword catalogue before running Transporter, otherwise keywords are silently dropped:
- Metadata → Import Keywords
- Import a text file with one keyword per line

### After Transporter import
- Check metadata panel: Title, Caption, Keywords should all be populated
- If keywords missing: check they were pre-imported into catalogue

---

## Metadata Read-Back from Files
After ExifTool embeds metadata into exported JPEGs:
1. In LR grid, select the images
2. Right-click → Metadata → Read Metadata From Files
3. LR reads IPTC from file and updates catalog

*Note: Only applies to files already imported into LR catalog.*

---

## Culling Workflow
- Cull on shoot day to prevent preview cache bloat
- Use P (pick) / X (reject) flags
- Delete rejected immediately: Photo → Delete Rejected Photos
- This keeps preview cache manageable and internal SSD clear

---

## Catalog & Cache Locations
*(All moved to T7 to save internal SSD space)*
- Catalog: `/Volumes/Samsung PSSD T7/Lightroom/[catalog name].lrcat`
- Previews: `/Volumes/Samsung PSSD T7/Lightroom/[catalog name] Previews.lrdata`
- ACR Cache: `/Volumes/Samsung PSSD T7/Lightroom/Camera Raw Cache`

To move ACR cache: LR Preferences → File Handling → Camera Raw Cache Settings → Choose location on T7
