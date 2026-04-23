# pm-phases

Fancy Lab Web Development department's Standard Operating Procedures, organized as phase gates across the full project lifecycle — from sale through post-launch. Each phase defines the RACI, deliverables, tools, process steps, and the gate requirements that must be satisfied before work can advance.

## Phases

| # | Phase | File |
|---|---|---|
| P0 | Sales & Billing | [P0_Sales_Billing_SOP_v1.md](P0_Sales_Billing_SOP_v1.md) |
| P1 | Client Onboarding | [P1_Client_Onboarding_SOP_v1.md](P1_Client_Onboarding_SOP_v1.md) |
| P2 | Project Kickoff | [P2_Project_Kickoff_SOP_v1.md](P2_Project_Kickoff_SOP_v1.md) |
| P3 | Content Strategy & Copywriting | [P3_Content_Strategy_SOP_v1.md](P3_Content_Strategy_SOP_v1.md) |
| P4 | Branding & Design | [P4_Branding_Design_SOP_v2.md](P4_Branding_Design_SOP_v2.md) |
| P5 | Inventory Management | [P5_Inventory_Management_SOP_v1.md](P5_Inventory_Management_SOP_v1.md) |
| P6 | Development | [P6_Development_SOP_v1.md](P6_Development_SOP_v1.md) |
| P7 | Testing & QA | [P7_Testing_QA_SOP_v3.md](P7_Testing_QA_SOP_v3.md) |
| P8 | Client Approval | [P8_Client_Approval_SOP_v1.md](P8_Client_Approval_SOP_v1.md) |
| P9 | Launch | [P9_Launch_SOP_v1.md](P9_Launch_SOP_v1.md) |
| P10 | Post-Launch | [P10_Post_Launch_SOP_v1.md](P10_Post_Launch_SOP_v1.md) |

An older rolled-up reference is kept in [EVO_SEM_Web_Dev_Phase_Gate_SOPs.md](EVO_SEM_Web_Dev_Phase_Gate_SOPs.md), but the individual phase files above are the source of truth — the consolidated doc predates the Fancy Lab rebrand and the P3 Content Strategy phase, so its numbering is offset from P3 onward.

## SOP template

Every phase file follows the same structure:

- **WHO** — RACI matrix (Responsible / Accountable / Approved By / Informed)
- **WHAT** — deliverables, communication channel, sign-off / handoff
- **WHERE** — data storage and tools used
- **PROCESS** — sequential steps
- **PHASE GATE** — numbered completion requirements the phase cannot advance without, plus a sign-off block

## Conventions

- **Filename = canonical phase number.** External references should cite the filename rather than prose.
- **Version suffix (`_vN`) tracks revisions.** Bump to the next `_vN` rather than overwriting when an SOP changes materially.
- **Inserting or renumbering a phase cascades.** Every downstream file and any external reference has to follow — avoid unless the lifecycle actually changes.
