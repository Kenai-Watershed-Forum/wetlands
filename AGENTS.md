# Wetlands Project — Agent Memory

Last updated: 2026-06-15

## Project Overview

KWF (Kenai Watershed Forum) is developing a full proposal for the NFWF National Coastal Resilience Fund (NCRF) 2026 cycle. The project focuses on Cook Inlet coastal wetlands stewardship, decision support, and community capacity building on the Kenai Peninsula, AK.

## Key People

- **Alie Minium** — Hydrology Coordinator, new hire, will serve as **PI** on the 2026 proposal
- **Benjamin Meyer** — Environmental Scientist, PI on existing NCRF grant #84304 (stream mapping)
- **Trent Dodson** — Executive Director, project manager
- **Candace Nakagawa** — Accounts & Grants Manager

## Key Files

| File | Description |
|---|---|
| `other/documents/DRAFT FULL PROPOSAL ncrf-2026.docx` | Original 9-page draft (do not edit directly) |
| `other/documents/DRAFT FULL PROPOSAL ncrf-2026-v2.docx` | Working draft with programmatic edits applied |
| `other/documents/proposal_edits_reference.qmd` | **Primary working doc** — all proposed paragraph replacements and Section E responses for manual copy-paste into Word |
| `other/documents/previous_proposal/` | Funded 2024 NCRF proposal (#84304) for reference |
| `other/documents/CookInletWetlands.zip` | Cook Inlet wetlands shapefile (NAD83 Alaska StatePlane ft) |
| `other/agent_context/agent_context.qmd` | Original task description |

`other/documents/` is excluded from Git (added to `.gitignore`).

## Proposal Status (as of 2026-06-15)

**Target:** 8 pages maximum including Section E reviewer responses  
**Current state of v2.docx:** Programmatic edits applied; still needs manual paragraph replacements from the QMD

### Edits Already Applied to v2.docx
- Edit 1: Removed duplicate "in 2015" from Coastal Hazards paragraph
- Edit 2: Merged redundant opening sentences in Proposed Solution paragraph
- Edit 4: Condensed NHD/NetMap description in Activity 1
- Edit 6: Consolidated fragmented team bios into single paragraphs (no visual space savings due to Word formatting, but cleaner structure)

### Edits in QMD — Awaiting Manual Copy-Paste into Word
All of these are in `proposal_edits_reference.qmd`, organized in document order:
- Q1 Coastal Hazards: 201 → 135 words
- Q2 Past Planning: 154 → 108 words
- Q5 Proposed Solution: 154 → 130 words
- Q6 Deliverables: 125 → 76 words
- Q7 Community Benefits: 170 → 105 words
- Q9 Scale/Transferability: 104 → 72 words
- Section A Methods intro: 111 → 45 words
- Activity 1: 305 → 230 words
- Activity 3: 198 → 138 words
- Activity 6: 103 → 79 words
- Section C Monitoring: 141 → 77 words
- **Section E: 4 reviewer responses** (~285 words total, not yet in document at all)

**Projected net reduction: ~400 words** — should reach 8-page target.

### Outstanding Issues Before Submission
- `[MAP ATTACHMENT]` and `[ATTACHMENT X1]` are placeholders in Activity 1 — need actual file references
- Comment 4 (match timing) is not yet in the Word document — both the comment text and response need to be added
- Annotated map showing #84304 and 2026 project footprints needs to be uploaded

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
