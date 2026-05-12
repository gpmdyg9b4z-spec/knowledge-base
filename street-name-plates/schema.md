# Street Name Plates Project — Schema & Vocabulary

## Project Overview
An archival photography and cartographic project documenting historic London street name plates across 19 boroughs. Published at: gpmdyg9b4z-spec.github.io/street-name-plates

- Dataset: 253+ entries in `plates_data.json`
- Location: `/Volumes/Samsung PSSD T7/StreetNamePlatesProject/`
- Map: Interactive Leaflet.js (`index.html`), self-contained with embedded data
- Instagram: @streetnameplates

---

## Dataset Schema

```json
{
  "id": "unique-identifier",
  "street_name": "Full Street Name",
  "borough": "Metropolitan Borough of [Name]",
  "plate_material": "controlled-vocabulary-term",
  "lat": 51.4950,
  "lng": -0.1753,
  "notes": "Optional cross-reference or description",
  "photo_filename": "DSC_0001.jpg"
}
```

---

## Controlled Vocabulary — `plate_material`

| Value | Description |
|-------|-------------|
| `cast-iron` | Cast iron plates, typically raised lettering |
| `ceramic` | Ceramic mosaic tile, hand-set individual tiles |
| `enamel` | Vitreous enamel on metal backing |
| `modern-metal` | Modern metal sign, post-1965 |
| `modern-plastic` | Modern plastic sign, post-1965 |
| `painted-glass` | Lettering painted on glass |
| `painted-metal` | Flat painted metal, matte finish |
| `painted-wall` | Lettering painted directly onto wall surface |
| `painted-wood` | Painted wooden board |
| `stone-carved` | Lettering carved directly into stone |

---

## Borough Naming Convention
Use **pre-1965 Metropolitan Borough names** throughout:
- Metropolitan Borough of Hampstead (not London Borough of Camden)
- Royal Borough of Kensington (not Royal Borough of Kensington and Chelsea)
- Metropolitan Borough of Chelsea (separate from Kensington pre-1965)
- Metropolitan Borough of St Marylebone (covers Marylebone and St John's Wood)

See `london/architecture-vocabulary.md` for full borough name mapping.

---

## Duplicate Policy
- **Same street + same material** = skip (duplicate)
- **Same street + different material or era** = include with cross-reference in `notes` field
- Example: Fitzjohn's Avenue has both ceramic and enamel plates → both entries included, each noting the other

---

## Sign Identification Rules
*(See also `getty/metadata-rules.md` for photography-specific guidance)*

### Vitreous Enamel
- Smooth, glossy surface
- Royal Borough of Kensington: white ground, red blackletter, black serif, red postcode, green frame
- Other boroughs: typically dark navy/green ground with white or cream lettering
- Corner fixings visible (screws or rivets)
- Does not chip — crazes in circular patterns if damaged

### Ceramic Mosaic Tile
- Individual tiles visible on close inspection
- Grout lines between tiles
- Slightly uneven surface
- Most common in former Metropolitan Borough of Hampstead (NW3)
- Typically dark ground (navy or black) with white lettering

### Cast Iron
- Heavy metal plate
- Raised or recessed lettering
- Often painted (but substrate is cast iron)
- Pre-dates enamel signs in many boroughs

### Painted Wall
- Street name painted directly onto brick, stucco or stone
- No separate plate
- Often found on corner buildings

### Stone Carved
- Name cut into stone lintel or facade
- Often 18th or early 19th century
- No plate — integrated into the building fabric

---

## Photography Notes
- Shoot: straight on, parallel to the sign
- Avoid reflections on enamel — use polarising filter or shade
- Capture full plate including frame and fixings
- Also capture context shot showing position on building
- RAW format, process to reveal material texture
