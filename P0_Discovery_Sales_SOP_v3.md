# P0 — Discovery & Sales

**FANCY LAB** · Web Development Department
Standard Operating Procedure & Phase Gate Document

| Version | Date | Status |
|---|---|---|
| v3.0 | April 2026 | Confidential |

## Table of Contents

- [Revision History](#revision-history)
- [Purpose & Scope](#purpose--scope)
- [WHO — RACI Matrix](#who--raci-matrix)
- [WHAT — Deliverables](#what--deliverables)
- [WHERE — Tools & Platforms](#where--tools--platforms)
- [HOW — Process Steps](#how--process-steps)
- [Communication — Stakeholder Updates](#communication--stakeholder-updates)
- [Escalation — Blocked Phase Protocol](#escalation--blocked-phase-protocol)
- [Dependencies — Required Inputs](#dependencies--required-inputs)
- [Revision Limits & Scope Control](#revision-limits--scope-control)
- [Phase Gate — Completion Checklist](#phase-gate--completion-checklist)
- [Data Enrichment](#data-enrichment-clickup-export-2026-04-22)
- [Appendix A: Project Brief Template](#appendix-a-project-brief-template)

## Revision History

<details>
<summary>v3.0 (April 2026) — GitHub-render pass</summary>

- Restructured headings: `**BOLD CAPS**` paragraphs → `##` / `###`, so GitHub's outline sidebar populates.
- Replaced empty-header pandoc tables (`|  |  |  |` + bolded content row) with proper pipe tables.
- Converted nested-blockquote process steps (`> **1. Step**`) to ordered lists.
- Unescaped pandoc backslash noise (`\|`, `\-`, `\#`, `\<`, `\>`, `\_`).
- Added TOC, metadata table; wrapped Appendix A (Project Brief Template) in `<details>` and converted the raw HTML `<table>` into twelve `###`-sectioned pipe tables.
- No content changes — every fact, number, named person, client, and cell preserved verbatim from v2.

</details>

<details>
<summary>v2.0 (April 2026) — ClickUp enrichment</summary>

v1.0 (Feb 2026) → v2.0 (Apr 2026):

- Rebranded from "EVO SEM" to "FANCY LAB" in Purpose & Scope (per `CLAUDE.md` conventions; v1 still referenced the legacy entity name).
- **Fixed ClickUp drift in step 8 / gate item #8** — the ClickUp project list is opened during P1 Onboarding, not P0 Sales. Step 8 and gate item #8 now reference the artifacts actually created during sales (CRM / PandaDoc opportunity record); a note flags that ClickUp list creation is owned by P1. Less invasive than moving the step out of this file (Option (b) in spawn brief). Per `data/analysis/03_sop_gap_and_recommendations.md` §C item 1 and §D item 9.
- **Made the proposal-stall escalation auditable** by introducing a `proposal-archived` ClickUp tag and a weekly Sales pipeline review step in the Escalation table. Per `data/analysis/03_sop_gap_and_recommendations.md` §D item 9 follow-up note and the §Data Enrichment "Risk — proposal stall" item in the merged rollup.
- Added `## Data Enrichment (ClickUp export, 2026-04-22)` section after the Phase Gate sign-off; ports the rollup's stats (34 signed contracts, 34 deposits) and named client examples as evidence base for P0 throughput.
- Updated Appendix A internal cross-reference from `P0_..._v1.md` to `P0_..._v3.md`.

</details>

## Purpose & Scope

This SOP defines the standard process for the initial sales engagement,
project scoping, proposal delivery, and payment processing for all new
web development projects at FANCY LAB. It ensures that every project
begins with a clear agreement on scope, deliverables, timelines, and
costs before any work commences.

### Phase Objective

Secure a signed contract and deposit payment, establish a clear project
brief that defines scope boundaries, and ensure all billing and
accounting records are properly set up before transitioning to client
onboarding.

### Scope Includes

- Initial discovery call with prospective client
- Project scoping and requirements gathering
- Proposal creation and delivery via PandaDoc
- Contract negotiation and signing
- Deposit payment processing
- Project brief documentation
- Internal team notification via Slack

### Scope Excludes

- Detailed technical requirements (covered in P2 - Project Specification)
- Design or development work of any kind
- Third-party tool procurement or setup
- Client onboarding activities (covered in P1)
- ClickUp project list creation (owned by P1 - Client Onboarding; see step 8 note below)

## WHO — RACI Matrix

| Role | Person(s) | Responsibility |
|---|---|---|
| Responsible | Harry + Rinaldo | *Performs the work for this phase* |
| Accountable | Harry + Rinaldo | *Ultimately answerable for completion* |
| Consulted | Harry + Rinaldo | *Provides input and approves deliverables* |
| Informed | Harry + Rinaldo | *Kept up to date on progress* |

## WHAT — Deliverables

| Deliverable | Format / Location | Owner |
|---|---|---|
| Discovery Meeting Notes | Google Docs / Drive | Harry + Rinaldo |
| Project Brief / Strategy | Google Docs / Drive | Harry + Rinaldo |
| Proposal Document | PandaDoc | Harry + Rinaldo |
| Signed Contract | PandaDoc | Harry + Rinaldo |
| Deposit Invoice + Payment Confirmation | Accounting System | Harry + Rinaldo |
| CRM / PandaDoc Opportunity Record | PandaDoc + CRM | Harry + Rinaldo |
| Welcome Email | Email | Harry + Rinaldo |

## WHERE — Tools & Platforms

| Tool | Purpose in This Phase |
|---|---|
| Google Meet | Discovery calls and client meetings |
| Google Drive | Meeting notes, project brief storage |
| PandaDoc | Proposal creation, contract signing, payment processing; opportunity record of truth for P0 |
| Slack | Internal team notification when deal is closed |
| ClickUp | Sales-pipeline tracking only in P0 (opportunity card in the Sales list); project list / project workspace are created in P1 - Client Onboarding |

## HOW — Process Steps

1. **Schedule Discovery Meeting.** Coordinate a discovery call with the prospective client to understand their business, goals, current website situation, and project needs.

2. **Conduct Discovery Meeting.** During the call, gather information on: business model, target audience, competitors, desired features, content readiness, brand assets, timeline expectations, and budget range. Document all notes in Google Drive.

3. **Create Project Brief / Strategy.** Synthesize discovery notes into a structured project brief that outlines: project objectives, proposed approach, estimated timeline, key assumptions, and out-of-scope items.

4. **Prepare and Send Proposal.** Create a detailed proposal in PandaDoc including: project scope, phased deliverables, timeline, pricing breakdown, payment schedule, revision limits, and terms of service. Send to client for review.

5. **Negotiate and Finalize Contract.** Address any client questions or requested changes to the proposal. Make adjustments as needed while maintaining scope boundaries. Finalize and obtain electronic signature via PandaDoc.

6. **Process Deposit Payment.** Confirm deposit payment has been received. Update accounting records. Generate payment confirmation for client.

7. **Send Welcome Email + Next Steps.** Send the client a welcome email confirming: project start date, next steps (onboarding), key contacts, and what to prepare for the onboarding meeting.

8. **Record the Opportunity in CRM / PandaDoc and Notify Internal Team.** Confirm the opportunity record is complete in PandaDoc (signed contract, deposit confirmation attached) and the corresponding card in the ClickUp **Sales** list is moved to "Closed-Won". Post in the designated Slack channel: client name, project type, timeline, assigned team, and link to project brief.

> [!IMPORTANT]
> The project's ClickUp list / workspace is created during P1 - Client Onboarding, not here. P0's ClickUp footprint is limited to the Sales pipeline opportunity card. Do not create the project list during P0 — Carlos opens it as the first action of P1.

## Communication — Stakeholder Updates

| Type | Frequency | Audience | Channel |
|---|---|---|---|
| Discovery Call | Once (at phase start) | Client + Sales Lead | Google Meet |
| Proposal Delivery | Once | Client Decision Maker | PandaDoc / Email |
| Contract Follow-up | As needed (max 3 follow-ups) | Client | Email / Phone |
| Sales Pipeline Review | Weekly | Harry + Rinaldo | ClickUp Sales list |
| Internal Notification | Once (at phase close) | Full Project Team | Slack |

## Escalation — Blocked Phase Protocol

| Trigger | Timeframe | Escalation Action | Escalated To |
|---|---|---|---|
| Client unresponsive to proposal | 5 business days | Send follow-up email with gentle reminder; tag the ClickUp opportunity card `proposal-stalled` | Harry / Rinaldo |
| Client unresponsive after follow-up | 10 business days | Final outreach call; if no response, archive opportunity by moving the ClickUp card to status "Archived" and applying tag `proposal-archived` | Harry |
| Contract negotiation stalled | 7 business days | Schedule call to address concerns directly | Rinaldo |
| Payment not received after signing | 3 business days | Send payment reminder; hold project start | Harry + Rinaldo |
| Weekly Sales pipeline review | Every Monday | Audit ClickUp Sales list: any opportunity with `proposal-stalled` ≥10 business days that has not been moved to `proposal-archived` is escalated for archival decision | Harry + Rinaldo |

*The `proposal-archived` tag is the auditable signal that the 10-day
unresponsive rule was actually enforced. The Monday Sales review is the
control that catches missed archivals — this closes the v1 gap where
"archive opportunity" had no enforcement mechanism (per
`data/analysis/03_sop_gap_and_recommendations.md` §D item 9).*

## Dependencies — Required Inputs

| Dependency | Source Phase | Impact if Missing |
|---|---|---|
| None - This is the first phase | N/A | N/A |

## Revision Limits & Scope Control

Proposal Revisions: Up to 2 rounds of revisions included before
additional scoping fees apply

Scope Changes: Any scope changes after contract signing require a formal
Change Order with updated pricing and timeline

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

## PHASE GATE — Completion Checklist

> [!WARNING]
> ALL items below must be completed and verified before the project can advance to P1 - Client Onboarding. No onboarding activities should begin until deposit is confirmed.

| # | Gate Requirement | Status | Date |
|---|---|---|---|
| 1 | Discovery Meeting completed and notes documented in Drive |  |  |
| 2 | Project Brief / Strategy document created and stored |  |  |
| 3 | Proposal sent to client via PandaDoc |  |  |
| 4 | Client has signed the contract (PandaDoc `Client Signed Contract` checklist item ticked) |  |  |
| 5 | Deposit payment received and confirmed (PandaDoc `Client Paid Deposit` checklist item ticked) |  |  |
| 6 | Welcome Email sent to client with next steps |  |  |
| 7 | Internal team notified via Slack with project details |  |  |
| 8 | Opportunity record complete in CRM / PandaDoc and ClickUp Sales-list card moved to "Closed-Won" *(Note: project ClickUp list is created in P1, not here)* |  |  |
| 9 | Sales-list card status set to "Closed-Won" in ClickUp |  |  |
| 10 | Project Brief Template (Appendix A of `P0_..._v3.md`) fully completed |  |  |

### Phase Gate Sign-Off

| Field | Details | Date |
|---|---|---|
| Project Name |  |  |
| Approved By |  |  |
| Client Rep |  |  |
| Next Phase | P1 - Client Onboarding |  |
| Notes / Conditions |  |  |

## Data Enrichment (ClickUp export, 2026-04-22)

*Sourced from the ClickUp data analysis at `data/analysis/` (see
`03_sop_gap_and_recommendations.md` and `Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md`
lines 93–99). Numbers reflect observed activity across the export window.*

- **Signal of phase completion in the export.** The checklist items
  `Client Signed Contract` (34 occurrences) and `Client Paid Deposit`
  (34 occurrences) appear across onboarding tasks in client lists
  including `Steindiamonds.com`, `hawaiilabgrown.com`, `anglodiamond.com`,
  and `christopher-salon.com`. Read at face value, ~34 projects have
  cleared the P0 gate in the observed window. These two checklist items
  are the reliable downstream evidence that gate items #4 and #5 were
  satisfied — use them as the audit trail when reconciling P0 throughput.
- **Gap vs. SOP — addressed in v2.** v1 listed "ClickUp project record
  created" at step 8, but the dataset shows the project's ClickUp list is
  typically opened during onboarding, not at contract signing. v2 rewrites
  step 8 and gate item #8 to reference the CRM / PandaDoc opportunity
  record (the actual P0 artifact) and explicitly notes that ClickUp list
  creation is owned by P1.
- **Risk — proposal stall, addressed in v2.** v1's escalation said
  "Client unresponsive after 10 business days → archive opportunity",
  but nothing in the dataset confirmed archival was happening. v2
  introduces the `proposal-archived` ClickUp tag and a Monday Sales
  pipeline review as the control. Going forward the count of cards with
  `proposal-archived` should be tracked against the count of cards with
  `proposal-stalled` to confirm the rule is being enforced.
- **Throughput baseline.** 34 signed contracts / 34 deposits is the
  observed P0 completion volume in the dataset window; future revisions
  of this SOP should compare against this baseline to flag pipeline
  contraction or expansion.

---

## Appendix A: Project Brief Template

<details>
<summary>Expand — Project Brief Template</summary>

*This template must be fully completed during the Discovery & Sales phase.
All fields are required unless marked [Optional]. A completed Project
Brief is a gate requirement before advancing to P1 - Client Onboarding.*

### 1. Client Information

| Field | Description |
|---|---|
| Company / Brand Name | *Legal business name and DBA if different* |
| Primary Contact Name | *First and last name of main point of contact* |
| Primary Contact Email | *Email for all project communications* |
| Primary Contact Phone | *Best phone number and preferred contact hours* |
| Secondary Contact Name | *Backup contact (name, email, phone)* |
| Decision Maker | *Who has final approval authority on design/content? If different from primary contact* |
| Company Website (Current) | *URL of existing site, or N/A if new build* |
| Industry / Vertical | *e.g., Jewelry, Fashion, Health & Wellness, Food & Beverage* |
| Company Description | *2-3 sentence overview of what the business does and who they serve* |

### 2. Project Scope & Objectives

| Field | Description |
|---|---|
| Project Type | *New Website Build / Redesign / Migration / Feature Addition* |
| Platform | *Shopify / Shopify Plus / Other (specify)* |
| Primary Goal | *What is the #1 business outcome this website should achieve?* |
| Secondary Goals | *List 2-3 additional goals (e.g., increase conversions, improve brand perception, enable B2B ordering)* |
| Target Launch Date | *Desired go-live date (mm/dd/yyyy)* |
| Budget Range | *Confirmed project budget or package tier* |
| Must-Have Features | *List all non-negotiable features (e.g., product filtering, quick view, mega menu, wishlist)* |
| Nice-to-Have Features | *[Optional] Features that would be ideal but not critical for launch* |
| Known Integrations | *List all third-party tools/apps needed (e.g., Klaviyo, Judge.me, ShipStation, Diamond Search, ERP)* |
| Payment Gateways Required | *Shopify Payments, PayPal, Affirm, Klarna, other?* |

### 3. Target Audience & Market

| Field | Description |
|---|---|
| Primary Audience | *Who is the ideal customer? (age range, gender, income level, interests)* |
| Secondary Audience | *[Optional] Any secondary customer segments?* |
| Geographic Focus | *Local, National, International? Which countries?* |
| Customer Pain Points | *What problems does the customer have that this site should solve?* |
| Unique Value Proposition | *What makes this brand different from competitors?* |

### 4. Brand & Design Direction

| Field | Description |
|---|---|
| Brand Guidelines Available? | *Yes / No / Partial - If yes, where are they stored?* |
| Logo Files Available? | *Yes / No - Formats available (SVG, PNG, AI)?* |
| Brand Colors | *List primary, secondary, and accent colors (hex codes if available)* |
| Brand Fonts | *Specify font families for headings and body, or state if to be determined in design phase* |
| Design Style Preference | *Minimal / Bold / Luxury / Playful / Corporate / Other - Describe the desired feel* |
| Reference / Inspiration Sites | *List 3-5 websites the client admires and what they like about each (be specific: layout, color, UX, photography style)* |
| Photography / Imagery | *Does the client have professional product photos? Lifestyle images? Or will stock photos be needed?* |
| Video Assets | *Any existing video content? Plans for video on the site?* |

### 5. Content & Copywriting

| Field | Description |
|---|---|
| Content Readiness | *Does the client have existing copy for all pages? None? Partial?* |
| Copywriting Needed? | *Yes / No - If yes, specify which pages need copy written* |
| Brand Voice / Tone | *Professional / Casual / Luxury / Friendly / Technical - Describe how the brand speaks* |
| Key Messaging / Taglines | *Any established taglines, slogans, or key messages to incorporate?* |
| Blog / Content Marketing | *Will the site include a blog? If yes, is content being provided by client?* |
| Legal Pages Needed | *Privacy Policy, Terms of Service, Return Policy, Shipping Policy - who provides these?* |

### 6. Products & Inventory

| Field | Description |
|---|---|
| Number of Products (approx.) | *How many total SKUs at launch?* |
| Number of Collections | *How many product categories/collections?* |
| Product Data Source | *Manual entry / CSV import / ERP feed / Vendor API / Existing Shopify store?* |
| Product Variants | *Do products have variants (size, color, material)? Approximately how many per product?* |
| Product Metafields | *Any custom product data needed? (e.g., specs, certifications, care instructions, diamond attributes)* |
| Inventory Management | *Who manages inventory? In Shopify? In ERP? Multi-location?* |
| Vendor / Brand List | *List all brands/vendors whose products will be on the site* |
| Diamond / Gem Search | *[If applicable] MyDiamonds, Nivoda, or other feed? Which vendors?* |
| Ring Builder / Customization | *[If applicable] Custom ring builder, engraving, or personalization features needed?* |

### 7. Site Architecture & Pages

| Field | Description |
|---|---|
| Estimated Number of Pages | *Total unique page templates needed (Home, About, Contact, Collection, PDP, Blog, Custom...)* |
| Navigation Structure | *Describe desired menu structure: mega menu? How many levels? Key categories?* |
| Custom Pages Required | *List any special pages beyond standard (e.g., Store Locator, Custom Quiz, Lookbook, B2B Portal)* |
| Search Functionality | *Standard Shopify search or enhanced (e.g., predictive search, filters by attributes)?* |
| Multi-Language Required? | *Yes / No - If yes, which languages?* |
| Multi-Currency Required? | *Yes / No - If yes, which currencies?* |

### 8. SEO & Migration Requirements

| Field | Description |
|---|---|
| Existing Website Platform | *What platform is the current site on? (Shopify, WordPress, Wix, Squarespace, Custom, None)* |
| URL Redirect Mapping Needed? | *Yes / No - If migrating, do existing URLs need to be preserved with 301 redirects?* |
| Existing SEO Rankings | *Does the client have pages that rank well in Google that must be preserved?* |
| Google Analytics Access | *GA4 property ID / access status* |
| Google Search Console Access | *GSC verified property / access status* |
| SEO Priorities | *Any specific keywords, pages, or SEO goals for the new site?* |
| Domain Setup | *Current registrar? Who manages DNS? Any subdomains needed?* |

### 9. Technical & Integration Requirements

| Field | Description |
|---|---|
| Email Marketing Platform | *Klaviyo / Mailchimp / Omnisend / Other?* |
| Reviews Platform | *Judge.me / Yotpo / Loox / Stamped / Other?* |
| Shipping Solution | *ShipStation / Shippo / Shopify Shipping / Other?* |
| Loyalty / Rewards Program | *[Optional] Smile.io / LoyaltyLion / Other?* |
| Live Chat / Support | *[Optional] Gorgias / Zendesk / Tidio / Other?* |
| Social Media Integration | *Instagram feed, Facebook Shop, TikTok Shop, Pinterest?* |
| Custom API / ERP Integration | *[Optional] Any custom backend integrations?* |
| Age Verification / Compliance | *[Optional] Any regulatory requirements (age gate, GDPR, ADA)?* |

### 10. Access & Credentials Checklist

| Field | Description |
|---|---|
| Shopify Admin Access | *Provided / Pending / N/A (new store to be created)* |
| Domain Registrar Login | *Provided / Pending - Registrar name?* |
| Current Hosting Login | *Provided / Pending / N/A* |
| Email Marketing Login | *Provided / Pending / N/A* |
| Google Analytics Access | *Provided / Pending / N/A* |
| Social Media Credentials | *Provided / Pending / N/A* |
| Payment Gateway Access | *Provided / Pending / N/A* |
| Other Third-Party Logins | *List any additional platform access needed* |

### 11. Timeline & Client Expectations

| Field | Description |
|---|---|
| Agreed Start Date | *mm/dd/yyyy* |
| Target Launch Date | *mm/dd/yyyy* |
| Design Review Rounds | *Number of included revision rounds (default: 2)* |
| Client Response SLA | *Expected client turnaround time for feedback (default: 3 business days)* |
| Meeting Cadence | *Weekly check-ins? Bi-weekly? Design review meetings only?* |
| Client Availability | *Any blackout dates, vacations, or busy periods during the project?* |
| Hard Deadlines | *Any immovable dates? (e.g., product launch, trade show, holiday season)* |

### 12. Internal Notes (FANCY LAB Team Only)

| Field | Description |
|---|---|
| Assigned Designer | *Name or TBD* |
| Assigned Developer | *Name or TBD* |
| Assigned PM / Admin | *Name or TBD* |
| Complexity Rating | *Low / Medium / High / Enterprise* |
| Risk Factors | *Any known risks (tight timeline, complex integrations, unclear scope, difficult client history)* |
| Special Considerations | *Any unique aspects of this project the team should be aware of* |
| Sales Notes / Context | *Key notes from the discovery call that provide context for the team* |

Brief Completed By: ____________________________ Date: _______________

Brief Reviewed By: ____________________________ Date: _______________

*Once all fields above are complete, this Project Brief serves as the
foundational document for the entire project. All team members should
reference this brief when making decisions about scope, design
direction, content, and technical implementation.*

</details>
