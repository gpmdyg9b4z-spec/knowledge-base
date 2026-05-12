# Sergio Amiti — Getty Images Portfolio: Session Start Document

## Who I Am
London-based editorial stock photographer and Getty Images contributor. Core workflow: shoot → cull in Lightroom Classic → metadata via Getty Metadata Studio artifact → CSV export via LR/Transporter → DeepMeta → Getty ESP portal. Also contribute to the Street Name Plates Project (gpmdyg9b4z-spec.github.io/street-name-plates).

---

## Portfolio Overview

**Strengths by subject:**
- London architecture, street scenes, and urban detail (Chelsea, Brixton, Hackney/Dalston, City of London, Kensington)
- International food — Sichuan, Middle Eastern, West African, Indonesian, Central Asian, Levantine, British market produce
- National flags — large collection including Kuwait, Qatar, Saudi Arabia, Sweden, Illinois, Belgium/Flemish
- Travel — Beijing, Chicago, New York, Bordeaux, Rotterdam, Delft, Kyoto, Bhaktapur, Lombok/Sumba, Gambia, Bangladesh, Kyrgyzstan
- Botany/horticulture — Chelsea Physic Garden, Kew, herb gardens, carnivorous plants
- Street name signs — London and international, linked to Street Name Plates Project

**Notable placements to date:**
- National Geographic Life in Color coffee table book (Beijing Opera House double-page spread)
- National Geographic online (Philly cheesesteak)
- Financial Times Globetrotter (Hudson River Greenway)
- Architectural Digest (Ez-Zitouna Mosque, Tunis)
- Condé Nast Traveler, Elle Italy, Cambridge Dictionary (historical)

**Top earning assets observed:**

| Asset ID | Subject | $ | DL | RPD |
|---|---|---|---|---|
| 1146268182 | Rhubarb at market | $145.24 | 67 | $2.17 |
| 1413277628 | Illinois state flag Navy Pier | $117.18 | 25 | $4.69 |
| 2088386179 | Kuwait flag | $17.67 | 42 | $0.42 |

---

## Established Caption Format

**Structure:** Two paragraphs, present tense, factual prose. No quotation marks in prose. En-dash dateline format where used.

**Dateline format:** City, Region, Country – Day Month Year.

**Example:**
> London, England, United Kingdom – 14 February 2026. A large-scale street art mural covers the corner facade of a Victorian commercial terrace on Kingsland Road in Dalston, Hackney…

**Standing rules:**
- Dark-ground signs in the Metropolitan Borough of Hampstead area: default to ceramic mosaic tile, not painted metal, unless visual evidence suggests otherwise
- Bronze statues: always include full sculptor attribution
- No internal double-quotes in captions (use single quotes if needed — Transporter requirement)
- Title Case for titles
- Descriptions should add contextual/historical value beyond the visual — Getty rewards informative captions

---

## CSV/Pipeline Format Rules
- QUOTE_MINIMAL with caption newlines collapsed to single spaces
- Keywords semicolon-separated (Transporter rejects comma-separated)
- Internal double-quotes replaced with single quotes
- All keywords pre-imported into Lightroom keyword catalogue before running Transporter
- DeepMeta title field: 63-character limit (bug now fixed but worth monitoring)

---

## Getty Keyword Vocabulary Guide

### Core Principles
- Target 40–55 keywords per asset
- Below 30 is undertagged; above 66 risks dilution (66 is the highest observed)
- Keywords cannot be edited after submission
- Subject scarcity beats keyword density — under-supplied subjects outperform over-tagged generic ones

### The Three-Tier Hierarchy

Apply to every subject:

| Tier | Food example | Flag example | Architecture example |
|---|---|---|---|
| Specific | `Rhubarb` | `Kuwaiti Flag` | `Battersea Power Station` |
| Category | `Vegetable` | `National Flag` | `Power Station` |
| Broadest | `Food and Drink` | `Flag` | `Architecture` |

### Standard Core Keywords
Apply to almost every asset:
`No People` · `Color Image` · `Close-up` · `Freshness` · `Photography` · `Horizontal` or `Vertical` · `Outdoors` or `Indoors` · `Tradition` · `Cultures` · `Day` · `Travel` · `Travel Destinations` · `Famous Place` (landmarks)

### Getty Compound Terms (exact spelling required)

**Food & Ingredients**
`Chili Pepper` · `Pepper - Vegetable` · `Fat - Nutrient` · `Heat - Temperature` · `Rice - Food Staple` · `Sugar - Food` · `Lamb - Meat` · `Dessert - Sweet Food` · `Leaf Vegetable` · `Red Chili Pepper` · `Serving Food and Drinks` · `Food Staple` · `Savory Food` · `Sweet Food` · `Ready-To-Eat` · `Street Food` · `Fine Dining` · `Dried Food` · `Dried Fruit` · `Apple - Fruit` · `Nut - Food` · `Berry Fruit` · `Rose - Flower` · `Indonesian Food` · `Unhealthy Eating`

**Architecture & Urban**
`Bell Tower - Tower` · `Town Hall - Government Building` · `Temple - Building` · `Wall - Building Feature` · `GLA Building` · `Architectural Column` · `Architectural Dome` · `Residential Building` · `Residential District` · `Built Structure` · `Building Exterior` · `Building Story` · `Row House` · `Townhouse` · `Sash Window` · `Listed Building` · `Run-Down` · `Housing Problems` · `Housing Development`

**Retail & Commercial**
`Closed Sign` · `Store Sign` · `Store Window` · `Commercial Sign` · `Commercial Activity` · `Retail Occupation` · `Finance and Economy` · `Small Business` · `Real Estate`

**Signs & Typography**
`Street Name Sign` · `Road Sign` · `Directional Sign` · `Information Sign` · `Wayfinding` · `Signage` · `Typescript` · `Borough - District Type` · `Identity` · `Illuminated` · `French Language` · `Japanese Script` · `Latin Script` · `Kanji` · `House Address`

**Geography Compounds**
`London - England` · `Chicago - Illinois` · `China - East Asia` · `Nine Elms - London` · `Kensington And Chelsea` · `East London` · `Central London` · `City of London` · `Finsbury` · `Kensington High Street` · `South Kensington` · `Upper West Side Manhattan` · `Manhattan - New York City` · `Central Park - Manhattan` · `Sichuan Province` · `Kyoto Prefecture` · `Xinjiang Province` · `Nouvelle-Aquitaine` · `South Holland` · `Kyrgyzstani Culture` · `Central Asia`

**Flags & Politics**
`All Middle Eastern Flags` · `Persian Gulf Countries` · `National Flag` · `Patriotism` · `Independence - Concept` · `Insignia` · `Diplomacy` · `Embassy` · `Politics and Government` · `US Embassy`

**Religion & Heritage**
`Temple - Building` · `Place of Worship` · `Religious Offering` · `Nandi - Religious Symbol` · `Shiva - Hindu God` · `UNESCO World Heritage Site` · `UNESCO - Organised Group` · `Spirituality` · `Praying` · `Protestantism` · `Religious Cross` · `Christopher Wren` (architect as keyword)

**Botany & Plants**
`Beauty In Nature` · `Flowering Plant` · `In Bloom` · `Lush Foliage` · `Homegrown Produce` · `Healthcare And Medicine` · `Herbal Medicine` · `Alternative Medicine` · `Poisonous` · `Herb Garden` · `Horticulture` · `Carnivorous Plant` · `Endangered Species` · `Threatened Species` · `Endemic - Species` · `Flora Family` · `Insectivore` · `Living Organism` · `Pitcher Plant`

**Luxury & Lifestyle**
`Old Bond Street` · `Haute Couture` · `Glamour` · `Luxury` · `Upper Class` · `Wealth` · `Expense` · `Elegance`

**Compositional / Editorial**
`Establishing Shot` · `Wide Shot` · `High Angle View` · `Directly Above` · `Stationary` · `Editorial` · `Part of a Series`

**Market & Bazaar**
`Bazaar Market` · `Market - Retail Space` · `Market Stall` · `Farmer's Market` · `Abundance` · `Sack` · `Osh Bazaar` (model: always name specific markets)

**London-Specific**
`Dragon` (City of London heraldic symbol) · `City of London` (Square Mile only) · `GLA Building` · `Christopher Wren` · `Finsbury`

### Collection/Aggregation Tags
Surface assets when buyers browse categories rather than search specific terms:
`All Middle Eastern Flags` · `Persian Gulf Countries` · `Szechuan Cuisine` · `East Asian Culture` · `West Africa` · `African Culture` · `Southeast Asia` · `South Asian Culture` · `British Culture` · `UNESCO World Heritage Site` · `Dutch Culture` · `Kyrgyzstani Culture` · `Central Asia` · `Indonesian Culture`

### Flags Checklist
Every national flag asset must include:
- Specific compound (e.g. `Kuwaiti Flag`, `Swedish Flag`)
- `National Flag`
- `Flag`
- `Patriotism`
- `Symbol`
- `Insignia`
- `Politics and Government`
- Relevant regional collection tag
- `Capital Cities` if shot in capital
- City and country geography compounds

### RPD Patterns by Subject

| Subject | Typical RPD | Notes |
|---|---|---|
| Flags (premium editorial) | $4–5 | Illinois $4.69 highest observed |
| Architectural landmarks | $2–4 | |
| Niche produce/food | $2–3 | Rhubarb $2.17 |
| Flags (subscription) | $0.40–0.50 | Kuwait $0.42 |
| Niche national dishes | $0.10–0.25 | Tavče gravče $0.11 |

### Errors to Avoid
- Sri Lankan Culture on Nepalese/Hindu content
- Fine Dining on street-food-origin dishes
- Incorrect City field (check Nottingham Council House — tagged City: London in error)
- Keyword count below 30
- Missing `UNESCO - Organised Group` when `UNESCO World Heritage Site` is present
- Ubud on Lombok content (geographic mismatch)
- Applying Tepuis (South American habitat) to Chelsea/Kew specimens

---

## Street Name Plates Project Reference
- Dataset: 253+ entries, plates_data.json at /Volumes/Samsung PSSD T7/StreetNamePlatesProject/
- Published: gpmdyg9b4z-spec.github.io/street-name-plates
- Instagram: @streetnameplates
- plate_material vocabulary: `cast-iron` · `ceramic` · `enamel` · `modern-metal` · `modern-plastic` · `painted-glass` · `painted-metal` · `painted-wall` · `painted-wood` · `stone-carved`
- Borough naming: pre-1965 Metropolitan Borough names
- Getty term for these assets: `Street Name Sign` (not "street name plate")
- Duplicate policy: same street + same material = skip; same street + different material or era = include with cross-reference

---

## Knowledge Base: Lessons from Existing Assets

Derived from audit of submitted assets where keywords can no longer be edited. Apply these rules at submission time going forward.

### Keyword Count Floors by Subject

| Subject type | Minimum target | Notes |
|---|---|---|
| Ceramic / craft / folk art | 40 | Ortigia Testa di Moro submitted at 23 — severe undercount |
| Campus / historic architecture | 40 | Princeton East Pyne submitted at 25 — no sales |
| Wildlife / nature | 40 | Orca asset submitted at 28 |
| Middle East architecture | 40 | Katara Pigeon Towers at 31 — borderline |
| Religious flags | 38 | Church of Sweden flag at 26 |
| NYC landmarks | 45–55 | Irish Famine Memorial (53) and Dakota Building (45) are the benchmark |

### Subject-Specific Keyword Gaps to Always Fill

**Ceramic crafts / folk art objects**
Always add: `Handmade` · `Traditional Culture` · `Folklore` · `Souvenir` · `Mediterranean Culture` · `Travel Destinations` · `Famous Place` · `Tradition` · `Day` · `Outdoors` · `Art` · `Painted` · `Head` · `Face` · `Gift`

**Marine wildlife**
Always add: `Killer Whale` (for orca) · `Marine Mammal` · `Mammal` · `Wildlife` · `Dorsal Fin` · `Water` · `Ocean` · `Dramatic Landscape` · `International Border` (if relevant) · `Mist` · `Nature`

**Functional / vernacular architecture (towers, dovecotes, non-monumental structures)**
Always add: `Cultural Village` · `Agriculture` · `Sustainable` · `Heritage` · `Animal` · named site keyword (e.g. `Katara`)

**Religious flags (church, institutional — distinct from national flags)**
Apply standard flags checklist plus: `Christianity` · `Patron Saint` · `Crown` · `Spirituality` · `Low Angle View` · `Religion` · `Place of Worship`

**Campus / Ivy League / university buildings**
Always add: `Architecture` · `Built Structure` · `Building Exterior` · `College - Education Building` · `Historic Site` · `Stone Material` · `Famous Place` · `Travel` · `Travel Destinations`

**Blue hour / dawn / dusk architecture**
Always add: `Blue Hour` · `Dusk` or `Dawn` · `Long Exposure` (if applicable) · `Twilight` · `Morning` or `Evening` · `Illuminated`

### General Rules Reinforced by This Audit
- The standard core keywords (`No People` · `Color Image` · `Photography` · `Outdoors` · `Day` · `Travel` · `Travel Destinations` · `Tradition` · `Cultures`) must be checked against every asset before submission — several older assets are missing multiple of these
- Named-site keywords (e.g. `Katara`, `Princeton University`, `Dakota Apartments - New York City`) should always be included where the specific location is identifiable and searchable
- For assets with zero sales and low keyword counts, the two are likely correlated — prioritise keyword depth on niche or non-London subjects where search volume is lower

---

*Paste this document at the start of each new session to restore context.*
