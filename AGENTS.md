# Wetlands Project — Agent Memory

Last updated: 2026-06-18

## Project Overview

KWF (Kenai Watershed Forum) is developing a full proposal for the NFWF National Coastal Resilience Fund (NCRF) 2026 cycle. The project focuses on Cook Inlet coastal wetlands stewardship, decision support, and community capacity building on the Kenai Peninsula, AK.

## Key People

- **Alie Minium** — Hydrology Coordinator (full-time wetlands coordinator), will serve as **PI** on the 2026 proposal — independent of Benjamin Meyer's #84304 work
- **Benjamin Meyer** — Environmental Scientist, PI on existing NCRF grant #84304 (stream mapping)
- **Trent Dodson** — Executive Director, project manager
- **Candace Nakagawa** — Accounts & Grants Manager

## Key Files

| File | Description |
|---|---|
| `other/documents/DRAFT FULL PROPOSAL ncrf-2026.docx` | Original 9-page draft (do not edit directly) |
| `other/documents/DRAFT FULL PROPOSAL ncrf-2026 - 20260618.docx` | **Current working draft** as of 2026-06-18 |
| `other/documents/DRAFT FULL PROPOSAL ncrf-2026-v2.docx` | Earlier working draft with some programmatic edits applied |
| `other/documents/proposal_edits_reference.qmd` | **Primary working doc** — all proposed paragraph replacements for manual copy-paste into Word |
| `other/documents/previous_proposal/` | Funded 2024 NCRF proposal (#84304) for reference |
| `other/documents/CookInletWetlands.zip` | Cook Inlet wetlands shapefile (NAD83 Alaska StatePlane ft) |
| `other/agent_context/agent_context.qmd` | Task description (updated 2026-06-18) |

`other/documents/` is excluded from Git (added to `.gitignore`).

## Proposal Status (as of 2026-06-18)

**Target:** 8 pages maximum including Section E reviewer responses

### Structure of proposal_edits_reference.qmd

The QMD has two dated sections. **Apply 6/18 edits for Q3, Q7, and Q9** — they supersede the 6/15 versions of those paragraphs.

**6/15 section (lines ~1–178):** Bulk cuts targeting the 8-page limit. Replacement paragraphs for Q1, Q2, Q5, Q6, Q7, Q9, Section A Methods intro, Activities 1/3/6, Section C Monitoring, and all 4 Section E reviewer responses. Also includes a word count summary table and an "Additional Cuts" list.

**6/18 section (lines ~191–233):** Three targeted edits to reinforce Section E reviewer comment themes throughout the proposal body. These supersede the 6/15 versions of Q7 and Q9.

| Edit | Paragraph | Comment addressed | Net words |
|------|-----------|-------------------|-----------|
| 2026-A | Q3 Pipeline Project | Comment 1 (capacity/dual-PI) | −2 |
| 2026-B | Q7 Community Benefits | Comment 2 (flood specificity, adds Kalifornsky Beach) | 0 |
| 2026-C | Q9 Scale/Transferability | Comment 3 (names 4 physiographic regions, federal exclusion) | +12 |

### Edits Already Reflected in 20260618.docx
- `[MAP ATTACHMENT]` resolved → `proposal_map.pdf`
- `[ATTACHMENT X1]` resolved → `wetlands_infographic.pdf`
- Most 6/15 QMD edits appear already incorporated
- Section E has Comments 1, 2, 3 responses present; Comment 4 is still missing

### Outstanding Issues Before Submission
- Comment 4 (match timing) not yet in document — add both comment text and response from 6/15 QMD section
- Annotated map showing #84304 and 2026 project footprints needs to be uploaded
- Apply 6/18 edits A, B, C from QMD if not yet done

**Projected net reduction from all QMD edits: ~400 words** — should reach 8-page target.

## Reviewer Comments (all 4)

1. Explain relationship to current NCRF grant #84304 and organizational capacity for both
2. Articulate flood/erosion risk reduction benefits more clearly and specifically
3. Provide exact project location and size (acres/linear feet); upload annotated map
4. Match must be expended within the period of performance — review match sources

## Project Area

- **Geographic scope:** Kenai Peninsula coastal lowlands within KPB — Nikishka Lowlands, Ninilchik Lowland, Homer Bench, Fox River Lowland physiographic regions
- **Excludes:** Kenai National Wildlife Refuge, Chugach National Forest
- **Wetland acreage:** ~229,000 acres (from Cook Inlet Wetlands shapefile; field `acres` is pre-calculated; CRS: NAD83 Alaska StatePlane Zone 4 feet)

## GIS Data

- `CookInletWetlands.shp` (in zip): 38,691 features, projected CRS (feet), use `acres` field for area (do not recalculate from geometry without reprojecting to meters first)
- Total dataset acreage: ~716,639 acres across all Cook Inlet physiographic regions

## Key Framing Lessons from Funded 2024 Proposal (#84304)

1. State explicit causal mechanism for flood resilience ("wetlands act as sponges... their loss directly reduces storage")
2. Always state the downstream regulatory/conservation outcome that identifying priority wetlands enables
3. Section E reviewer responses work best as concise bullets addressing each sub-question directly
4. Quantify past success and project scale throughout
5. Body text must corroborate Section E claims — reviewers read the narrative first
