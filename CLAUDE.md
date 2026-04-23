# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this directory is

Not a codebase. It's a set of Standard Operating Procedure documents for Fancy Lab's Web Development department, covering the project lifecycle from sale to post-launch. There is no build system, tests, or source code — work here is reading, editing, and cross-referencing markdown files. The SOPs were originally authored as `.docx` and converted to `.md` via `pandoc -t gfm`; the originals have been removed, so the `.md` files are now the source of truth.

## Phase numbering (canonical)

The **filenames** are the source of truth for phase numbers. Current lineup:

- `P0_Discovery_Sales_SOP_v2.md`
- `P1_Client_Onboarding_SOP_v2.md`
- `P2_Project_Specification_SOP_v2.md`
- `P3_Project_Setup_SOP_v3.md`
- `P4_Design_SOP_v3.md`
- `P5_Inventory_SOP_v2.md`
- `P6_Development_SOP_v2.md`
- `P7_Testing_QA_SOP_v4.md`
- `P8_Client_Review_Pre_Launch_SOP_v2.md`
- `P9_Launch_SOP_v2.md`
- `P10_Post_Launch_SOP_v2.md`

The `_vN` suffix marks the current version of each SOP (most are v2; P4 is v3; P7 is v4). All phases were enriched in April 2026 with findings from the ClickUp data analysis in `data/analysis/` — each current file has a Revision History block at the top and a `## Data Enrichment` section after the phase gate.

## The consolidated reference doc is stale — do not trust it for phase numbers

`EVO_SEM_Web_Dev_Phase_Gate_SOPs.md` (Feb 2026, v1.0) is an earlier roll-up and diverges from the individual files in two important ways:

1. **Branding**: it says "EVO SEM". The individual SOPs have since been rebranded to "FANCY LAB".
2. **Numbering / scope**: it has 10 phases (P0–P9) and no Project Setup phase. Its P3 is "Inventory Management", so everything from P3 onward is numbered one lower than the current filenames.

When a user asks about a phase by number, map it against the filenames, not this doc. If asked to update or regenerate the consolidated doc, treat the individual SOPs as the source of truth.

## SOP template (uniform across all phases)

Every phase file follows the same structure. When editing, preserve these section headers:

- **WHO** — RACI matrix (Responsible / Accountable / Approved By / Informed). Several phases (P3/P5–P10 in the consolidated doc's older view, and some individual files) still have `[TO BE DEFINED]` entries — confirm with the user before filling these in.
- **WHAT** — Deliverables & Communication (Communication channel, Deliverable, Sign-Off / Handoff).
- **WHERE** — Tools & Data (Data Storage, Tools Used).
- **PROCESS** — numbered Sequential Steps.
- **PHASE GATE** — numbered Completion Requirements the phase cannot advance without, followed by a sign-off block.

## Tooling conventions referenced in the SOPs

Shared tools the SOPs assume are in use: ClickUp (tasks / roadmaps), Figma (design + client commenting), Shopify (dev store + production store), PandaDoc (proposals), Pastel (QA feedback dashboard), Google Drive (assets), Slack (team notifications), Google Meet (client calls). If a new phase or step is drafted, prefer these over introducing new tools unless the user asks.

## Editing guidance

- Edit the `.md` files directly. Pandoc's GFM output represents the RACI / Deliverables / Tools blocks as pipe tables — preserve table structure when editing so the phase template stays scannable.
- When bumping a phase version, rename with the next `_vN` suffix (e.g., `P4_..._v2.md` → `P4_..._v3.md`) rather than overwriting — the version suffix is how the current revision is tracked here.
- Keep phase numbers stable. Inserting a new phase (as happened with P3 Project Setup) cascades renames through every downstream file and breaks any external references; flag this cost to the user before doing it.
