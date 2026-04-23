**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P3**

**PROJECT SETUP**

Standard Operating Procedure & Phase Gate Document

v3.0 \| April 2026 \| Confidential

**REVISION HISTORY**

- **v3.0 (April 2026) — Full rewrite. Phase renamed from "Content Strategy & Copywriting" to "Project Setup".** Driven by the team decision that content authoring, copywriting, and SEO keyword strategy are **not** services Fancy Lab delivers — the client supplies their own copy, imagery, brand assets, and product data. P3's job is therefore to (a) provision every technical environment, tool, and credential the project needs and (b) ingest, organize, and quality-check client-provided content so that P4 — Design can begin on a fully provisioned project with all assets in place. The old content-strategy scope (SEO keyword research, page-by-page copywriting, meta authoring) is removed entirely — it is neither in Fancy Lab's remit nor reflected in the ClickUp export; only 27 of 2,304 workspace tasks carry the `seo` tag, and there is no copywriting queue in practice.
- **v3.0 — Scope handed upstream & downstream.** ClickUp project-list creation stays in **P1 — Client Onboarding** (v2, Step 11). P3 does not re-open the list; it extends it by applying the canonical tag taxonomy and priority-hygiene automations defined in **P2 — Project Specification** (v2, Steps 1.5 and 5.5). Client-content review and approval live in **P4 — Design**; P3 is ingestion-and-organization only.
- **v3.0 — Out-of-scope escalation path added.** If during intake the client requests content authoring, copywriting, SEO writing, or content strategy, the PM must escalate to Rinaldo for an out-of-scope conversation; these are not Fancy Lab deliverables and cannot be absorbed silently. See Escalation — Blocked Phase Protocol.
- **v3.0 — Content Gap Log introduced.** New artifact that itemizes any client content that is missing, low-quality, or mis-aligned with the Project Specification. Each gap must be resolved (client delivers) or formally waived (client accepts design will proceed with placeholder / best-available asset) before the phase gate is passed.
- **v3.0 — Data Enrichment paragraph added.** The ClickUp export surfaces no direct P3 signals because the old Content Strategy phase was never faithfully executed — the setup work that actually happens between onboarding and design has historically been threaded through P2 kickoff tasks, P1 asset collection, and ad-hoc dev-store creation. Formalizing it here closes that gap.

**PURPOSE & SCOPE**

This SOP defines the standard process for preparing all technical
environments, tooling, and client-provided content so that the design
team (P4) can begin work on a fully provisioned project with every
asset in place. P3 is the bridge between the client specification
(P2) and creative execution (P4): it is the phase where everything
that "must exist" for the rest of the project to run is stood up,
credentialed, and stocked.

**Phase Objective**

Every technical system is provisioned and credentialed; every
client-provided content item (copy, imagery, brand assets, product
data) is ingested, organized in Google Drive, and quality-checked
against the P2 Project Specification; any content gap is logged and
resolved or formally waived before design begins. The P4 design team
receives a single Handoff Packet with every link, asset, and open
question accounted for.

**Scope Includes**

> \- Shopify development store creation, configuration, and password
> protection
>
> \- Staging environment provisioning and access-list management
>
> \- Repository creation (if the project requires custom theme code or
> custom app scaffolding)
>
> \- Application of the canonical tag taxonomy and priority-hygiene
> automations (per P2 — Project Specification v2) to the ClickUp
> project list (the list itself is opened in P1 — Client Onboarding
> v2; P3 does not create it)
>
> \- Pastel dashboard creation, scoped to the project, ready for later
> QA feedback in P7 — Testing & QA
>
> \- Google Drive project folder structure (standardized subfolders for
> brand assets, client content, contracts, credentials, approved
> deliverables)
>
> \- Project Slack channel creation and full team onboarding
>
> \- Access provisioning to every provisioned system for the full
> project team, captured in an Access Matrix
>
> \- Client content intake — collecting copy, imagery, brand assets,
> and product-data feeds that the client has supplied; organizing
> them in Google Drive and (for brand assets) Figma
>
> \- Quality check of client-provided content against the P2 Project
> Specification (right pages present, right formats, minimum image
> resolution, product feed field completeness)
>
> \- Content Gap Log — itemized list of missing or sub-quality items,
> with owner and resolution date
>
> \- Gap resolution — chasing the client via Carlos (P1-owned
> relationship) to deliver missing items, or obtaining a formal
> waiver
>
> \- P3 → P4 Handoff Packet — single document linking the provisioned
> environments, ingested content, Access Matrix, and Content Gap Log
> disposition, acknowledged by Aida (P4 lead) in ClickUp

**Scope Excludes**

> \- Content authoring, copywriting, SEO keyword research, content
> strategy, meta-description writing — **not a Fancy Lab service.**
> If the client requests any of these, the PM escalates to Rinaldo
> for an out-of-scope / change-order conversation; work does not
> silently expand.
>
> \- Design work of any kind (covered in P4 — Design)
>
> \- Product import, catalog ingestion, variant mapping, vendor-feed
> validation (covered in P5 — Inventory). P3 only
> confirms that the client-supplied product-data file exists and is
> machine-readable — actual import lives in P5.
>
> \- Front-end, back-end, or theme development (covered in P6 —
> Development)
>
> \- Opening the ClickUp project list (already done in P1 — Client
> Onboarding v2, Step 11)
>
> \- Credential capture / registrar access verification (already done
> in P1 — Client Onboarding, Gate items #11–#16)
>
> \- Approval authority mapping (already done in P1 — Client
> Onboarding, Gate item #5)

**WHO - RACI MATRIX**

|                 |                       |                                                                                              |
|:----------------|:----------------------|:---------------------------------------------------------------------------------------------|
| **Role**        | **Person(s)**         | **Responsibility**                                                                           |
| **Responsible** | Asya (phase lead)     | *Coordinates setup across sub-owners; owns the phase gate audit*                             |
| **Responsible** | Ishkhan / Narine      | *Shopify dev store, staging environment, repository provisioning, developer access*          |
| **Responsible** | Manuk                 | *Pastel dashboard creation and scoping*                                                      |
| **Responsible** | Carlos                | *Google Drive folder structure; client-content intake; Content Gap Log chase*                |
| **Responsible** | Aida                  | *Figma file brand-asset ingestion and organization; acknowledges the P3 → P4 Handoff Packet* |
| **Accountable** | Asya                  | *Single accountable owner for phase-gate sign-off*                                           |
| **Approved By** | Rinaldo               | *Approves the phase gate*                                                                    |
| **Consulted**   | Aida                  | *Consulted on Figma setup, content organization, and handoff readiness*                      |
| **Informed**    | Client, Harry         | *Kept up to date on progress, missing-item requests, and phase completion*                   |

*RACI notes: Asya coordinates but delegates. Per
`data/analysis/03_sop_gap_and_recommendations.md` §A, Ishkhan (196
tasks) and Narine own the dev stack, Manuk (155 tasks) owns the QA
stack including Pastel, Carlos (184 tasks) owns the client
relationship, and Aida (246 tasks) is the design-side counterpart
who receives the handoff. Asya's 131-task load matches a
coordinator-plus-auditor role.*

**WHAT - DELIVERABLES**

|                                                                    |                                           |                      |
|:-------------------------------------------------------------------|:------------------------------------------|:---------------------|
| **Deliverable**                                                    | **Format / Location**                     | **Owner**            |
| **Shopify Development Store (provisioned + configured)**           | Shopify / URL + credentials in vault      | Ishkhan / Narine     |
| **Staging Environment**                                            | Platform-specific URL + access list       | Ishkhan / Narine     |
| **Project Repository (if applicable)**                             | Git host + README                         | Ishkhan / Narine     |
| **ClickUp List — Tags + Priority Automations Applied**             | ClickUp                                   | Asya                 |
| **Pastel Dashboard (scoped + linked to ClickUp list)**             | Pastel / URL                              | Manuk                |
| **Google Drive Project Folder (with documented subfolder tree)**   | Google Drive                              | Carlos               |
| **Slack Project Channel (#proj-[clientname]) with full team**      | Slack                                     | Asya                 |
| **Access Matrix (who has access to what, with verification date)** | Google Sheets                             | Asya                 |
| **Client Content Package (organized by page / section)**           | Google Drive                              | Carlos               |
| **Figma Project File — Brand Assets Loaded**                       | Figma                                     | Aida                 |
| **Content Gap Log (resolved or waived per item)**                  | Google Sheets                             | Carlos               |
| **P3 → P4 Handoff Packet**                                         | Google Docs (linked from ClickUp)         | Asya + Aida (ack)    |

**WHERE - TOOLS & PLATFORMS**

|  |  |
|:---|:---|
| **Tool** | **Purpose in This Phase** |
| **Shopify** | Dev store + staging store provisioning; password protection; base-theme install; basic store settings (currency, timezone, taxes placeholder) |
| **ClickUp** | Apply canonical tag taxonomy + priority-hygiene automations to the project list opened in P1; track P3 tasks; host the Handoff Packet acknowledgment |
| **Pastel** | Create the project QA feedback dashboard now so P7 can begin without a setup tax |
| **Figma** | Ingest brand assets supplied by the client (logos, fonts, color tokens) into the design file so P4 starts with a stocked design environment |
| **Google Drive** | Standardized project folder tree (Brand, Client Content, Contracts, Credentials placeholder, Deliverables, Reference); primary home of the ingested client content |
| **Slack** | Project channel creation (`#proj-[clientname]`), team onboarding, ClickUp automation alert routing |
| **Google Meet** | Intake calls if content delivery requires a screenshare walkthrough (optional) |
| **Email** | Client-content chase correspondence (Carlos) — follow-ups, waivers, confirmation of delivery |
| **Secure Credential Vault** | Canonical home for every credential created or handed off during this phase (dev store admin, staging password, Pastel account, Drive share links requiring sign-in) |

**HOW - PROCESS STEPS**

> **1. Provision Shopify Development Store**
>
> Ishkhan / Narine create the Shopify development store using the
> Fancy Lab Partner account. Name it per convention (typically
> `[clientdomain]-dev.myshopify.com`). Install the base theme agreed
> in P2 (Dawn / Custom / Migration source). Configure: currency,
> timezone, measurement units, placeholder tax settings. Enable
> password protection with a documented password. Store admin URL
> and credentials in the secure credential vault; add the admin URL
> to the ClickUp project list pinned-links section.
>
> **2. Provision Staging Environment**
>
> Stand up the staging environment required by the project
> (password-protected dev storefront, themekit preview URL, or
> separate staging store depending on the project shape).
> Document the URL, password, and access expiry (if any). Build the
> initial Access List — which team members have staging access now
> and in what role (admin / developer / designer / viewer).
>
> **3. Create Project Repository (if applicable)**
>
> For projects with custom theme code or app scaffolding, create the
> Git repository under the Fancy Lab org using the naming convention
> `[clientdomain]`. Initialize the README with project summary, dev
> store URL, staging URL, branch strategy (main → staging → feature
> branches), and links back to the ClickUp list, Drive folder, and
> Figma file. Invite the assigned developers.
>
> **4. Apply ClickUp Tag Taxonomy + Priority Automations to the
> Project List**
>
> The ClickUp project list was opened in P1 — Client Onboarding
> (v2, Step 11). In this step Asya applies the canonical 15-tag
> taxonomy defined in P2 — Project Specification (v2, Step 1.5) and
> enables both priority-hygiene automations (missing-priority >24h
> Slack alert; untagged-task >24h Slack alert; see P2 v2 Step 5.5).
> Verify that the automations are routing to `#proj-[clientname]`
> and that the canonical tag Doc is linked from the project list's
> pinned-links section. Re-audit every task already present in the
> list and backfill priority + tag as needed — no task leaves this
> phase unprioritized or untagged.
>
> **5. Create Pastel Dashboard**
>
> Manuk creates the project's Pastel dashboard scoped to the staging
> URL created in Step 2. Set up reviewer permissions so that every
> team member (and, later, the client during P7 — Testing & QA) can
> comment. The dashboard is intentionally dormant now — it exists
> so P7 does not incur a setup tax mid-QA. Document the Pastel URL
> in the Access Matrix and in the ClickUp list pinned-links
> section.
>
> **6. Create Google Drive Project Folder Structure**
>
> Carlos creates (or extends, if partially created in P1) the Google
> Drive project root folder using the naming convention
> `[ClientName] — [Year]` and the standardized subfolder tree:
>
> - `00-Brief & Contracts`
> - `01-Onboarding`
> - `02-Client Content` (with sub-subfolders per page / section from
>   P2's sitemap — e.g., `/Homepage`, `/About`, `/Collections`,
>   `/Products`, `/Legal`)
> - `03-Brand Assets` (logos, fonts, colors, guidelines PDF)
> - `04-Reference` (competitor captures, inspiration)
> - `05-Credentials Pointer` (README only — actual credentials live
>   in the secure credential vault; this file points to the vault
>   entry)
> - `06-Deliverables` (populated in P4 onward)
> - `07-Handoff Packets` (each phase-gate handoff lives here)
>
> Set folder permissions: internal team Edit, client View or
> Comment.
>
> **7. Create Project Slack Channel and Onboard Team**
>
> Asya creates `#proj-[clientname]` in Slack. Adds every assigned
> team member (Carlos, Aida, Ishkhan, Narine, Manuk, Harry, Asya,
> Rinaldo). Pins a message with: Drive link, ClickUp list link,
> Figma file link, dev store URL, staging URL, Pastel URL, repo URL
> (if applicable). Confirms that ClickUp → Slack automation alerts
> (priority / tag hygiene per Step 4) are routing to this channel.
>
> **8. Grant Team Access to Every Provisioned System (Access Matrix)**
>
> Asya populates the Access Matrix (Google Sheet), one row per
> system (Shopify dev store, staging, Pastel, Figma, Drive, Slack,
> Repo, ClickUp list), one column per team member. Each cell
> records the role (admin / editor / viewer / none) and the
> verification date. Every team member is required to log in to
> each system they're marked for and confirm access by replying to
> the Access Matrix thread in Slack. Un-verified rows block the
> phase gate — historical access drift noted in P1 v2 applies
> equally here.
>
> **9. Ingest Client Content into Drive**
>
> Carlos walks the P2 — Project Specification's sitemap page-by-page
> and, for each page, collects the client-supplied copy, imagery,
> and any auxiliary content (testimonials, FAQ answers, product
> photos, lifestyle imagery, hero video). Files are renamed per
> convention (`[page]_[element]_[version].ext`) and placed in the
> correct `/02-Client Content/[page]/` subfolder. If the client has
> provided a product-data feed (CSV / XLSX / XML / API), drop it
> into `/02-Client Content/Products/` and confirm it is
> machine-readable — do **not** import it; import is P5's job.
>
> **10. Ingest Brand Assets into Figma**
>
> Aida loads the brand assets collected in P1 into the Figma project
> file: logo variants on the Assets page, color styles built from
> the confirmed hex codes, font families wired up (with license
> verified), brand photography placed on the Reference page. The
> UI Kit itself is **not** built here — that is P4's Step 3; P3
> only stocks the file so P4 can start cleanly.
>
> **11. Quality-Check Client Content Against the Project
> Specification**
>
> Carlos (content side) and Aida (brand-asset side) run a structured
> check against P2's Project Specification:
>
> - Every page in the approved sitemap has copy present (or copy is
>   marked as client-responsibility with a delivery date)
> - Every product in the spec has at least one web-ready image
>   (minimum 2000×2000 px, consistent background per the P1 intake)
> - Every brand asset in P1's inventory is present in Figma and has
>   passed license / format verification
> - Every legal page is either provided by the client or explicitly
>   delegated to Shopify auto-generated templates per P1's intake
> - The product-data file (if any) opens cleanly and its column
>   headers match the P2 spec's field list
>
> Findings go directly into the Content Gap Log (Step 12).
>
> **12. Compile the Content Gap Log**
>
> Carlos opens the Content Gap Log (Google Sheet, one row per gap)
> with columns: **Item**, **Page / Section**, **Type** (copy /
> image / asset / product data / legal), **Gap Description**,
> **Owner** (client / Fancy Lab), **Requested Date**, **Target
> Resolution Date**, **Status** (open / delivered / waived),
> **Resolution Note**. Every Step 11 finding becomes a row. The Gap
> Log is linked from the ClickUp list and from the Handoff Packet.
>
> **13. Resolve or Waive Every Gap**
>
> Carlos chases the client for each open gap via the communication
> channel agreed in P1 — Client Onboarding. Cadence: initial
> request → 3-day reminder → 5-day escalation with timeline-impact
> statement → 10-day phone call with Rinaldo copied. Each delivered
> item updates the Gap Log Status to `delivered` and is filed into
> the matching Drive subfolder. If the client cannot or will not
> deliver, Carlos secures a **written waiver** (reply-email is
> sufficient) acknowledging that design will proceed with
> placeholder content or a best-available alternative; the Status
> becomes `waived` and the waiver email is filed under
> `/00-Brief & Contracts/waivers/`. The phase cannot advance while
> any row is still `open`.
>
> **14. Out-of-Scope Escalation (if triggered)**
>
> If during Steps 9 – 13 the client requests that Fancy Lab **write**
> content (copy, SEO meta, product descriptions, etc.), Carlos
> documents the request and escalates to Rinaldo the same business
> day. Rinaldo runs the out-of-scope conversation: either the
> client pulls the request, or a Change Order is issued back
> through P0 — Discovery & Sales. P3 does not absorb authoring
> work silently, and the phase gate does not advance until the
> out-of-scope request is formally resolved.
>
> **15. Compile the P3 → P4 Handoff Packet**
>
> Asya produces a single Handoff Packet (Google Doc) at the end of
> the phase containing:
>
> - Links: Shopify dev store, staging URL, repo (if any), ClickUp
>   list, Figma file, Drive folder, Pastel dashboard, Slack channel,
>   Access Matrix
> - Summary of provisioned state (what exists, what it's scoped to)
> - Content Gap Log current state with every row resolved or waived
> - Known constraints / follow-ups flagged for P4
> - Aida's acknowledgment checkbox (as a ClickUp subtask assigned to
>   Aida)
>
> The packet lives in `/07-Handoff Packets/P3-to-P4.gdoc`. Aida
> checks off the ClickUp acknowledgment before the phase gate is
> signed.

**COMMUNICATION - STAKEHOLDER UPDATES**

|  |  |  |  |
|:---|:---|:---|:---|
| **Type** | **Frequency** | **Audience** | **Channel** |
| Internal kickoff of P3 setup | Once | Full project team | Slack (#proj-[clientname]) |
| Client-content intake request | Once at P3 open; reminders at day 3 / 5 / 10 as needed | Client | Email (Carlos) |
| Access Matrix verification call-out | Once (48 hours before gate) | Full project team | Slack |
| Content Gap Log status update | Weekly while any row is open | PM + Client | Slack (internal) + Email (client) |
| Out-of-Scope Escalation | As triggered | Rinaldo, Carlos, Client | Email + Slack |
| P3 → P4 Handoff acknowledgment | Once (at phase close) | Aida (primary), Asya (confirm) | ClickUp (subtask check-off) + Slack |
| Phase-close notification | Once | Full team + Client | Slack internal + Email to client |

**ESCALATION - BLOCKED PHASE PROTOCOL**

|  |  |  |  |
|:---|:---|:---|:---|
| **Trigger** | **Timeframe** | **Escalation Action** | **Escalated To** |
| Shopify dev store creation blocked (partner-account issue) | 1 business day | Tech-lead involvement; if unresolved in 48h, escalate to Rinaldo | Asya → Rinaldo |
| Team member cannot access a provisioned system (Access Matrix failure) | Same day | Re-issue access; if blocked >24h, escalate to Asya for manual resolution | Sub-owner → Asya |
| Client has not delivered any content 5 business days after request | 5 business days | Send specific missing-items checklist with timeline-impact statement | Carlos |
| Client still not delivering after first follow-up | 10 business days | Phone call from Rinaldo; formalize timeline slip; require written waiver OR delivery plan | Rinaldo |
| Content Gap Log row cannot be resolved and client refuses to waive | Any point | Pause P3 gate; escalate to Rinaldo for commercial conversation (Change Order or scope reduction) | Rinaldo |
| **Client asks Fancy Lab to write / author / strategize content (out-of-scope)** | **Immediately** | **Document request; Carlos escalates to Rinaldo same day; run Out-of-Scope sub-protocol (Step 14). Do NOT start the work.** | **Rinaldo** |
| Pastel dashboard creation blocked (licence / seat issue) | 1 business day | Manuk resolves with Pastel account admin; if unresolved in 48h, escalate | Manuk → Asya |
| Client-supplied product-data feed is unreadable / malformed | 2 business days | Carlos requests a clean re-export; if client cannot produce one, flag to P5 as an import-phase risk | Carlos + Asya |
| Figma brand-asset ingestion blocked (missing fonts / unresolvable licence) | 3 business days | Aida requests replacement from client via Carlos; document as Content Gap row | Aida → Carlos |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **Approved Project Specification** | P2 — Project Specification | Cannot run the content quality-check (Step 11) without the approved sitemap + field list |
| **ClickUp Project List (opened)** | P1 — Client Onboarding (v2, Step 11) | Cannot apply tag taxonomy / automations without an existing list |
| **Canonical Tag Taxonomy (workspace doc)** | P2 — Project Specification (v2, Step 1.5) | Cannot apply the tag set in Step 4 if the workspace doc does not exist |
| **Brand Assets (verified in P1)** | P1 — Client Onboarding (Gate #8) | Cannot stock the Figma file in Step 10 without verified brand assets |
| **Credentials (registrar, hosting, GA, GSC, payment, email platform)** | P1 — Client Onboarding (Gates #11–#16) | Cannot provision staging or wire integrations without verified credentials |
| **Approval Authority Map** | P1 — Client Onboarding (Gate #5, HARD BLOCK) | Content Gap Log chase (Step 13) and waiver collection require a confirmed decision-maker |
| **Client Content (copy, imagery, product data)** | Client | No content = nothing to ingest; Gap Log will be >50% open and gate blocked |

**REVISION LIMITS & SCOPE CONTROL**

Technical Environment: Standard Shopify dev store + staging pattern
used. Non-standard stacks (e.g., headless storefronts, custom CMS)
require PM approval and are priced as Change Orders against P0 if
not captured in the original Project Brief.

Drive Folder Structure: Canonical subfolder tree is fixed — do not
add or rename top-level folders without PM approval. Sub-subfolder
additions (e.g., extra `/Products/[category]/`) are allowed without
approval.

Content Gap Log: No limit on the number of rows, but any row open
past the phase's target end date requires written waiver or a
schedule-slip acknowledgment by Rinaldo.

Out-of-Scope Content Authoring: Not permitted under any
circumstances without a signed Change Order. This is not subject to
a "revision limit" — it is a categorical exclusion.

*Any additional revisions beyond the limits above require a Change
Order approved by the Project Lead and communicated to the client
with associated timeline and cost impact.*

**PHASE GATE - COMPLETION CHECKLIST**

*ALL items below must be completed before the project can advance to
P4 — Design. Any open item on the Content Gap Log, any un-verified
row on the Access Matrix, or any missing Handoff Packet
acknowledgment blocks the gate.*

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **1** | Shopify development store provisioned, configured, and password-protected; URL + credentials in vault |  |  |
| **2** | Staging environment live; access list documented |  |  |
| **3** | Project repository created with README + pinned-links (if custom code in scope) |  |  |
| **4** | Canonical tag taxonomy applied to the ClickUp list; priority + tag hygiene automations live and routing to `#proj-[clientname]` |  |  |
| **5** | Pastel dashboard created, scoped, and linked from ClickUp |  |  |
| **6** | Google Drive project folder structure created with canonical subfolder tree; permissions set |  |  |
| **7** | Slack project channel `#proj-[clientname]` created; full team added; pinned-links message posted |  |  |
| **8** | Access Matrix complete; every team member has logged in and confirmed access to every system they are marked for |  |  |
| **9** | Client content package fully ingested and organized in Drive (copy + imagery + product data, per P2 sitemap) |  |  |
| **10** | Figma project file stocked with brand assets (logos, color styles, fonts, brand photography) |  |  |
| **11** | Client content quality-checked against the P2 Project Specification; findings captured in Content Gap Log |  |  |
| **12** | Every Content Gap Log row is either `delivered` or formally `waived` (written waiver on file for waived rows) |  |  |
| **13** | Any Out-of-Scope content-authoring request (if triggered) has been formally resolved by Rinaldo (pulled or Change Order) |  |  |
| **14** | P3 → P4 Handoff Packet published in `/07-Handoff Packets/`; Aida has acknowledged via ClickUp subtask |  |  |

**Phase Gate Sign-Off**

|                        |                             |          |
|:-----------------------|:----------------------------|:---------|
| **Field**              | **Details**                 | **Date** |
| **Project Name**       |                             |          |
| **Phase Lead**         | Asya                        |          |
| **Approved By**        | Rinaldo                     |          |
| **Client Rep**         |                             |          |
| **Next Phase**         | P4 — Design                 |          |
| **Notes / Conditions** |                             |          |

## Data Enrichment (ClickUp export, 2026-04-22)

*The current ClickUp export contains no direct P3 signals because
the old "Content Strategy & Copywriting" phase was never faithfully
executed — the setup work that actually happens between P1
onboarding and P4 design has historically been threaded through P2
kickoff tasks, P1 asset collection, and ad-hoc dev-store creation.
Formalizing the work here is itself the correction; future ClickUp
exports should show discrete P3 tasks tagged against the canonical
taxonomy, which will enable the first real measurement of
setup-phase load. In the meantime, the following indirect signals
from the gap analysis and portfolio health docs informed the v3
design:*

- **Why "no content authoring" is the right boundary.** Only 27 of
  2,304 workspace tasks carry the `seo` tag, and the workspace has
  no recurring copywriting queue (per
  `data/analysis/03_sop_gap_and_recommendations.md` §A/§B). The
  previous P3 SOP's scope (SEO keyword research, page-by-page
  copywriting) was never operationalized. v3 removes the fiction and
  aligns P3 with what the team actually does — technical setup and
  content ingestion.
- **Why Access Matrix verification is a gate item.** Per P1 v2 Data
  Enrichment, "access verification drift" is a recurring failure
  mode — credentials captured early can break before P6 begins
  (examples: `add residential liftgate`, `Bank Wants the Following`,
  broken-link fixes). P3's Access Matrix re-verifies every
  provisioned system before design begins so design-phase blockers
  are not credential-related.
- **Why Aida must explicitly acknowledge the handoff.** Aida's
  workspace load is 246 tasks, 123 open (per P2 v2 Data
  Enrichment) — she is the upstream bottleneck. A silent handoff
  risks P4 starting on an under-provisioned project; an explicit
  ClickUp acknowledgment closes the loop.
- **Why the Content Gap Log is a blocking gate.** Client-side stalls
  (breadiamonddirect.com 862d, ian.club 457d, Select Dental,
  barclaysjewelers.com 580d — per `02_portfolio_health.md`) trace
  repeatedly to missing client inputs that were never formally
  resolved. Forcing every gap to `delivered` or `waived` with a
  written trail prevents the same pattern from recurring in P4 and
  beyond.

---

**APPENDIX A: PROJECT SETUP CHECKLIST WORKSHEET**

*One row per process step. Used as the live worksheet while P3 is in
flight. Lightweight — free-form notes allowed in the Status
column.*

|  |  |  |  |  |
|:---|:---|:---|:---|:---|
| **\#** | **Process Step** | **Owner** | **Status** | **Date Completed** |
| **1** | Provision Shopify Development Store | Ishkhan / Narine |  |  |
| **2** | Provision Staging Environment | Ishkhan / Narine |  |  |
| **3** | Create Project Repository (if applicable) | Ishkhan / Narine |  |  |
| **4** | Apply ClickUp Tag Taxonomy + Priority Automations | Asya |  |  |
| **5** | Create Pastel Dashboard | Manuk |  |  |
| **6** | Create Google Drive Project Folder Structure | Carlos |  |  |
| **7** | Create Project Slack Channel + Onboard Team | Asya |  |  |
| **8** | Grant Team Access + Build Access Matrix | Asya |  |  |
| **9** | Ingest Client Content into Drive | Carlos |  |  |
| **10** | Ingest Brand Assets into Figma | Aida |  |  |
| **11** | Quality-Check Client Content vs. Project Specification | Carlos + Aida |  |  |
| **12** | Compile Content Gap Log | Carlos |  |  |
| **13** | Resolve or Waive Every Gap | Carlos |  |  |
| **14** | Out-of-Scope Escalation (if triggered) | Carlos → Rinaldo |  |  |
| **15** | Compile P3 → P4 Handoff Packet + Aida Acknowledgment | Asya + Aida |  |  |

**Appendix A.1 — Access Matrix Template**

|  |  |  |  |  |  |  |  |
|:---|:---|:---|:---|:---|:---|:---|:---|
| **System** | **Carlos** | **Aida** | **Ishkhan** | **Narine** | **Manuk** | **Asya** | **Verified Date** |
| Shopify Dev Store |  |  |  |  |  |  |  |
| Staging Environment |  |  |  |  |  |  |  |
| Project Repository |  |  |  |  |  |  |  |
| ClickUp Project List |  |  |  |  |  |  |  |
| Pastel Dashboard |  |  |  |  |  |  |  |
| Figma Project File |  |  |  |  |  |  |  |
| Google Drive Folder |  |  |  |  |  |  |  |
| Slack Channel |  |  |  |  |  |  |  |
| Secure Credential Vault |  |  |  |  |  |  |  |

*Cell values: `admin` / `editor` / `viewer` / `none`. Every
non-`none` cell must be logged-in-verified by the named person and
initialled in the Verified Date column before Gate Item #8 is
checked.*

**Appendix A.2 — Content Gap Log Template**

|  |  |  |  |  |  |  |  |  |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| **Row** | **Item** | **Page / Section** | **Type** | **Gap Description** | **Owner** | **Requested Date** | **Target Resolution Date** | **Status** |
|  |  |  |  |  |  |  |  |  |

*Types: copy / image / brand asset / product data / legal. Status:
open / delivered / waived. A `waived` row requires a pointer to the
written waiver filed under `/00-Brief & Contracts/waivers/`.*

**Setup Completed By:**
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Phase Lead Sign-Off (Asya):**
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Approver Sign-Off (Rinaldo):**
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Downstream Acknowledgment (Aida, P4 Lead):**
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

*Once all fourteen gate items are checked and the four signatures
above are collected, the project is fully provisioned, the client's
content is organized and quality-checked, and P4 — Design can
begin without ambiguity or setup tax.*
