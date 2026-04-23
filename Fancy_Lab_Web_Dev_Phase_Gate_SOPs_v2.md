# FANCY LAB — Web Development Phase-Gate SOPs (v2, Data-Enriched)

**v2.0 · April 2026 · Confidential**
**Supersedes:** `EVO_SEM_Web_Dev_Phase_Gate_SOPs.md` (v1.0, Feb 2026).
**Source of truth for each phase:** the individual `P0…P10_*_vN.md` files. This document **merges their canonical sections** (Purpose, RACI, Deliverables, Tools, Process Steps, Phase Gate) and layers in **data enrichment** derived from the ClickUp workspace export `data/8519953gHWPiybO.csv` (2,304 tasks, 84 lists, 2020-11-02 → 2026-04-22).

Key differences vs. the v1 consolidated doc:

| # | Change |
|---|---|
| 1 | Branding corrected to **Fancy Lab** throughout (v1 said "EVO SEM") |
| 2 | Phase numbering aligned to current filenames: **P0–P10** (11 phases; v1 had 10 and was missing Project Setup) |
| 3 | New phase **P3 Project Setup** included; old P3+ shifted down one |
| 4 | Each phase now has a **§ Data Enrichment** section with real counts + examples |
| 5 | New Part II: **Portfolio Health, Team Load, SOP Gap Analysis, Recommended SOPs** — all grounded in the export |

---

## Part I — Phases P0 through P10

### Table of contents

| # | Phase | Owner (R/A) | Canonical file |
|---|---|---|---|
| [P0](#p0--discovery--sales) | Discovery & Sales | Harry + Rinaldo | `P0_Discovery_Sales_SOP_v2.md` |
| [P1](#p1--client-onboarding) | Client Onboarding | Carlos | `P1_Client_Onboarding_SOP_v2.md` |
| [P2](#p2--project-specification) | Project Specification | Asya + Aida | `P2_Project_Specification_SOP_v2.md` |
| [P3](#p3--project-setup) | Project Setup | Aida | `P3_Project_Setup_SOP_v3.md` |
| [P4](#p4--design) | Design | Aida | `P4_Design_SOP_v3.md` |
| [P5](#p5--inventory) | Inventory | Asya | `P5_Inventory_SOP_v2.md` |
| [P6](#p6--development) | Development | Narine + Ishkhan (A: Asya) | `P6_Development_SOP_v2.md` |
| [P7](#p7--testing--qa) | Testing & QA | Manuk (A: Asya) | `P7_Testing_QA_SOP_v4.md` |
| [P8](#p8--client-review--pre-launch) | Client Review & Pre-Launch | Carlos (A: Rinaldo) | `P8_Client_Review_Pre_Launch_SOP_v2.md` |
| [P9](#p9--launch) | Launch | Narine + Ishkhan (A: Asya) | `P9_Launch_SOP_v2.md` |
| [P10](#p10--post-launch) | Post Launch | Carlos + Asya (A: Rinaldo) | `P10_Post_Launch_SOP_v2.md` |

---

## P0 — Discovery & Sales

**Purpose.** Standard process for the initial sales engagement, project scoping, proposal delivery, and payment processing for every new web development project. Ensures every project begins with a clear agreement on scope, deliverables, timelines, and costs before any work commences.

**Phase Objective.** Secure a signed contract and deposit payment, establish a clear project brief that defines scope boundaries, and ensure all billing and accounting records are properly set up before transitioning to client onboarding.

### WHO — RACI

| Role | Person(s) | Responsibility |
|---|---|---|
| Responsible | Harry + Rinaldo | Performs the work for this phase |
| Accountable | Harry + Rinaldo | Ultimately answerable for completion |
| Consulted | Harry + Rinaldo | Provides input and approves deliverables |
| Informed | Harry + Rinaldo | Kept up to date on progress |

### WHAT — Deliverables

| Deliverable | Format / Location | Owner |
|---|---|---|
| Discovery Meeting Notes | Google Docs / Drive | Harry + Rinaldo |
| Project Brief / Strategy | Google Docs / Drive | Harry + Rinaldo |
| Proposal Document | PandaDoc | Harry + Rinaldo |
| Signed Contract | PandaDoc | Harry + Rinaldo |
| Deposit Invoice + Payment Confirmation | Accounting System | Harry + Rinaldo |
| Welcome Email | Email | Harry + Rinaldo |

### WHERE — Tools

Google Meet · Google Drive · PandaDoc · Slack · ClickUp.

### HOW — Process Steps

1. Schedule Discovery Meeting
2. Conduct Discovery Meeting
3. Create Project Brief / Strategy
4. Prepare and Send Proposal
5. Negotiate and Finalize Contract
6. Process Deposit Payment
7. Send Welcome Email + Next Steps
8. Notify Internal Team

### Phase Gate — Completion Checklist

1. Discovery Meeting completed and notes documented in Drive
2. Project Brief / Strategy document created and stored
3. Proposal sent to client via PandaDoc
4. Client has signed the contract
5. Deposit payment received and confirmed
6. Welcome Email sent to client with next steps
7. Internal team notified via Slack with project details
8. ClickUp project record created
9. Task marked as completed in ClickUp
10. Project Brief Template (Appendix A of `P0_..._v2.md`) fully completed

### § Data Enrichment (from ClickUp export)

- **Signal of phase completion in the export:** the checklist items `Client Signed Contract` (34 occurrences) and `Client Paid Deposit` (34) appear across onboarding tasks in lists like `Steindiamonds.com`, `hawaiilabgrown.com`, `anglodiamond.com`, `christopher-salon.com`. Reading at face value, ~34 projects have cleared the P0 gate in the observed window.
- **Gap vs. SOP.** The SOP mentions "ClickUp project record created" at step 8, but the dataset shows the project's ClickUp list is typically opened *during onboarding*, not at contract signing. The v1 SOP already names this as a gate requirement — enforcement is the issue.
- **Risk — proposal stall.** The v1 escalation says "Client unresponsive after 10 business days → archive opportunity." Nothing in the dataset tells us archival is happening; consider a `BACKLOG` folder subtag like `proposal-archived` to make this auditable.

---

## P1 — Client Onboarding

**Purpose.** Transition a signed client into an active project by establishing working relationship, communication expectations, feedback processes, approval authority, asset handoff, and technical access verification — while preparing the internal team with all context needed for P2.

**Phase Objective.** Establish the complete working relationship with the client — including communication expectations, feedback processes, approval authority, asset handoff, and technical access verification — while simultaneously preparing the internal team with all context and design-specific inputs needed to begin high-quality work immediately in P2.

### WHO — RACI

| Role | Person(s) | Responsibility |
|---|---|---|
| Responsible | Carlos | Performs the work for this phase |
| Accountable | Carlos | Ultimately answerable for completion |
| Consulted | Rinaldo | Provides input and approves deliverables |
| Informed | Harry | Kept up to date on progress |

### WHAT — Deliverables (abridged; full list in `P1_..._v2.md`)

Welcome Email with preparation checklist · Onboarding Presentation Deck · Meeting Recording · Completed Intake Form · Brand Asset Package · Access & Credential Verification Log · Communication Cadence Agreement · Content Readiness Assessment · Existing Site Audit (if migration) · Internal Team Brief · Timeline Confirmation Email.

### WHERE — Tools

Google Meet · Google Drive · Google Slides · Google Sheets · Email · Slack · Google Analytics · Google Search Console · Google PageSpeed Insights.

### HOW — Process Steps

1. Send Welcome Email with Preparation Checklist
2. Schedule and Prepare Onboarding Meeting
3. Conduct Onboarding Meeting
4. Establish Communication Expectations
5. Collect and Verify Brand Assets
6. Gather Design-Specific Inputs
7. Assess Content Readiness
8. Verify Technical Access and Credentials
9. Audit Existing Site Data (Migrations Only)
10. Document Client Expectations and Working Style
11. Prepare Internal Team
12. Review Project Brief with Client and Finalize
13. Send Project Timeline Confirmation and Close Phase

### Phase Gate — Completion Checklist (24 items)

Full checklist in `P1_Client_Onboarding_SOP_v2.md`. Highlights: welcome email, onboarding meeting, communication SLAs, approval authority mapping, brand assets verified, domain/hosting/GA/GSC access verified, content readiness assessed, internal Slack channel created, project timeline confirmation email sent, intake form fully completed.

### § Data Enrichment

- **Carlos's load is consistent with him owning P1.** 184 total tasks assigned, 59 still open — a healthy active-vs-closed ratio. He also authors a large share of the onboarding-related comments.
- **Recurring onboarding checklist fingerprint** (observed in ClickUp checklists, occurring ~34–39× each): `Client Paid Deposit`, `Client Signed Contract`, `Setup Launch Meeting`, `Setup Marketing Success Call`, `Ascend Proposals to Marketing`, `Weekly Support Follow Ups`, `Mark Task as Completed and notify on Slack`. Several of these (e.g., `Setup Launch Meeting`, `Ascend Proposals to Marketing`, `Weekly Support Follow Ups`) sit across the P1/P9/P10 seams — they're being tracked in onboarding-style lists rather than launch/post-launch ones. Consider splitting this mega-checklist into three phase-scoped templates.
- **Gap — access verification drift.** Many client lists have stuck tasks referring to `add residential liftgate`, `Bank Wants the Following`, `https://…` link fixes that imply credentials were never fully captured upfront; re-enforce gate items #11–#16 (registrar, hosting, GA, GSC, payment, email).

---

## P2 — Project Specification

**Purpose.** Technically initialize a new project — create the project workspace, stand up Figma/Shopify/ClickUp infrastructure, get client sign-off on a requirements document and roadmap.

**Phase Objective.** Set up all technical project infrastructure (ClickUp, Figma, Shopify/platform), create and get client approval on the project requirements document and roadmap, and ensure the full team is aligned on deliverables, timeline, and responsibilities.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Asya + Aida |
| Accountable | Asya + Aida |
| Consulted | Rinaldo + Carlos |
| Informed | Harry |

### WHAT — Deliverables

ClickUp Project Workspace (Asya) · Figma Project File (Aida) · Platform/Shopify Dev Store (Asya) · Project Requirements Document (Asya + Aida) · Project Roadmap with Milestones (Asya) · Kickoff Email to Client (Asya) · Internal Kickoff Summary (Asya).

### WHERE — Tools

ClickUp · Figma · Shopify / WordPress / Custom CMS · Google Drive · Google Meet · Slack · Email.

### HOW — Process Steps

1. Create ClickUp Project Workspace
2. Set Up Figma Project File
3. Configure Development Platform
4. Draft Project Requirements Document
5. Build Project Roadmap and Milestones
6. Internal Kickoff Meeting
7. Client Requirements Review
8. Send Kickoff Confirmation Email
9. Finalize and Notify Team

### Phase Gate — Completion Checklist

1. ClickUp project workspace created with full task structure
2. Figma project file created with proper page structure
3. Development store/staging environment configured
4. Project Requirements Document drafted and client-approved
5. Project Roadmap with milestones created in ClickUp
6. Internal kickoff meeting conducted with all team members
7. Client sign-off on requirements and timeline received
8. Kickoff Confirmation Email sent to client
9. All team members assigned and notified in Slack
10. All project links documented (ClickUp, Figma, Dev Store, Drive)

### § Data Enrichment

- **84 ClickUp lists** in the workspace, mostly client domains — consistent with "one list per project." A handful are cross-client ops: `DAILY STAND UP` (15), `EOD Report` (5), `Inventory Management` (34), `DIAMOND SEARCH` (6), `RING BUILDER` (56), `TICKETS` (10), `Kirk Kara Tickets Tracking` (10). These are legitimate but **not named in the P2 SOP** — recommend an explicit "ops lists" registry maintained alongside client lists.
- **Tag hygiene is poor at kickoff.** Only 10 distinct tags are in use across 2,304 tasks (top: `development` 187 · `inventory` 30 · `qa` 29 · `seo` 27 · `design` 23 · `iframe` 22). Add "Create tag taxonomy on kickoff" as Step 1.5 — standardized tags at kickoff would unlock cross-phase analytics later.
- **Asya is already central to this phase in practice** — 131 tasks, 53 open; Aida 246 tasks, 123 open. Aida's 123-open load suggests Aida is the upstream bottleneck (P3 + P4); see Part II for the remediation suggestion.

---

## P3 — Project Setup

**Purpose.** Plan, create, and approve all content (copy, CTAs, meta data, image direction, content map) before design and development.

**Phase Objective.** Deliver a complete, client-approved content package — including page copy, CTAs, meta data, image direction, and content map — that the design and development teams can use without delay or ambiguity.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Aida |
| Accountable | Aida |
| Consulted | Rinaldo + Carlos |
| Informed | Harry + Asya |

### WHAT — Deliverables

Content Audit Report · SEO Keyword Research · Sitemap / Content Map · Page Copy Document · Meta Titles & Descriptions · Image & Media Direction Brief · Client-Approved Content Package.

### WHERE — Tools

Google Docs · Sheets · Drive · Ahrefs/SEMrush/Ubersuggest · ClickUp · Slack · Email.

### HOW — Process Steps

1. Conduct Content Audit
2. Perform SEO Keyword Research
3. Create Sitemap and Content Map
4. Write Page Copy
5. Draft Meta Titles and Descriptions
6. Create Image and Media Direction
7. Internal Content Review
8. Client Content Review
9. Finalize and Hand Off Content

### Phase Gate — Completion Checklist

1. Content audit completed (if existing site)
2. SEO keyword research completed and documented
3. Sitemap / Content Map created and approved
4. Page copy written for all pages in scope
5. Meta titles and descriptions drafted for all pages
6. Image and media direction documented per page
7. Internal content review completed
8. Client review completed (max 2 rounds of revisions)
9. Final content package organized in Google Drive
10. Content handed off to design team with notification
11. ClickUp content tasks marked as complete
12. Slack notification posted confirming content phase completion

### § Data Enrichment

- **The dataset barely surfaces P3 signal.** Only **27 tasks** are tagged `seo` across all 2,304 rows (1.2%). Content-authoring tasks exist (160 tasks begin with "design", 55 with "update", 81 with "add") but they're not tagged with a content/copy identifier. **Action:** add `content` and `copy` tags and require them on P3 tasks, so content-phase volume becomes measurable.
- **Aida = de-facto content + design owner.** Because both P3 and P4 list Aida as Responsible, her 123-open load (highest non-PM WIP) is a structural bottleneck. Consider co-owning P3 with a content editor or splitting "copywriting" from "SEO/content ops."
- **Comment-heavy P3 red flags.** `Update the design of PDP` (20 comments, 1800loosediamonds.com), `Update design of Collection page` (18 comments) — threads with >15 comments almost always indicate unresolved content/design scope. Triage rule: any task with >10 comments gets PM review within 48 h.

---

## P4 — Design

**Purpose.** Research, plan, and deliver the full client-approved design package (Research Wall → Sitemap → UI Kit → Wireframes → Desktop/Mobile designs → Dev handoff).

**Phase Objective.** Deliver a complete, client-approved Figma design package — Research Wall, Sitemap, UI Kit (multi-scheme colors, type scale, button states, page layouts), wireframes, and pixel-perfect desktop & mobile page designs — that the development team can implement without design ambiguity or missing assets.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Aida |
| Accountable | Aida |
| Consulted | Rinaldo + Asya + Carlos |
| Informed | Harry |

### WHAT — Deliverables

Research Wall (Figma/FigJam) · Sitemap · UI Kit (logos/fonts/colors/buttons/layout) · Wireframes · Desktop designs · Mobile designs · Section Components with Color Scheme Application · Interactive Prototype (if applicable) · Exported Assets · Design Handoff Document.

### WHERE — Tools

Figma · FigJam · Google Drive · ClickUp · Slack · Google Meet · Email.

### HOW — Process Steps

1. Review Content and Requirements
2. Create Research Wall
3. Create Sitemap
4. Develop UI Kit — Logos
5. Develop UI Kit — Typography
6. Develop UI Kit — Color Schemes
7. Develop UI Kit — Buttons & Components
8. Develop UI Kit — Page Layout
9. Create Wireframes
10. Present Wireframes to Client
11. Design Desktop Layouts
12. Design Mobile Layouts
13. Internal Design Review
14. Client Design Review
15. Prepare Design Handoff
16. Hand Off to Development

### Phase Gate — Completion Checklist (19 items)

Full list in `P4_Design_SOP_v3.md`. Highlights: Research Wall + Sitemap + UI Kit (logos, type, color schemes, buttons, layout), wireframes client-approved, desktop designs, mobile designs, section components documented, internal review signed off, **client design approval in writing**, prototype if in scope, assets exported, design handoff doc created, Figma Dev Mode enabled, ClickUp design tasks done, Slack confirm.

### § Data Enrichment

- **Design volume is material.** 160 tasks begin with the word "design"; 23 tasks carry the `design` tag explicitly. Biggest design spikes (by task count in client lists): `Steindiamonds.com` (182 total), `hawaiilabgrown.com` (162), `christopher-salon.com` (130), `erikarecords.com` (98). Each of those projects has >50 Figma-linked artifacts in the comments/attachments.
- **Design-review bottleneck is real.** 42 tasks sit in `Review` status on `hawaiilabgrown.com` alone — this is the single largest pile of Review-status work in the portfolio. Consider a time-boxed "Design Review Friday" cadence or a second reviewer for Aida.
- **SOP already addresses design-token discipline** (P4 v2). The dataset validates why: `Update the design of PDP` (1800loosediamonds) and `Update design of Collection page` both collected 15–20 comments — exactly the class of issue token/spec discipline prevents.

---

## P5 — Inventory

**Purpose.** Collect, organize, format, import, and validate the product catalog.

**Phase Objective.** Deliver a complete, validated product/service catalog with all required data fields (titles, descriptions, images, pricing, variants, categories, tags, metadata) imported into the target platform and verified for accuracy.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Asya |
| Accountable | Asya |
| Consulted | Rinaldo + Carlos |
| Informed | Harry + Aida |

### WHAT — Deliverables

Product Data Template · Completed Product Data Sheet (client-filled) · Category & Tag Taxonomy · Product Image Inventory · Import Validation Report · Platform Product Catalog (imported).

### WHERE — Tools

Google Sheets · Drive · Shopify / WooCommerce / CMS · ClickUp · Slack · Email · Matrixify / WP All Import / native importers.

### HOW — Process Steps

1. Send Product Data Template
2. Collect Product Data from Client
3. Build Category and Tag Taxonomy
4. Collect and Organize Product Images
5. Format and Validate Data
6. Import Products to Platform
7. Validate Imported Data
8. Fix Issues and Finalize

### Phase Gate — Completion Checklist

1. Product data template sent to client
2. All product data received and validated
3. Category and tag taxonomy created and applied
4. Product images collected, optimized, and organized
5. Products successfully imported to platform
6. Import validation completed (min 20% spot-check)
7. All data issues identified and resolved
8. SEO metadata verified for all products
9. Variant and option configurations validated
10. PM sign-off on final product catalog
11. ClickUp inventory tasks marked as complete
12. Slack notification posted confirming inventory phase completion

### § Data Enrichment

- **Dedicated ops list exists.** `Inventory Management` list has 34 tasks (14 Completed, 12 Open, 2 Backlog, 4 In Progress, 2 Client Approval) — 41.2 % completion, health **yellow**.
- **Inventory is a persistent post-launch topic, not one-off.** The `inventory` tag shows up 30× across tasks — but many of those live in *client-domain* lists, not in the central `Inventory Management` list. That means inventory work is being tracked in two places; fragmenting it makes reporting unreliable.
- **Representative stuck example:** `868hxpjwv — Correct mm information in the product description and search functionality` on `watchcollectorsllc.com` (Open since 2026-03-17). The same pattern ("fix data for all watches with X diameter") recurs across `beverlyhillswatch.com`, `Steindiamonds.com`, and `sellmewatch.com` — evidence that **diamond/watch-vendor feed validation** deserves its own sub-SOP under P5.
- **Recommended checklist add** (from the data): "Run vendor-feed diff between last import and current feed; flag any SKUs where diameter / carat / material mismatch."

---

## P6 — Development

**Purpose.** Build the approved website on the target platform, wire content + product data, integrate third-party services, and hand off to QA.

**Phase Objective.** Deliver a fully functional website that accurately implements approved designs, incorporates all content and product data, integrates required third-party services, and is ready for QA testing.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Narine + Ishkhan |
| Accountable | Asya |
| Consulted | Rinaldo + Aida |
| Informed | Harry + Carlos |

### WHAT — Deliverables

Functional Dev Site · Development Checklist · Third-Party Integration Documentation · SEO Technical Implementation Report · Performance Optimization Report · Dev→QA Handoff.

### WHERE — Tools

Shopify / WordPress / Custom Platform · Figma (Dev Mode) · VS Code · GitHub · ClickUp · Slack · Google PageSpeed Insights · BrowserStack.

### HOW — Process Steps

1. Development Sprint Planning
2. Build Global Elements
3. Build Page Templates
4. Implement E-Commerce Features
5. Integrate Third-Party Services
6. Implement SEO Technical Requirements
7. Performance Optimization
8. Cross-Browser and Device Testing (Dev QA)
9. Development Handoff to QA

### Phase Gate — Completion Checklist (12 items)

1. All page templates built and matching Figma designs
2. Responsive layouts verified (desktop, tablet, mobile)
3. All content populated from approved content package
4. E-commerce functionality working (if applicable)
5. All third-party integrations configured and functional
6. SEO technical implementation complete (schema, sitemap, redirects)
7. Performance optimization completed (PageSpeed targets met)
8. Developer cross-browser testing completed
9. All ClickUp development tasks marked as complete
10. Third-party integration documentation created
11. Staging URL shared with QA team
12. Slack notification posted confirming development phase completion

### § Data Enrichment

- **`development` is by far the top tag** (187 tasks). Dev volume is highest on `hawaiilabgrown.com` (54 In-Progress tasks — more than any other list) and `Steindiamonds.com` (22 In-Progress).
- **Ishkhan is the dev-side bottleneck.** 196 total tasks, **122 open** (tied for 2nd-highest open WIP in the entire org). Juan FancyLab (220 total, 184 open) and Luis Grosso (198/154) also sit primarily in dev territory. Recommend a WIP limit per developer (e.g., max 20 concurrent open tasks) — Ishkhan is 6× that now.
- **Third-party integration is the top comment-heavy theme.** `Integrate Frederick Goldman Inventory via BOSS Logics API - Artcarved & Triton` (breadiamonddirect.com) has appeared twice with 8 comments each — duplicate task evidence that the team is re-creating tickets when stuck. Add a "check for existing open duplicate by SKU/endpoint name" step to sprint planning.
- **iframe-tag cluster.** 22 tasks tagged `iframe` — specific enough to warrant an **iframe-integration micro-SOP** (Diamond Search, Ring Builder, Nivoda, MyDiamonds use iframes heavily).

---

## P7 — Testing & QA

**Purpose.** Systematically test the website for functional, design, performance, and accessibility issues, with an emphasis on pre-QA developer self-review, design-token verification, and link audits to compress QA cycle time.

**Phase Objective.** Deliver a thoroughly tested, bug-free website that meets all design specifications, functional requirements, performance benchmarks, and accessibility standards — ready for client review with confidence.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Manuk |
| Accountable | Asya |
| Consulted | Narine + Ishkhan + Aida |
| Informed | Rinaldo + Harry |

### WHAT — Deliverables

Pre-QA Developer Self-Review Checklist · QA Test Plan · Link Map & Audit Report · Bug Report Log (Pastel + ClickUp) · Visual QA Comparison (Figma overlay) · Cross-Browser Test Results · Performance Test Results · SEO Validation Checklist · QA Sign-Off Report.

### WHERE — Tools

Pastel · ClickUp · Figma · BrowserStack/LambdaTest · PixelPerfect · PageSpeed Insights / Lighthouse · Google Search Console · Screaming Frog / Sitebulb · WAVE / axe DevTools · Slack.

### HOW — Process Steps (20)

1. Verify Pre-QA Developer Self-Review
2. Create QA Test Plan
3. Spacing & Layout Audit
4. Navigation & Link Audit
5. Buttons & CTAs Audit
6. Shopify-Specific Audit
7. Design Fidelity Check (Figma Match)
8. Section & Component Management Check
9. Visual QA (Comprehensive)
10. Functional Testing
11. Responsive Testing
12. Cross-Browser Testing
13. E-Commerce Testing
14. Third-Party Integration Testing
15. SEO Validation
16. Performance Testing
17. Accessibility Testing
18. Footer, Header & Multi-Language Check
19. Bug Fixing Cycle
20. QA Sign-Off

### Phase Gate — Completion Checklist (23 items)

Full list in `P7_Testing_QA_SOP_v4.md`.

### § Data Enrichment

- **QA templating already exists in the data.** 31 tasks contain the checklist items `Create Pastel Dashboard`, `Client training and tutorial on how to use Pastel`, `Product Detail Checklist`, `Product Collection Checklist`, `Header & Navigation Checklist`, `Footer Checklist`, `Homepage Checklist`, `Additional Pages Checklist`, `Shopping Cart and Checkout checklist`, `Transactional E-mails checklist`. These exactly match `P7_Testing_QA_SOP_v4.md`. **P7 is the most faithfully executed SOP in the portfolio** — treat it as the reference model.
- **Manuk owns QA in practice.** 155 tasks total, 54 open — healthy ratio. The `qa` tag is used on 29 tasks; narrower than expected, suggests QA work is mostly identified by *list position* (inside dev lists) rather than tagged.
- **Bug-fix cycle (step 19) is the typical stall point.** 42 Review-status tasks on `hawaiilabgrown.com` and 7 Review-status tasks on `ian.club` are effectively "waiting on bug fix to re-QA." Add an SLA: bugs in Review > 5 business days auto-escalate to Asya.

---

## P8 — Client Review & Pre-Launch

**Purpose.** Present the completed website, collect + resolve in-scope client revisions, and obtain formal launch authorization.

**Phase Objective.** Obtain written client approval on the completed website, resolve all client-requested revisions within the contracted scope, and secure formal launch authorization before proceeding to the launch phase.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Carlos |
| Accountable | Rinaldo |
| Consulted | Asya + Aida + Narine |
| Informed | Harry |

### WHAT — Deliverables

Client Review Guide · Staging Site Access · Client Feedback Log · Revision Implementation Report · Known Issues Disclosure · Formal Client Sign-Off Document.

### WHERE — Tools

Google Meet · ClickUp · PandaDoc / Google Docs · Slack · Email · Loom (optional).

### HOW — Process Steps

1. Prepare Client Review Package
2. Send Staging Access to Client
3. Conduct Client Walkthrough Meeting
4. Collect and Categorize Client Feedback
5. Implement Approved Revisions
6. Conduct QA on Revisions
7. Final Client Walkthrough
8. Obtain Formal Sign-Off
9. Notify Team of Launch Readiness

### Phase Gate — Completion Checklist

1. Client Review Guide sent with staging access
2. Client walkthrough meeting conducted
3. All client feedback collected and categorized
4. Out-of-scope items communicated (Change Orders if applicable)
5. All approved revisions implemented
6. QA on revisions completed (no new Critical/High bugs)
7. Final client walkthrough conducted
8. Known issues disclosed and accepted by client
9. Formal written client sign-off received
10. Launch Approval document signed
11. ClickUp tasks updated to launch-ready status
12. Slack notification posted confirming client approval and launch readiness

### § Data Enrichment

- **`client approval` status has 84 tasks**, unevenly distributed: `Select Dental` 14 · `Steindiamonds.com` 8 · `breadiamonddirect.com` 8 · `ian.club` 7 · `divinitymetals.com` 6 · `naimies.com` 6 · `OverstockCellars.com` 4 · `christopher-salon.com` 2 · others. The fact that 7/8 of `breadiamonddirect.com`'s non-completed tasks are in client approval but the list has **0% completion** is the single clearest bottleneck in the portfolio — clients are receiving approval packages but not returning sign-off.
- **Oldest "client approval" items are 400+ days old.** This is a hard escalation trigger that v1 P8 doesn't quantify — add: "Client Approval > 30 days → PM escalation; > 90 days → Rinaldo decision on parking the project."

---

## P9 — Launch

**Purpose.** Deploy the approved website to production with minimal downtime, verify technical configuration, and hold the monitoring watch for 24–48 h.

**Phase Objective.** Execute a smooth, zero-downtime (or minimal-downtime) launch that transitions the site from staging to production, with all technical configurations verified and a monitoring plan in place.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Narine + Ishkhan |
| Accountable | Asya |
| Consulted | Rinaldo |
| Informed | Harry + Carlos + Client |

### WHAT — Deliverables

Pre-Launch Checklist · DNS Configuration Record · SSL Verification Report · Post Launch Verification Report · Redirect Verification Report (if migration) · Launch Notification Email · Post Launch Monitoring Log.

### WHERE — Tools

Platform admin · Domain registrar · Google Search Console · Google Analytics · Screaming Frog / Sitebulb · GTmetrix / PageSpeed Insights · ClickUp · Slack · Email.

### HOW — Process Steps

1. Complete Pre-Launch Checklist
2. Schedule Launch Window
3. Backup Current Site (if migration)
4. Configure DNS
5. Verify SSL Certificate
6. Deploy to Production
7. Implement and Verify Redirects
8. Post-Deployment Verification
9. Submit to Search Engines
10. Send Client Launch Notification
11. Monitor for 24-48 Hours

### Phase Gate — Completion Checklist (15 items, canonical in `P9_..._v2.md`)

### § Data Enrichment

- **Launch is the most templated phase in the data.** Checklist items recurring **39×** across tasks: `Setup Launch Meeting`, `Website Launch Checklist`, `Send Client Knowledge Base / Pastel / Support Email`, `Give client 1 month free of Base Plan`, `Setup Marketing Success Call`. Read at face value, **≥39 launches have been run** in the observed window; the SOP reflects actual practice.
- **Cross-phase leak.** `Give client 1 month free of Base Plan` is a **commercial hand-off into an ongoing support engagement**, but it's tracked in the launch checklist. This should move into P10 (or a new "P11 — Ongoing Support Onboarding") so launch-phase reporting isn't polluted by long-term subscription admin.
- **No visible launch rollback log** in the data. Add: "If launch-day critical issue requires rollback, log the rollback decision + rollback ID in the Monitoring Log."

---

## P10 — Post Launch

**Purpose.** Deliver training, resolve post-launch issues, finalize documentation, run an internal retrospective, and either close the project or transition to a maintenance agreement.

**Phase Objective.** Deliver comprehensive client training, resolve any post-launch issues, finalize all project documentation, conduct an internal retrospective, and formally close the project or transition to an ongoing maintenance agreement.

### WHO — RACI

| Role | Person(s) |
|---|---|
| Responsible | Carlos + Asya |
| Accountable | Rinaldo |
| Consulted | Narine + Aida |
| Informed | Harry |

### WHAT — Deliverables

Client Training Session (recorded) · Website Admin Guide · Credentials & Access Document · Integration Documentation · 30-Day Analytics Report · Internal Retrospective Notes · Project Closure Report · Maintenance Agreement (if applicable) · Client Satisfaction Survey.

### WHERE — Tools

Google Meet · Drive · Google Analytics · Google Search Console · ClickUp · PandaDoc · Slack · Loom (optional) · Email.

### HOW — Process Steps

1. Address Post Launch Issues
2. Schedule and Conduct Client Training
3. Create Website Admin Guide
4. Compile Credentials and Access Document
5. Document Integrations and Technical Setup
6. Generate 30-Day Analytics Report
7. Conduct Internal Retrospective
8. Prepare Project Closure Report
9. Present Maintenance Agreement (if applicable)
10. Send Client Satisfaction Survey
11. Formal Project Closure

### Phase Gate — Completion Checklist (14 items, canonical in `P10_..._v2.md`)

### § Data Enrichment

- **P10 is only a small slice of actual post-launch reality.** The `SUPPORT` folder in ClickUp has **262 tasks**, and the checklist item `Weekly Support Follow Ups` recurs **42×** — i.e., the team is doing ongoing support that extends well beyond P10's 90-day warranty concept. There is **no SOP covering this ongoing support mode**.
- **`MARKETING` folder has 303 tasks** — these look like post-launch marketing work (likely the handoff the launch checklist calls `Ascend Proposals to Marketing`) but there's no SOP defining the boundary between P10 and marketing handover.
- **MAGENTO folder (3 tasks) exists** but no Magento work appears in the SOPs — either a dead folder or a one-off that should be merged into SUPPORT.
- **Oldest open tasks in the export are post-launch remediation.** `1800loosediamonds.com` has tasks open since 2020 ("Each product should be its own sku," 1,998 days). These clearly exceeded P10 scope; they belong in a long-term support backlog with explicit aging SLAs.

---

# Part II — Portfolio Snapshot, Team Load, and Gaps (from ClickUp export)

## II.A — Portfolio Snapshot

**Totals:** 2,304 tasks · 84 lists · 80+ client domains · 5.5-year span.

**Throughput trend (tasks created per quarter).** Volume exploded in the last year: 2025-Q3 = 284, 2025-Q4 = 135, **2026-Q1 = 856**, **2026-Q2 = 706** (partial). The org is moving ~10× the ticket volume it did 18 months ago.

**Completion throughput (completed in same period):** 2025-Q3 = 115, 2025-Q4 = 20, **2026-Q1 = 419**, 2026-Q2 = 158 (partial). Completion is growing but is outpaced by creation — aging WIP is increasing.

**Aging WIP (non-completed tasks, by age):**

| Bucket | Tasks |
|---|---|
| 0–30 days | 624 |
| 31–90 | 277 |
| 91–180 | 192 |
| 181–365 | 250 |
| **365+ days (stale)** | **113** |

**Priority discipline:** 62.4 % of tasks have **no priority set**. Urgent = 250, High = 292, Normal = 291, Low = 33.

## II.B — Client Health Scorecard (≥20 tasks per list)

| List | N | Done | Open | IP | Rev | CApp | Back | % Done | Oldest Open | Health |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|:---:|
| Steindiamonds.com | 182 | 102 | 2 | 22 | 0 | 8 | 46 | 56.0 | 132d | 🟡 |
| hawaiilabgrown.com | 162 | 38 | 42 | 54 | 8 | 2 | 18 | 23.5 | 66d | 🟡 |
| christopher-salon.com | 130 | 50 | 2 | 2 | 0 | 2 | 72 | 38.5 | 216d | 🟡 |
| OverstockCellars.com | 122 | 10 | 96 | 2 | 0 | 4 | 10 | 8.2 | 21d | 🔴 |
| sweatymelons.com | 110 | 88 | 0 | 2 | 0 | 4 | 14 | 80.0 | 100d | 🟡 |
| beverlyhillswatch.com | 98 | 93 | 1 | 0 | 0 | 0 | 4 | 94.9 | 392d | 🟢 |
| erikarecords.com | 98 | 12 | 2 | 6 | 42 | 0 | 34 | 12.2 | 216d | 🔴 |
| anglodiamond.com | 74 | 16 | 38 | 0 | 0 | 2 | 18 | 21.6 | 136d | 🟡 |
| divinitymetals.com | 66 | 8 | 8 | 4 | 0 | 6 | 34 | 12.1 | 562d | 🔴 |
| barclaysjewelers.com | 65 | 1 | 55 | 1 | 0 | 3 | 2 | 1.5 | 580d | 🔴 |
| kirkkara.com | 62 | 22 | 3 | 0 | 0 | 1 | 35 | 35.5 | 993d | 🟡 |
| Select Dental | 60 | 6 | 0 | 0 | 0 | 14 | 38 | 10.0 | 78d | 🔴 |
| naimies.com | 60 | 24 | 0 | 0 | 0 | 6 | 30 | 40.0 | 36d | 🟡 |
| luxefinejewelers.com | 56 | 28 | 4 | 2 | 0 | 0 | 22 | 50.0 | 55d | 🟡 |
| RING BUILDER | 56 | 0 | 22 | 18 | 0 | 0 | 12 | 0.0 | 449d | 🔴 |
| chicaura.com | 54 | 48 | 0 | 0 | 0 | 0 | 2 | 88.9 | 216d | 🟢 |
| leadingjewelersguild.org | 47 | 14 | 5 | 0 | 0 | 0 | 24 | 29.8 | 548d | 🟡 |
| onlinetireoutlet.com | 44 | 0 | 2 | 0 | 2 | 0 | 38 | 0.0 | 745d | 🔴 |
| moderncarats.com | 43 | 37 | 2 | 0 | 0 | 0 | 4 | 86.0 | 202d | 🟢 |
| goldandgems.com | 42 | 10 | 24 | 0 | 0 | 0 | 6 | 23.8 | 276d | 🟡 |
| violetfoods.com | 40 | 28 | 2 | 0 | 0 | 0 | 8 | 70.0 | 217d | 🟡 |
| diamondanddesign.com | 38 | 36 | 2 | 0 | 0 | 0 | 0 | 94.7 | 142d | 🟢 |
| diamondstuds.com | 36 | 24 | 0 | 0 | 0 | 0 | 8 | 66.7 | 241d | 🟡 |
| Inventory Management | 34 | 14 | 12 | 4 | 0 | 2 | 2 | 41.2 | 29d | 🟡 |
| breadiamonddirect.com | 32 | 0 | 4 | 0 | 0 | 8 | 12 | 0.0 | 862d | 🔴 |
| feyjewelers.com | 32 | 6 | 2 | 0 | 2 | 0 | 22 | 18.8 | 464d | 🔴 |
| bey-berk.com | 32 | 14 | 6 | 0 | 0 | 0 | 8 | 43.8 | 216d | 🟡 |
| watchcollectorsllc.com | 30 | 26 | 2 | 0 | 0 | 0 | 0 | 86.7 | 216d | 🟢 |
| ian.club | 28 | 2 | 12 | 1 | 4 | 7 | 1 | 7.1 | 457d | 🔴 |
| rhythmrocks.com | 22 | 0 | 0 | 0 | 0 | 0 | 20 | 0.0 | 216d | 🔴 |
| diamantaireimports.com | 20 | 0 | 2 | 0 | 0 | 0 | 18 | 0.0 | 216d | 🔴 |

**Takeaways:**

- **8 client lists are red** (≥10 tasks, <20 % done). 4 of them have **zero completions** at all (`RING BUILDER`, `onlinetireoutlet.com`, `breadiamonddirect.com`, `rhythmrocks.com`, `diamantaireimports.com`). Triage: confirm each is (a) actively billed, (b) parked, or (c) abandoned — then archive the parked ones.
- **`beverlyhillswatch.com`, `chicaura.com`, `diamondanddesign.com`, `moderncarats.com`, `watchcollectorsllc.com`** are the green lights — use as templates for what a "completed" list should look like at closeout.
- **`hawaiilabgrown.com` has 54 In-Progress tasks and 42 in Review** — that's one list holding 43 % of all In-Progress work in the company. Merits a dedicated sprint meeting.

## II.C — Team Load Snapshot

| Person | Total | Open | Ratio |
|---|---:|---:|---:|
| Juan FancyLab | 220 | 184 | 84% open |
| Rinaldo | 227 | 161 | 71% |
| Luis Grosso | 198 | 154 | 78% |
| Aida | 246 | 123 | 50% |
| Ishkhan Ghukasyan | 196 | 122 | 62% |
| Jason Van Hil | 154 | 72 | 47% |
| Carlos Castaneda | 184 | 59 | 32% |
| Manuk Navasardyan | 155 | 54 | 35% |
| Asya | 131 | 53 | 40% |
| Johanna | 20 | 18 | 90% |
| Miguel Soler | 16 | 16 | 100% |
| Harry Kabadaian | 12 | 12 | 100% |

**Observations.**

- **Juan FancyLab, Luis Grosso, and Ishkhan Ghukasyan** are the most backed-up (184 / 154 / 122 open). None of them appear in any P0–P10 RACI. **Either the SOP roster is out of date or these contributors are specialists whose work flows in sideways.** Update the RACI matrices to reflect them explicitly.
- **Carlos, Manuk, and Asya** (the three people named Responsible on the most SOPs) have healthy ratios (<40 % open). This validates that the SOPs are being followed on their turf.
- **Rinaldo is personally carrying 161 open tasks** (2nd highest). For an owner, that's a sign of "doer-in-chief" gravity; if the goal is to scale the team, delegating ~50 of those tasks would be the single biggest lever.

## II.D — SOP Gap Analysis

Comparing the dataset to the 11 phase SOPs:

| Observation | Phase(s) it touches | Gap in SOP? |
|---|---|---|
| 262 tasks in `SUPPORT` folder (ongoing) | beyond P10 | ✅ **No SOP for ongoing support** |
| 303 tasks in `MARKETING` folder | P10 handoff | ✅ No SOP defines marketing handoff boundary |
| `RING BUILDER` list (56 tasks) | Cross-phase | ✅ No SOP for ring-builder integration lifecycle |
| `DIAMOND SEARCH` list (6 tasks) | P5 / P6 | ✅ No SOP for diamond-feed integration |
| `Inventory Management` list (34) + `inventory` tag (30) | P5 | Partial — fragmented between ops list and client lists |
| `iframe` tag (22 tasks) | P6 | ✅ No SOP for iframe-based third-party integrations |
| `DAILY STAND UP` list (15) + `EOD Report` list (5) | Team ops | ✅ No SOP for daily cadence / EOD reporting |
| `TICKETS` list (10) + `Kirk Kara Tickets Tracking` list (10) | beyond P10 | ✅ No SOP for ticket queue management |
| 62 % of tasks have no priority set | All | ✅ P2 SOP doesn't require priority setting at creation |
| Only 10 tags total across 2,304 tasks | All | ✅ P2 SOP doesn't define a tag taxonomy |
| 113 tasks open >365 days | All | ✅ No SOP defines aging-out / archival policy |

## II.E — Recommended New / Refined SOPs

Prioritized by data signal strength:

1. **Ongoing Support SOP (post-P10).** 262 SUPPORT tasks + `Weekly Support Follow Ups` checklist (42×) make this the single largest gap. Define: intake, triage priority, response SLA, monthly health check, quarterly renewal conversation.
2. **Marketing Handoff SOP (between P10 and Marketing).** 303 MARKETING-folder tasks + `Ascend Proposals to Marketing` checklist (42×). Define the exact deliverable bundle handed from Web Dev → Marketing and the accountability transfer.
3. **Diamond Search / Ring Builder / Iframe Integration micro-SOPs (under P6).** 56 RING BUILDER + 6 DIAMOND SEARCH + 22 iframe-tagged tasks. These integrations have repeat failure modes (see `868j2g54k Wishlist Functionality Missing...`); capturing them in a dedicated micro-SOP would compress cycle time materially.
4. **Inventory Sub-SOP — Vendor Feed Validation (under P5).** 30 inventory-tagged tasks + recurring "fix mm / fix carat / fix diameter" pattern. Define: feed diff on import, spot-check protocol, feed-vendor escalation path.
5. **Daily Cadence / EOD Reporting SOP.** `DAILY STAND UP` and `EOD Report` lists exist but aren't codified. Write the 1-pager defining who posts what, where, and by when.
6. **Ticketing / Client Issue SOP.** `TICKETS` and `Kirk Kara Tickets Tracking` lists are currently client-specific workarounds. A generic client-ticket SOP would let this pattern scale.
7. **Aging / Archival Policy (cross-cutting).** 113 tasks >365 days and 250 tasks 181–365 days. Add: "Any open task >180 days auto-routes to a weekly PM review list; >365 days triggers an archive/delete decision."
8. **Priority & Tag Hygiene Enforcement (addendum to P2).** Require priority on creation; define 10–15 canonical tags; ClickUp automation to flag untagged tasks.

## II.F — Analyses Worth Running Next

Things the export alone can't answer but are reachable:

- **Per-status duration via ClickUp API** (`clickup_get_bulk_tasks_time_in_status`) — would give real cycle-time per phase.
- **Comment sentiment** across the 1,282 comments — flag at-risk client relationships.
- **Estimate-vs-actual** calibration once estimation becomes a habit (today only 52/2,304 = 2.3 % of tasks have estimates).
- **Pastel ↔ ClickUp reconciliation** — does every Pastel bug map to a ClickUp bug? Currently unknown.
- **Billing cross-reference** — time spent per client × hourly rate vs. contracted scope (profitability proxy).
- **Repository of "golden launches"** — pick the 5 healthiest client lists and codify their task template as the canonical kickoff pattern.

---

## Appendix — Where to find the supporting data

All derived artifacts are in `/Users/melo/pm-phases/data/analysis/`:

- `cleaned_tasks.csv` — flat, normalized one-row-per-task table
- `normalized/{assignees,tags,comments,checklists,attachments}.csv` — long-format relational tables
- `insights.json` — the machine-readable insight payload driving Part II
- `phase_structures.json` — cached canonical sections extracted from each P0–P10 file
- `build_analysis.py` — re-run to regenerate everything

*Regenerate with:* `python3 data/analysis/build_analysis.py`

---

*Prepared by the Web Development analytics workstream · data cutoff 2026-04-22.*
