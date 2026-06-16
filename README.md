# Cook Inlet Wetlands — NCRF 2026 Proposal

**Organization:** Kenai Watershed Forum (KWF)  
**Program:** NFWF National Coastal Resilience Fund (NCRF), 2026 cycle  
**Project:** Cook Inlet (Alaska) Wetlands Stewardship, Decision Support, and Community Capacity Building  
**EasyGrants ID (2026):** 91219 *(full proposal stage)*

---

## About This Repository

This repository supports development of KWF's 2026 NCRF full proposal. It contains analysis code, GIS scripts, AI assistant context files, and project notes. Proposal documents (Word files, PDFs, budget spreadsheets) are stored locally and **excluded from version control** — see `.gitignore`.

This project builds on KWF's currently funded NCRF grant [#84304](https://www.nfwf.org/) (stream mapping, Kenai River watershed, 2025–2027).

---

## Project Summary

The proposed project addresses a regional capacity gap in wetlands stewardship on the Kenai Peninsula. Key activities include:

- **Wetlands Resilience Prioritization Map** — LiDAR-based hydrologic analysis identifying wetlands of highest flood storage and fish habitat value across ~229,000 acres of mapped Cook Inlet coastal lowlands
- **Wetlands Stewardship Cohort** — professional training for ~10 local practitioners in jurisdictional delineation, GIS tools, and current regulations
- **Public decision-support tools** — a "decision tree" for community leaders and landowners navigating wetland inquiries
- **Cook Inlet Wetland Jewels story-map** — public-facing communication of high-value wetlands
- **Community micro-grants** — four subawarded grants ($2,500 each) to tribal organizations, schools, and nonprofits

**Geographic scope:** Kenai Peninsula coastal lowlands within the Kenai Peninsula Borough — Nikishka Lowlands, Ninilchik Lowland, Homer Bench, and Fox River Lowland physiographic regions (excluding Kenai National Wildlife Refuge and Chugach National Forest).

---

## Repository Structure

```
wetlands/
├── other/
│   ├── agent_context/          # AI assistant task context and notes
│   │   └── agent_context.qmd   # Original task description
│   ├── documents/              # ⛔ Excluded from Git — proposal docs, GIS data, PDFs
│   ├── input/                  # Input data files (GIS, tabular)
│   └── output/                 # Analysis outputs
├── AGENTS.md                   # AI assistant memory — project status and key file locations
├── wetlands.Rproj              # RStudio project file
└── README.md
```

> **Note:** `other/documents/` contains the working proposal drafts and supporting documents and is not synced to GitHub. See `AGENTS.md` for a description of key files and current proposal status.

---

## Key Personnel

| Name | Role |
|---|---|
| Alie Minium | Hydrology Coordinator; PI on 2026 proposal |
| Benjamin Meyer | Environmental Scientist; PI on NCRF grant #84304 |
| Trent Dodson | Executive Director; project manager |
| Candace Nakagawa | Accounts & Grants Manager |

---

## GIS Data

The primary wetlands dataset is the **Cook Inlet Wetlands** shapefile (Gracz 2005–2015), distributed as `CookInletWetlands.zip`. It covers 38,691 features across all Cook Inlet physiographic regions (~716,000 acres total). The `acres` field is pre-calculated; the CRS is NAD83 Alaska StatePlane Zone 4 (feet).

---

## Related Resources

- [Kenai Watershed Forum](https://www.kenaiwatershed.org/)
- [NFWF National Coastal Resilience Fund](https://www.nfwf.org/programs/national-coastal-resilience-fund)
- [KPB ViewKPB Wetlands Viewer](https://www.kpb.us/gis)
