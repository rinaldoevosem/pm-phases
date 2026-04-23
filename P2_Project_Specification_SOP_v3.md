# P2 — Project Specification

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
- [Appendix A: Project Specification & Infrastructure Setup Checklist](#appendix-a-project-specification--infrastructure-setup-checklist)

## Revision History

<details>
<summary>v3.0 (April 2026) — GitHub-render pass</summary>

- Restructured headings: `**BOLD CAPS**` paragraphs → `##` / `###`, so GitHub's outline sidebar populates.
- Replaced empty-header pandoc tables (`|  |  |  |` + bolded content row) with proper pipe tables.
- Converted nested-blockquote process steps (`> **1. Step**`) to ordered lists.
- Unescaped pandoc backslash noise (`\|`, `\-`, `\#`, `\<`, `\>`, `\_`).
- Added TOC, metadata table; wrapped long appendices in `<details>`.
- Converted HTML `<table>` appendix to GFM pipe tables with `###` section dividers.
- No content changes — every fact, number, named person, client, and cell preserved verbatim from v2.

</details>

<details>
<summary>v2.0 (April 2026) — ClickUp enrichment</summary>

- v2.0 (April 2026): Added Priority Hygiene Addendum — every kickoff-created ClickUp task must have a priority set at creation; ClickUp automation flags any task >24h old with no priority. Driven by `data/analysis/03_sop_gap_and_recommendations.md` §B finding that 62.4% of tasks have no priority set.
- v2.0 (April 2026): Added Tag Taxonomy Addendum — defined a canonical 14-tag taxonomy and made tag assignment a kickoff process step; ClickUp automation flags untagged tasks >24h. Driven by §B finding that only 10 distinct tags exist across 2,304 tasks.
- v2.0 (April 2026): Added two new Phase Gate items (#11 priority set on every kickoff-created task; #12 canonical tag taxonomy documented in ClickUp and socialized).
- v2.0 (April 2026): Added Step 1.5 "Define / Apply Tag Taxonomy" as part of ClickUp setup, per `Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md` § Data Enrichment recommendation.
- v2.0 (April 2026): Appended "Data Enrichment (ClickUp export, 2026-04-22)" section preserving the workspace-level statistics that motivated these additions.
- v2.0 (April 2026): Noted forward-looking recommendation to maintain an "ops lists" registry alongside client lists (DAILY STAND UP, EOD Report, Inventory Management, DIAMOND SEARCH, RING BUILDER, TICKETS, etc.).

</details>

## Purpose & Scope

This SOP defines the standard process for technically initializing a new
web development project at Fancy Lab. It ensures that all project
management tools, design environments, and development platforms are
properly configured, and a detailed project roadmap with clear
milestones is established and approved by the client before any design
or development work begins.

### Phase Objective

Set up all technical project infrastructure (ClickUp, Figma,
Shopify/platform), create and get client approval on the project
requirements document and roadmap, and ensure the full team is aligned
on deliverables, timeline, and responsibilities.

### Scope Includes

- Initial discovery call with prospective client
- ClickUp project workspace creation and task structure setup
- Figma project file creation with proper structure
- Development platform setup (Shopify, WordPress, or custom)
- Project requirements document creation and client approval
- Project roadmap and milestone planning
- Team role assignment and task delegation in ClickUp
- Client communication of approved roadmap and next steps
- Canonical tag taxonomy definition and rollout (new in v2)
- Priority-at-creation discipline for all kickoff tasks (new in v2)

### Scope Excludes

- Design work (covered in P4 - Design)
- Content creation or copywriting (covered in P3 - Project Setup)
- Actual development or coding (covered in P6 - Development)
- Client information gathering (completed in P1)
- Inventory or product data entry (covered in P5 - Inventory Management)

## WHO — RACI Matrix

| Role | Person(s) | Responsibility |
|---|---|---|
| Responsible | Asya + Aida | *Performs the work for this phase* |
| Accountable | Asya + Aida | *Ultimately answerable for completion* |
| Consulted | Rinaldo + Carlos | *Provides input and approves deliverables* |
| Informed | Harry | *Kept up to date on progress* |

## WHAT — Deliverables

| Deliverable | Format / Location | Owner |
|---|---|---|
| ClickUp Project Workspace | ClickUp | Asya |
| Figma Project File | Figma | Aida |
| Platform/Shopify Dev Store | Shopify / CMS | Asya |
| Project Requirements Document | Google Docs / ClickUp Doc | Asya + Aida |
| Project Roadmap with Milestones | ClickUp / Google Docs | Asya |
| Canonical Tag Taxonomy Doc | ClickUp Doc | Asya |
| Kickoff Email to Client | Email | Asya |
| Internal Kickoff Summary | Slack | Asya |

## WHERE — Tools & Platforms

| Tool | Purpose in This Phase |
|---|---|
| ClickUp | Project management, task creation, roadmap, milestone tracking, tag taxonomy enforcement, priority-hygiene automations |
| Figma | Design project file setup, wireframe structure |
| Shopify / WordPress / Custom CMS | Development store or staging environment setup |
| Google Drive | Requirements document, shared reference files |
| Google Meet | Internal kickoff meeting, client requirements review |
| Slack | Internal team notifications, daily coordination, automation alerts (untagged / unprioritized tasks) |
| Email | Client communication of roadmap and next steps |

## HOW — Process Steps

1. **Create ClickUp Project Workspace.** Set up the project workspace in ClickUp using the standard Fancy Lab template. Create lists for each phase (Design, Content, Development, QA, Launch). Assign team members to their respective lists. Configure custom fields: client name, project type, platform, target launch date.

2. **1.5. Define / Apply Canonical Tag Taxonomy (new in v2).** Apply the Fancy Lab canonical tag taxonomy to the project workspace. The canonical list (15 tags) is:

   - `qa` — testing, regression, Pastel-tracked issues
   - `iframe` — third-party embeds (Ring Builder, Diamond Search, Nivoda, MyDiamonds, BOSS Logics)
   - `inventory` — product / catalog / vendor-feed work
   - `seo` — on-page SEO, redirects, schema, metadata
   - `design` — Figma design or design-system work
   - `dev` — implementation, theme code, custom code
   - `client-block` — paused awaiting client input or approval
   - `vendor-block` — paused awaiting third-party / vendor response
   - `support` — post-launch / warranty / ongoing support work
   - `marketing` — marketing-handoff scope (Ascend, ads, etc.)
   - `bug` — defect against shipped / approved behavior
   - `feature` — net-new functionality
   - `content` — copy, image direction, content map
   - `launch-blocker` — must resolve before P9 launch
   - `change-order` — work added via approved change order (scope-creep tracking)

   Document this list in a ClickUp Doc pinned at the workspace root. Socialize in Slack at the internal kickoff (Step 6) so every team member knows the list exists and where to find it. Tags MUST be applied at task creation; multi-tag is allowed and encouraged.

3. **Set Up Figma Project File.** Create a new Figma project file using the Fancy Lab design template. Set up pages for: Wireframes, Desktop Design, Mobile Design, Components, and Client Feedback. Import brand assets from the Google Drive folder created in P1. Share with the design team and set proper permissions.

4. **Configure Development Platform.** Create the development store or staging environment on the target platform (Shopify, WordPress, or custom). Install required base themes or frameworks. Configure basic settings (currency, language, timezone). Document the dev store URL and admin credentials securely.

5. **Draft Project Requirements Document.** Using the approved Project Brief from P0 and information gathered in P1, create a detailed Project Requirements Document covering: all pages and their functionality, navigation structure, design requirements, third-party integrations, e-commerce features (if applicable), SEO requirements, performance targets, and browser/device compatibility requirements.

6. **Build Project Roadmap and Milestones.** Create a phased project roadmap in ClickUp with clear milestones: Project Setup completion, Design approval (per page/section), Development sprints, QA rounds, Client Review windows, and Launch date. Assign dates based on the agreed timeline from P0. Include buffer time for revisions.

7. **5.5. Apply Priority + Tag Hygiene to All Kickoff Tasks (new in v2).** Every task created in ClickUp during kickoff (and from this phase forward) MUST have:

   - A priority set at creation: Urgent / High / Normal / Low. "Normal" is the default for routine work; "Urgent" is reserved for launch-blockers or client-block items. No task ships from kickoff in an unprioritized state.
   - At least one tag from the canonical taxonomy defined in Step 1.5.

   Configure two ClickUp automations on the workspace:

   1. **Missing-priority alert.** If a task has been in any list for >24 hours with priority unset, post to `#proj-[clientname]` Slack and assign a "needs-priority" subtask to the task creator.
   2. **Untagged-task alert.** If a task has been in any list for >24 hours with zero tags, post to `#proj-[clientname]` Slack and assign a "needs-tag" subtask to the task creator.

   Asya owns the audit; the kickoff cannot pass the gate while the automations are unconfigured or while any kickoff-created task remains unprioritized or untagged.

8. **Internal Kickoff Meeting.** Conduct an internal team meeting to review: project scope and requirements, roadmap and milestones, individual responsibilities, client communication expectations, potential risks or blockers, and dependencies between phases. Walk the team through the canonical tag taxonomy (Step 1.5) and the priority-at-creation rule (Step 5.5). Document action items.

9. **Client Requirements Review.** Present the Project Requirements Document and Roadmap to the client via email or meeting. Walk through all deliverables, milestones, and approval checkpoints. Collect client sign-off on the requirements and timeline. Note any changes and update documents accordingly.

10. **Send Kickoff Confirmation Email.** Send the client a formal kickoff email including: confirmed project roadmap, milestone dates, next steps (what phase begins next), what the client needs to prepare, primary points of contact, and how to provide feedback throughout the project.

11. **Finalize and Notify Team.** Update ClickUp with all finalized information. Post in Slack with: project name, confirmed timeline, team assignments, links to all project resources (ClickUp, Figma, dev store, Drive folder), and a link to the canonical tag taxonomy doc. Mark P2 as complete.

## Communication — Stakeholder Updates

| Type | Frequency | Audience | Channel |
|---|---|---|---|
| Internal Kickoff Meeting | Once | Full Project Team | Google Meet |
| Client Requirements Review | Once (may require follow-up) | Client + PM | Google Meet / Email |
| Kickoff Confirmation Email | Once | Client | Email |
| Team Notification | Once (at phase close) | Full Project Team | Slack |
| Tag Taxonomy Socialization | Once at kickoff + on every onboarding | Full Project Team | Slack + ClickUp Doc |
| Priority/Tag Automation Alerts | Continuous (>24h breach) | Task creator + PM | Slack |
| Requirements Follow-up | As needed (max 2 rounds) | Client | Email |

## Escalation — Blocked Phase Protocol

| Trigger | Timeframe | Escalation Action | Escalated To |
|---|---|---|---|
| Client delays requirements approval | 5 business days | Send reminder with impact statement on timeline | Asya |
| Requirements still unapproved | 10 business days | Escalate to account lead; schedule direct call | Rinaldo |
| Scope creep identified in requirements | Immediately | Flag to PM; route to P0 for Change Order if needed | Rinaldo + Carlos |
| Platform/tool access issues | 2 business days | Escalate to tech lead for resolution | Asya |
| Team availability conflict | Immediately | Re-assign or adjust roadmap; notify client if timeline affected | Rinaldo |
| Untagged or unprioritized tasks accumulating | >24h breach reported by automation | PM reviews, assigns owner, fixes within 1 business day | Asya |

## Dependencies — Required Inputs

| Dependency | Source Phase | Impact if Missing |
|---|---|---|
| Completed Client Onboarding | P1 - Client Onboarding | Cannot set up project without client assets, credentials, and confirmed brief |
| Brand Assets in Drive | P1 - Client Onboarding | Cannot set up Figma project without logos, fonts, and brand guidelines |
| Platform Credentials | P1 - Client Onboarding | Cannot create dev store without domain/hosting access |
| Approved Project Brief | P0 - Discovery & Sales | Requirements document is built from the project brief |

## Revision Limits & Scope Control

Project Requirements Document: Up to 2 rounds of client revisions before
requiring PM approval for additional rounds

Roadmap Adjustments: Timeline can be adjusted once based on client
feedback; further changes require formal Change Order

Tool Setup: Standard templates used; custom configurations require PM
approval

Tag Taxonomy: The canonical list is workspace-wide. Project-specific
additions require PM approval and must be added to the master ClickUp
Doc so other projects inherit them.

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

## PHASE GATE — Completion Checklist

> [!IMPORTANT]
> ALL items below must be completed before the project can advance to P3 - Project Setup. No design or development work should begin until the project infrastructure is fully set up and requirements are approved.

| # | Gate Requirement | Status | Date |
|---|---|---|---|
| 1 | ClickUp project workspace created with full task structure |  |  |
| 2 | Figma project file created with proper page structure |  |  |
| 3 | Development store/staging environment configured |  |  |
| 4 | Project Requirements Document drafted and client-approved |  |  |
| 5 | Project Roadmap with milestones created in ClickUp |  |  |
| 6 | Internal kickoff meeting conducted with all team members |  |  |
| 7 | Client sign-off on requirements and timeline received |  |  |
| 8 | Kickoff Confirmation Email sent to client |  |  |
| 9 | All team members assigned and notified in Slack |  |  |
| 10 | All project links documented (ClickUp, Figma, Dev Store, Drive) |  |  |
| 11 | Every kickoff-created task has priority set (Urgent / High / Normal / Low); missing-priority automation configured |  |  |
| 12 | Canonical tag taxonomy documented in ClickUp and socialized to team; untagged-task automation configured |  |  |

### Phase Gate Sign-Off

| Field | Details | Date |
|---|---|---|
| Project Name |  |  |
| Approved By |  |  |
| Client Rep |  |  |
| Next Phase | P3 - Project Setup |  |
| Notes / Conditions |  |  |

## Data Enrichment (ClickUp export, 2026-04-22)

- **84 ClickUp lists** in the workspace, mostly client domains — consistent with "one list per project." A handful are cross-client ops: `DAILY STAND UP` (15), `EOD Report` (5), `Inventory Management` (34), `DIAMOND SEARCH` (6), `RING BUILDER` (56), `TICKETS` (10), `Kirk Kara Tickets Tracking` (10). These are legitimate but **not named in the P2 SOP** — recommend an explicit "ops lists" registry maintained alongside client lists.
- **Tag hygiene is poor at kickoff.** Only 10 distinct tags are in use across 2,304 tasks (top: `development` 187 · `inventory` 30 · `qa` 29 · `seo` 27 · `design` 23 · `iframe` 22). Step 1.5 ("Define / Apply Canonical Tag Taxonomy") is the v2 remediation — standardized tags at kickoff would unlock cross-phase analytics later.
- **Asya is already central to this phase in practice** — 131 tasks, 53 open; Aida 246 tasks, 123 open. Aida's 123-open load suggests Aida is the upstream bottleneck (P3 + P4); see Part II for the remediation suggestion.
- **Priority hygiene baseline.** 62.4% of all tasks across the workspace have no priority set. The Step 5.5 priority-at-creation rule plus the missing-priority automation are the v2 remediation; the gate item #11 is the enforcement point.

## Appendix A: Project Specification & Infrastructure Setup Checklist

<details>
<summary>Expand — Project Specification & Infrastructure Setup Checklist</summary>

*This document captures all internal infrastructure setup, technical
environment configuration, and requirements alignment completed during
the Project Specification phase. It does NOT duplicate the Project Brief (P0)
or Onboarding Intake (P1) — instead it records the translation of client
requirements into actionable project infrastructure.*

*Prerequisites: P0 Project Brief and P1 Onboarding Intake Form must be
complete and approved before this checklist is started.*

### 1. ClickUp Project Workspace Setup

| Field | Details |
|---|---|
| **ClickUp Space Name** | *Format: [ClientName] — [ProjectType] (e.g., 'Luxe Jewelry — Full Redesign')* |
| **Board Template Applied** | *Which template was applied? Standard E-commerce / Migration / Custom — Template version: ___* |
| **Phase Lists Created** | *[ ] P2 Kickoff [ ] P3 Content [ ] P4 Design [ ] P5 Inventory [ ] P6 Dev [ ] P7 QA [ ] P8 Approval [ ] P9 Launch [ ] P10 Post Launch* |
| **Custom Fields Configured** | *[ ] Priority [ ] Sprint [ ] Estimated Hours [ ] Actual Hours [ ] Phase Gate Status [ ] Blocker Flag* |
| **Automations Enabled** | *[ ] Task creation → Slack notification [ ] Status change → PM alert [ ] Overdue → Escalation [ ] Phase gate → Review trigger [ ] Missing-priority >24h → Slack alert (v2) [ ] Untagged-task >24h → Slack alert (v2)* |
| **Canonical Tag Taxonomy Applied** | *[ ] 15-tag canonical list loaded into workspace [ ] Pinned ClickUp Doc created [ ] Team socialized in Slack (v2)* |
| **Priority-at-Creation Rule Acknowledged** | *[ ] All kickoff-created tasks have priority set (Urgent / High / Normal / Low) — Asya audit complete (v2)* |
| **Team Members Assigned** | *List each team member added to the board with their role: ___* |
| **Client View Configured?** | *Yes / No — What can the client see? (Tasks only / Progress bar / Full board)* |
| **Milestone Dates Set** | *All phase target completion dates entered? [ ] — Source: Project Roadmap* |

### 2. Google Drive Project Structure

| Field | Details |
|---|---|
| **Root Folder Created** | *Folder URL: ___ / Format: [ClientName] — [Year]* |
| **Subfolder Structure** | *[ ] 00-Brief & Contracts [ ] 01-Onboarding [ ] 02-Content [ ] 03-Design [ ] 04-Assets [ ] 05-Development [ ] 06-QA [ ] 07-Launch [ ] 08-Post Launch* |
| **P0 Brief Uploaded** | *Project Brief from P0 uploaded and linked? [ ]* |
| **P1 Intake Form Uploaded** | *Onboarding Intake from P1 uploaded and linked? [ ]* |
| **Client Assets Organized** | *All brand assets from P1 organized into /04-Assets subfolders? [ ]* |
| **Folder Permissions Set** | *Internal team: Edit / Client: View or Comment — Permissions verified? [ ]* |

### 3. Communication Channels Setup

| Field | Details |
|---|---|
| **Internal Slack Channel** | *Channel name: #proj-[clientname] — Created? [ ] / Team added? [ ]* |
| **Client Communication Channel** | *Channel/method per P1 agreement: ___ / Set up? [ ]* |
| **Slack–ClickUp Integration** | *ClickUp notifications flowing to Slack channel? [ ] / Which events? ___ / Includes priority + tag automation alerts (v2)? [ ]* |
| **Calendar Invites Sent** | *All recurring check-ins scheduled per P1 communication cadence? [ ]* |
| **Welcome Email to Client** | *Sent? [ ] — Date: ___ / Includes: Project timeline, team intro, communication guide, next steps* |

### 4. Design Environment Setup

| Field | Details |
|---|---|
| **Figma Project Created** | *Project URL: ___ / Inside team workspace: [ ]* |
| **Figma File Structure** | *[ ] Cover page [ ] Wireframes page [ ] Desktop Designs page [ ] Mobile Designs page [ ] Components page [ ] Assets page* |
| **Brand Colors Added to Figma** | *Color styles created from P1 brand assets? [ ] — Verified against hex codes: [ ]* |
| **Brand Fonts Loaded** | *Heading font: ___ / Body font: ___ / Loaded in Figma? [ ] / License verified? [ ]* |
| **Logo Assets Placed** | *Logo variants imported to Figma assets page? [ ]* |
| **Inspiration Board Created** | *Reference sites from P0 brief captured in Figma? [ ] / Competitor screenshots from P1? [ ]* |
| **Design System Base Components** | *[ ] Button styles [ ] Typography scale [ ] Color palette [ ] Spacing system [ ] Grid system — Initialized: [ ]* |

### 5. Development Environment Setup

| Field | Details |
|---|---|
| **Shopify Development Store** | *Store URL: ___ / Created or existing: ___ / Admin access verified for all devs: [ ]* |
| **Theme Selection / Base** | *Theme: ___ (Dawn / Custom / Migration from existing) / Version: ___* |
| **Git Repository Created** | *Repo URL: ___ / Branch strategy: main → staging → feature branches / README initialized: [ ]* |
| **Development Workflow Confirmed** | *[ ] Local dev environment [ ] Theme CLI connected [ ] Preview theme created [ ] Deployment pipeline configured* |
| **Staging Environment URL** | *URL: ___ / Password protected: [ ] / Password: ___* |
| **Third-Party App Accounts Created** | *List each app installed on dev store with status: ___* |
| **API Keys Documented** | *All API keys stored in credentials vault? [ ] / Keys needed: ___* |

### 6. Requirements Alignment & Gap Analysis

| Field | Details |
|---|---|
| **P0 Brief → Requirements Mapping** | *All Project Brief items translated to specific ClickUp tasks? [ ] / Total tasks created: ___ / All tasks have priority + at least one canonical tag (v2)? [ ]* |
| **Feature Feasibility Check** | *All must-have features reviewed for technical feasibility? [ ] / Any flagged issues: ___* |
| **Integration Compatibility Verified** | *All integrations from P0 confirmed compatible with Shopify plan level? [ ] / Issues: ___* |
| **Scope Gaps Identified** | *Any requirements unclear or missing from P0/P1? List: ___* |
| **Scope Clarification Questions** | *Questions sent to client? [ ] / Date: ___ / Responses received? [ ]* |
| **Revised Scope (if applicable)** | *Any scope changes resulting from gap analysis? Document here: ___* |
| **Effort Estimation Complete** | *Hours estimated per phase: P3: ___ / P4: ___ / P5: ___ / P6: ___ / P7: ___ / P8: ___ / P9: ___ / P10: ___* |

### 7. Project Roadmap & Timeline

| Field | Details |
|---|---|
| **Project Start Date** | *Confirmed: ___ (from P0 brief)* |
| **Target Launch Date** | *Confirmed: ___ (from P0 brief) / Feasibility check: Achievable / At Risk / Requires Discussion* |
| **Phase Timeline Breakdown** | *P3: ___–___ / P4: ___–___ / P5: ___–___ / P6: ___–___ / P7: ___–___ / P8: ___–___ / P9: ___* |
| **Critical Path Items** | *List any tasks/phases that have zero float and directly impact launch date: ___ / Tagged `launch-blocker` (v2)? [ ]* |
| **Buffer Days Built In** | *How many buffer days between phases? ___ / Pre-launch buffer: ___ days* |
| **Client Dependencies on Timeline** | *List dates when client must deliver: Content by ___ / Asset approval by ___ / Final approval by ___* |
| **Roadmap Shared with Client?** | *[ ] Sent via email [ ] Reviewed on call [ ] Client acknowledged — Date: ___* |

### 8. Internal Team Kickoff Meeting

| Field | Details |
|---|---|
| **Meeting Date** | *Date: ___ / Duration: ___* |
| **Attendees** | *List all team members present: ___* |
| **Brief Walkthrough Completed** | *Project scope, client expectations, and brand direction reviewed with team? [ ]* |
| **Tag Taxonomy + Priority Rule Walkthrough (v2)** | *15-tag canonical list and priority-at-creation rule reviewed? [ ] / Team confirmed they know where the ClickUp Doc lives? [ ]* |
| **Role Assignments Confirmed** | *Each team member acknowledged their responsibilities for each phase? [ ]* |
| **Risk Discussion** | *Known risks discussed? [ ] / Mitigation plans documented? [ ]* |
| **Team Questions / Concerns** | *Any open questions from team members: ___* |
| **Action Items from Meeting** | *List action items with owner and due date: ___* |

Kickoff Completed By: ____________________________________ Date: _______________

PM Sign-Off: ____________________________________ Date: _______________

*Once all sections above are complete, the project infrastructure is
fully established and the team is aligned. The Phase Gate can be
evaluated for advancement to P3 — Project Setup.*

</details>
