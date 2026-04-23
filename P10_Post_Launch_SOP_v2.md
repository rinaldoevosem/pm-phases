**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P10**

**POST-LAUNCH, WARRANTY & ONGOING SUPPORT**

Standard Operating Procedure & Phase Gate Document

v2.0 \| April 2026 \| Confidential

**REVISION HISTORY / CHANGELOG**

> v1.0 → v2.0 (April 2026) — substantive scope expansion driven by ClickUp data analysis:
>
> \- **Scope widened to cover ongoing client support beyond the 90-day warranty.** Per `data/analysis/03_sop_gap_and_recommendations.md` §B (row "Ongoing client support beyond 90-day warranty") and §D item 1, the `SUPPORT` folder holds 262 ad-hoc tasks and `Weekly Support Follow Ups` recurs 42×. The PROCESS and PHASE GATE are now split into two clearly labeled sub-sections: **(A) Warranty Period (Day 0–90)** and **(B) Ongoing Support (Day 90+)**.
>
> \- **Warranty window aligned to 90 days** (was 30 days in v1) to match the 30-day analytics report cadence + a 60-day support-tail observed in the data. The 30-day analytics report itself remains a Day-30 deliverable inside the warranty window.
>
> \- **Absorbed two retention items moved out of P9 v2 launch scope** (per gap doc §C "P9 Launch checklist contains commercial/retention items"): `Give client 1 month free of Base Plan` and `Ascend Proposals to Marketing`. These now live in the new Ongoing Support sub-section as the retention incentive and the marketing-handoff trigger respectively.
>
> \- **Defined the marketing-handoff trigger.** Gap doc §D item 2 originally proposed a standalone "P10.5 Marketing Handoff" SOP; per the v2 brief's "do not invent new phases" rule, the handoff is defined here as a clearly-scoped section within Ongoing Support (303 tasks in the `MARKETING` folder lack a documented boundary today).
>
> \- **Added support-task escalation thresholds** (>14 days open or >5 comments without resolution → escalate to Rinaldo) to address the long-tail problem highlighted in `02_portfolio_health.md` (kirkkara.com oldest open = 993d; 1800loosediamonds.com oldest = 1,998d).
>
> \- **New phase-gate items:** "Ongoing support cadence set with named owner," "Marketing handoff completed or scheduled," and "Retention incentive issued."
>
> \- **Data Enrichment section appended** with ClickUp export figures (2026-04-22).
>
> \- **Follow-up flagged:** the gap analysis recommended a standalone `P11 Ongoing Support` SOP. v2 absorbs that scope into P10 as a pragmatic step. If support volume continues to grow or the Day-90 boundary becomes operationally meaningful for billing/reporting, separating into a dedicated P11 should be revisited.

**PURPOSE & SCOPE**

This SOP defines the standard process for post-launch support, client
training, project closure, transition to ongoing maintenance, and the
ongoing client-support relationship that runs beyond the 90-day
warranty. It ensures the client is empowered to manage their website,
all project documentation is finalized, the engagement transitions
cleanly from project delivery to support/retainer, and continuing
support work has a documented owner, cadence, and escalation path.

**Phase Objective**

Deliver comprehensive client training, resolve any post-launch issues
during the 90-day warranty, finalize all project documentation, conduct
an internal retrospective, formally close the project (or transition to
an ongoing maintenance agreement), and operate a documented ongoing
support cadence for clients beyond the warranty window.

**Scope Includes**

> \- Post-launch bug fixes and issue resolution (90-day warranty)
>
> \- Client training on CMS / platform management
>
> \- Documentation handoff (admin guide, credentials, integrations)
>
> \- Analytics baseline reporting (first 30 days)
>
> \- Internal project retrospective
>
> \- Project closure documentation
>
> \- Maintenance agreement transition (if applicable)
>
> \- Client satisfaction survey / testimonial request
>
> \- **Ongoing support beyond Day 90** — weekly support follow-ups, ticket triage, escalation
>
> \- **Retention incentive** — 1 month free of Base Plan
>
> \- **Marketing handoff trigger** — `Ascend Proposals to Marketing`

**Scope Excludes**

> \- New feature development (requires new project or Change Order)
>
> \- Ongoing content creation or blog management (retainer service)
>
> \- Ongoing SEO optimization (retainer service)
>
> \- Active marketing campaign management (transferred to Marketing team via handoff trigger)
>
> \- Hosting management (unless in maintenance agreement)

**WHO - RACI MATRIX**

|                 |               |                                            |
|:----------------|:--------------|:-------------------------------------------|
| **Role**        | **Person(s)** | **Responsibility**                         |
| **Responsible** | Carlos + Asya | *Performs the work for this phase*         |
| **Accountable** | Rinaldo       | *Ultimately answerable for completion*     |
| **Consulted**   | Narine + Aida | *Provides input and approves deliverables* |
| **Informed**    | Harry         | *Kept up to date on progress*              |

*Ongoing Support sub-section adopts the same RACI: Carlos + Asya
Responsible, Rinaldo Accountable. Escalations route to Rinaldo.*

**WHAT - DELIVERABLES**

|  |  |  |
|:---|:---|:---|
| **Deliverable** | **Format / Location** | **Owner** |
| **Client Training Session (recorded)** | Google Meet Recording / Drive | Carlos |
| **Website Admin Guide** | Google Docs | Carlos |
| **Credentials and Access Document** | Secure Storage / Google Docs | Asya |
| **Integration Documentation** | Google Docs | Asya |
| **30-Day Analytics Report** | Google Docs / Sheets | Carlos |
| **Internal Retrospective Notes** | Google Docs | Rinaldo |
| **Project Closure Report** | Google Docs | Carlos |
| **Maintenance Agreement (if applicable)** | PandaDoc | Harry + Rinaldo |
| **Client Satisfaction Survey** | Google Forms | Carlos |
| **Retention Incentive (1 month free of Base Plan)** | ClickUp + Email confirmation | Carlos |
| **Marketing Handoff Packet (`Ascend Proposals to Marketing`)** | Google Drive + ClickUp handoff task | Carlos + Rinaldo |
| **Weekly Support Follow-Up Log** | ClickUp `SUPPORT` list (recurring checklist) | Carlos + Asya |
| **Ongoing Support Ticket Records** | ClickUp tag `support` / `ticket` in dedicated `SUPPORT` list | Asya |

**WHERE - TOOLS & PLATFORMS**

|  |  |
|:---|:---|
| **Tool** | **Purpose in This Phase** |
| **Google Meet** | Client training sessions |
| **Google Drive** | Documentation storage, training recordings |
| **Google Analytics** | 30-day performance reporting |
| **Google Search Console** | Search performance monitoring |
| **ClickUp** | Post-launch task tracking, bug management, `SUPPORT` list (262 ongoing-support tasks today) |
| **PandaDoc** | Maintenance agreement creation and signing |
| **Slack** | Internal retrospective coordination, team updates, support escalations |
| **Loom (optional)** | Tutorial videos for client reference |
| **Email** | Client communication, survey distribution, weekly support follow-up |

**HOW - PROCESS STEPS**

The PROCESS is split into two sequential sub-sections. Sub-section A
runs Day 0–90 from launch; Sub-section B runs from Day 90 onward and
continues for the life of the client relationship until either churn or
explicit handoff.

---

**SUB-SECTION A — WARRANTY PERIOD (DAY 0–90)**

> **A.1. Address Post-Launch Issues**
>
> During the first 90 days after launch, monitor for and fix any issues
> that arise: bugs not caught during QA, browser-specific issues
> reported by end users, content corrections needed, performance issues
> under real traffic, and integration failures. Track all issues in
> ClickUp with priority and resolution status.
>
> **A.2. Schedule and Conduct Client Training**
>
> Schedule a comprehensive training session (1-2 hours) with the client
> covering: CMS navigation and content editing, adding/editing pages,
> managing products (if e-commerce), processing orders (if e-commerce),
> updating navigation menus, managing blog posts (if applicable), basic
> SEO maintenance, and who to contact for support. Record the session
> and share the recording.
>
> **A.3. Create Website Admin Guide**
>
> Prepare a written guide covering everything taught in training plus:
> step-by-step screenshots for common tasks, platform-specific tips and
> best practices, image size recommendations per section,
> troubleshooting common issues, and contact information for support.
> Make it accessible and non-technical.
>
> **A.4. Compile Credentials and Access Document**
>
> Create a secure document listing all accounts and access: CMS admin
> login, hosting account details, domain registrar access, Google
> Analytics and Search Console, email marketing platform, payment
> gateway, any third-party service accounts, and API keys (stored
> securely). Transfer all accounts to client ownership where applicable.
>
> **A.5. Document Integrations and Technical Setup**
>
> Create technical documentation covering: all third-party integrations
> (what, why, how configured), custom code or modifications made, theme
> customization details, any scheduled tasks or automations set up, CDN
> or caching configuration, and any platform-specific settings that
> should not be changed without developer guidance.
>
> **A.6. Generate 30-Day Analytics Report**
>
> After 30 days, compile a baseline analytics report: total sessions,
> users, and pageviews, traffic sources breakdown, top-performing pages,
> device and browser breakdown, e-commerce metrics (if applicable) —
> revenue, conversion rate, average order value, Google Search Console
> data — impressions, clicks, average position, Core Web Vitals status,
> and comparison to any pre-launch benchmarks.
>
> **A.7. Conduct Internal Retrospective**
>
> Hold a team retrospective meeting covering: what went well, what could
> be improved, process bottlenecks identified, communication issues,
> timeline accuracy vs. actual, client management learnings, tool or
> template improvements needed, and recommendations for future projects.
> Document findings and action items.
>
> **A.8. Prepare Project Closure Report**
>
> Create a formal closure report summarizing: project overview and final
> scope delivered, timeline (planned vs. actual), budget summary, team
> members and roles, key decisions and Change Orders, final deliverables
> list with links, and outstanding items or recommendations for the
> client.
>
> **A.9. Present Maintenance Agreement (if applicable)**
>
> If the client is interested in ongoing support, present a maintenance
> agreement covering: monthly retainer hours, response time SLAs,
> included services (updates, security patches, content changes,
> backups), excluded services (new features, redesign), pricing and
> billing terms. Process through PandaDoc.
>
> **A.10. Send Client Satisfaction Survey**
>
> Send a client satisfaction survey covering: overall satisfaction,
> communication quality, design quality, development quality, timeline
> management, likelihood to recommend (NPS), and open feedback. Use
> responses to improve processes. If the client is satisfied, request a
> testimonial for the portfolio.
>
> **A.11. Formal Project Closure**
>
> Mark all ClickUp tasks as complete. Archive the project workspace (but
> keep accessible). Send a final thank-you email to the client with: all
> documentation links, support contact information, maintenance
> agreement details (if signed), and appreciation for their business.
> Post in Slack confirming project closure.

---

**SUB-SECTION B — ONGOING SUPPORT (DAY 90+)**

*This sub-section formalizes work that the team is already performing
ad-hoc — 262 tasks in the `SUPPORT` folder and a `Weekly Support Follow
Ups` checklist that recurs 42 times in the ClickUp export (see Data
Enrichment). Carlos + Asya are Responsible; Rinaldo is Accountable.*

> **B.1. Stand Up the Ongoing Support Cadence**
>
> On Day 90 (warranty exit), formally transition the client into
> ongoing-support mode. Confirm the named owner on the Fancy Lab side
> (default: Carlos for client-facing communication, Asya for technical
> resolution) and the named contact on the client side. Communicate the
> shift to the client by email: where to send issues, expected response
> windows, what is and isn't covered without a maintenance agreement.
>
> **B.2. Intake and Triage**
>
> All incoming client requests are logged as ClickUp tasks in the
> dedicated `SUPPORT` list (or the client's list with the `support` or
> `ticket` tag — pick one convention per client and stay consistent).
> Required fields at intake: client, requestor, category (bug / change /
> question), priority, requested-by date. Tasks without a tag and a
> priority are flagged within 24 hours per the P2 priority/tag hygiene
> addendum.
>
> **B.3. Weekly Support Follow-Ups**
>
> Run the `Weekly Support Follow Ups` checklist every week per active
> support client. The cadence includes: review open tickets, send a
> status email to the client on each open item, close anything
> resolved-without-confirmation, surface anything blocked, and roll a
> short summary into the team's weekly stand-up. This checklist already
> recurs 42 times in the export — the SOP now governs it explicitly.
>
> **B.4. Resolution and SLAs**
>
> Default response and resolution windows when no maintenance agreement
> exists: critical (site down / revenue-blocking) — same business day;
> standard — 3 business days to first response, 10 business days to
> resolution; feature request — declined or routed to Change Order.
> Clients on a maintenance agreement use the SLAs in their contract,
> which override these defaults.
>
> **B.5. Escalation Thresholds**
>
> A support task escalates to the phase-gate owner (Rinaldo) if any of
> the following are true: open more than 14 calendar days without
> resolution; more than 5 comments accumulated without resolution;
> client has sent 2+ follow-up messages on the same task; or the task
> has been re-opened more than once. Escalation surfaces the task in
> the weekly PM review and triggers a written plan-to-resolve within 2
> business days. The aim is to prevent the long-tail problem visible in
> the data (kirkkara.com has an open task 993 days old; 1800loosediamonds.com
> has one 1,998 days old).
>
> **B.6. Issue Retention Incentive — 1 Month Free of Base Plan**
>
> Within 30 days of the warranty-exit transition (Step B.1), confirm the
> retention incentive `Give client 1 month free of Base Plan` has been
> issued: applied in billing, confirmed in writing to the client, and
> recorded in ClickUp. This item moved out of the P9 launch checklist
> in v2 because it is a retention-stage action, not a launch-sprint
> action.
>
> **B.7. Marketing Handoff Trigger — `Ascend Proposals to Marketing`**
>
> When the client is stable on the live site (typically 30–60 days
> after warranty exit, no active critical tickets, training delivered
> and acknowledged), trigger the marketing handoff. The trigger is the
> ClickUp task `Ascend Proposals to Marketing`, which packages: site
> URL and credentials shared with Marketing team, analytics access,
> brand and design tokens, completed deliverables list, recent support
> history, and any client preferences from the satisfaction survey.
> From the moment Marketing accepts the handoff, they own active
> outbound for the client; Web Development continues to own technical
> support per Sub-Section B unless otherwise agreed. (Gap doc §D item 2
> originally proposed a separate P10.5 SOP — absorbed here per the v2
> "no new phases" rule.)
>
> **B.8. Aging and Archival**
>
> Per the cross-phase Aging Policy added in v2 (gap doc §B "Aging /
> archival policy"): support tasks open more than 180 days enter weekly
> PM review with Rinaldo; tasks open more than 365 days require an
> explicit archive-or-keep decision. Document the decision on the task
> before archiving.
>
> **B.9. Ongoing Health Review**
>
> Quarterly, review every active support client against the portfolio
> health categories from `02_portfolio_health.md` (green / yellow /
> red). Red clients are escalated for either a recovery plan or an
> archive/park decision. This prevents the "5 client lists with ≥20
> tasks have 0% completion" pattern from recurring.

**COMMUNICATION - STAKEHOLDER UPDATES**

|  |  |  |  |
|:---|:---|:---|:---|
| **Type** | **Frequency** | **Audience** | **Channel** |
| Post-Launch Check-in | Weekly (first 4 weeks) | Client | Email |
| Training Session | Once (within first 2 weeks) | Client + PM | Google Meet |
| 30-Day Analytics Review | Once (at 30 days) | Client + PM | Email + Google Meet (optional) |
| Warranty-Exit Notification (Day 90) | Once | Client | Email |
| Internal Retrospective | Once | Full Project Team | Google Meet |
| Project Closure Email | Once (at project end) | Client | Email |
| Team Closure Notification | Once (at project end) | Full Team | Slack |
| **Weekly Support Follow-Up** | **Weekly (Day 90+, ongoing)** | **Client (active support clients)** | **Email + ClickUp** |
| **Marketing Handoff Confirmation** | **Once per client** | **Marketing team + Rinaldo** | **Slack + ClickUp task** |
| **Quarterly Portfolio Health Review** | **Quarterly** | **Rinaldo + Carlos + Asya** | **Google Meet + Google Docs** |

**ESCALATION - BLOCKED PHASE PROTOCOL**

|  |  |  |  |
|:---|:---|:---|:---|
| **Trigger** | **Timeframe** | **Escalation Action** | **Escalated To** |
| Critical post-launch bug affecting revenue | Immediately | Emergency fix; all hands response | Asya + Narine + Rinaldo |
| Client dissatisfied with final product | During survey or check-in | Schedule meeting to understand concerns; develop resolution plan | Rinaldo + Harry |
| Security vulnerability discovered | Immediately | Patch immediately; notify client; document incident | Asya + Narine + Rinaldo |
| Client requesting out-of-scope work during warranty | As encountered | Clarify warranty scope; offer Change Order or maintenance agreement | Rinaldo |
| Post-launch performance degradation | Within 24 hours of detection | Diagnose cause; optimize or roll back recent changes | Asya + Narine |
| **Support task open >14 days without resolution** | Per weekly review | **Surface in PM review; written plan-to-resolve within 2 business days** | **Rinaldo** |
| **Support task with >5 comments and no resolution** | Per weekly review | **Senior reviewer reassigns or re-scopes the task** | **Rinaldo** |
| **Support task open >180 days** | Weekly | **Aging review; archive-or-keep decision** | **Rinaldo** |
| **Marketing handoff stalled (no acceptance after 30 days)** | Day 60 post-warranty | **Joint Web Dev + Marketing meeting to clarify handoff blockers** | **Rinaldo + Marketing lead** |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **Successful Site Launch** | P9 - Launch | Cannot begin post-launch without live site |
| **Client Sign-Off on Final Site** | P8 - Client Approval | Warranty period begins from launch date |
| **All Project Documentation** | All Previous Phases | Need complete project history for closure documentation |
| **Analytics Access** | P1 - Client Onboarding / P6 - Development | Need analytics configured to generate 30-day report |
| **Maintenance Agreement Decision** | P10 Sub-Section A.9 | Determines SLAs that govern Sub-Section B |
| **Marketing Team Capacity to Accept Handoff** | External (Marketing team) | Without acceptance, client stays on Web Dev outbound longer |

**REVISION LIMITS & SCOPE CONTROL**

Post-Launch Bug Fixes: 90-day warranty covers bugs and development
defects from original scope; does not cover client-caused issues, new
requests, or third-party app/integration regressions outside scope.

Training: 1 training session included (up to 2 hours); additional
training sessions available at hourly rate.

Documentation: Standard admin guide included; custom technical
documentation beyond standard scope available at hourly rate.

Ongoing Support (Day 90+): Without a maintenance agreement, support is
best-effort against the SLAs in Step B.4. With a maintenance
agreement, the contract SLAs govern. Net-new feature work always
requires a Change Order.

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

**PHASE GATE - COMPLETION CHECKLIST**

*ALL items in Sub-Section A must be completed to formally close the
project. Sub-Section B items establish the ongoing-support steady
state; they recur indefinitely while the client remains in support.*

**Sub-Section A — Warranty Period (Day 0–90) Completion**

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **A1** | All post-launch bugs resolved within warranty period |  |  |
| **A2** | Client training session conducted and recorded |  |  |
| **A3** | Website Admin Guide delivered to client |  |  |
| **A4** | Credentials and access document completed and shared securely |  |  |
| **A5** | Integration documentation completed |  |  |
| **A6** | 30-day analytics baseline report delivered |  |  |
| **A7** | Internal retrospective conducted and documented |  |  |
| **A8** | Project Closure Report completed |  |  |
| **A9** | Maintenance agreement presented (if applicable) |  |  |
| **A10** | Client satisfaction survey sent and (ideally) received |  |  |
| **A11** | All ClickUp project tasks marked complete |  |  |
| **A12** | Project workspace archived |  |  |
| **A13** | Final thank-you email sent to client |  |  |
| **A14** | Slack notification posted confirming project closure |  |  |

**Sub-Section B — Ongoing Support (Day 90+) Standing Gate**

*These items must be true at the warranty-exit transition. Items B3–B5
are continuously enforced for as long as the client remains an active
support client.*

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **B1** | Ongoing support cadence set with named owner (Fancy Lab + client side) |  |  |
| **B2** | Warranty-exit notification email sent to client |  |  |
| **B3** | `Weekly Support Follow Ups` checklist instantiated and recurring |  |  |
| **B4** | Support intake convention documented (`SUPPORT` list and `support` / `ticket` tag) |  |  |
| **B5** | Escalation thresholds (>14 days, >5 comments) configured for ClickUp review |  |  |
| **B6** | Retention incentive issued (`Give client 1 month free of Base Plan`) |  |  |
| **B7** | Marketing handoff either completed or scheduled (`Ascend Proposals to Marketing`) |  |  |
| **B8** | Aging policy applied (no untouched support task >180 days without review) |  |  |

**Phase Gate Sign-Off**

|                        |                                                                       |          |
|:-----------------------|:----------------------------------------------------------------------|:---------|
| **Field**              | **Details**                                                           | **Date** |
| **Project Name**       |                                                                       |          |
| **Approved By**        |                                                                       |          |
| **Client Rep**         |                                                                       |          |
| **Next Phase**         | Project Closed / Maintenance Agreement / Ongoing Support (Sub-Section B) |          |
| **Notes / Conditions** |                                                                       |          |

## Data Enrichment (ClickUp export, 2026-04-22)

- **P10 v1 was only a small slice of actual post-launch reality.** The `SUPPORT` folder in ClickUp has **262 tasks**, and the checklist item `Weekly Support Follow Ups` recurs **42×** — i.e., the team is doing ongoing support that extends well beyond P10 v1's 30-day warranty concept. v2 absorbs this scope into Sub-Section B.
- **`MARKETING` folder has 303 tasks** — these look like post-launch marketing work (the handoff the launch checklist calls `Ascend Proposals to Marketing`) and previously had no SOP defining the boundary between Web Development and Marketing. v2 defines the trigger and handoff packet in Step B.7.
- **MAGENTO folder (3 tasks) exists** but no Magento work appears in the SOPs — either a dead folder or a one-off that should be merged into SUPPORT. Flag for triage in the next portfolio review.
- **Oldest open tasks in the export are post-launch remediation.** `1800loosediamonds.com` has tasks open since 2020 ("Each product should be its own sku," 1,998 days). These clearly exceeded P10 v1 scope; the new aging policy in Step B.8 + escalation thresholds in Step B.5 are designed to prevent this pattern from recurring.
- **Two retention items moved here from P9 v2 launch:** `Give client 1 month free of Base Plan` (39× in launch checklist) and `Ascend Proposals to Marketing` (42×). They are retention/handoff actions, not launch-sprint actions, and they were distorting launch-phase metrics where they previously lived.

---

**APPENDIX A: PROJECT CLOSURE & CLIENT HANDOFF PACKAGE**

*This comprehensive handoff package documents everything the client
needs to independently manage their website, all credentials and access
information, the 90-day warranty terms, and the formal project closure.
It also captures the internal retrospective for team improvement.*

*Prerequisites: P9 Launch — 48-hour monitoring complete with no critical
issues. All post-launch bugs from monitoring period resolved.*

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 65%" />
</colgroup>
<tbody>
<tr>
<td colspan="2"><strong>1. 90-DAY POST-LAUNCH WARRANTY
TRACKER</strong></td>
</tr>
<tr>
<td><strong>Warranty Start Date</strong></td>
<td><em>Launch date: ___ / Warranty expires (Day 90): ___</em></td>
</tr>
<tr>
<td><strong>Warranty Scope</strong></td>
<td><em>Covers: Bug fixes from original scope / Does NOT cover: New
features, content changes, design changes, third-party app
issues</em></td>
</tr>
<tr>
<td><strong>Bug Report Channel</strong></td>
<td><em>Client reports issues to: ___ / Response SLA: ___ business
hours</em></td>
</tr>
<tr>
<td><strong>Bug #1</strong></td>
<td><em>Date: ___ / Description: ___ / Severity: ___ / Fixed: [ ] / Date
fixed: ___</em></td>
</tr>
<tr>
<td><strong>Bug #2</strong></td>
<td><em>Date: ___ / Description: ___ / Severity: ___ / Fixed: [ ] / Date
fixed: ___</em></td>
</tr>
<tr>
<td><strong>Bug #3</strong></td>
<td><em>Date: ___ / Description: ___ / Severity: ___ / Fixed: [ ] / Date
fixed: ___</em></td>
</tr>
<tr>
<td><strong>Additional Bugs</strong></td>
<td><em>Document in ClickUp — Total reported: ___ / Total resolved: ___
/ Outstanding: ___</em></td>
</tr>
<tr>
<td><strong>Warranty Period Issues Summary</strong></td>
<td><em>Total issues: ___ / Average fix time: ___ / Client satisfaction:
___</em></td>
</tr>
<tr>
<td colspan="2"><strong>2. CLIENT TRAINING SESSION</strong></td>
</tr>
<tr>
<td><strong>Training Date</strong></td>
<td><em>Date: ___ / Duration: ___ / Format: Video call /
In-person</em></td>
</tr>
<tr>
<td><strong>Attendees (Client)</strong></td>
<td><em>Names and roles: ___</em></td>
</tr>
<tr>
<td><strong>Trainer (Fancy Lab)</strong></td>
<td><em>Name: ___</em></td>
</tr>
<tr>
<td><strong>Recording</strong></td>
<td><em>Session recorded: [ ] / Recording URL: ___ / Shared with client:
[ ]</em></td>
</tr>
<tr>
<td><strong>Topics Covered</strong></td>
<td><em>[ ] Shopify Admin overview [ ] Product management [ ] Order
processing [ ] Content editing [ ] Blog management [ ] Collection
management [ ] Discount creation [ ] Analytics overview [ ] App
management</em></td>
</tr>
<tr>
<td><strong>Product Management Training</strong></td>
<td><em>Add product: [ ] / Edit product: [ ] / Manage variants: [ ] /
Update inventory: [ ] / Manage images: [ ]</em></td>
</tr>
<tr>
<td><strong>Content Editing Training</strong></td>
<td><em>Edit pages: [ ] / Update sections: [ ] / Theme editor: [ ] /
Blog posting: [ ] / Menu editing: [ ]</em></td>
</tr>
<tr>
<td><strong>Order Processing Training</strong></td>
<td><em>View orders: [ ] / Fulfill orders: [ ] / Process refunds: [ ] /
Print labels: [ ] / Customer communication: [ ]</em></td>
</tr>
<tr>
<td><strong>Client Follow-Up Questions</strong></td>
<td><em>Questions raised during training: ___ / Answered: [ ] /
Documented in admin guide: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>3. WEBSITE ADMIN GUIDE (DELIVERED AS SEPARATE
DOCUMENT)</strong></td>
</tr>
<tr>
<td><strong>Admin Guide Created</strong></td>
<td><em>[ ] Format: PDF / Google Doc / Notion / Loom library — URL:
___</em></td>
</tr>
<tr>
<td><strong>Chapter 1: Getting Started</strong></td>
<td><em>Logging in, admin overview, navigation guide: [ ]</em></td>
</tr>
<tr>
<td><strong>Chapter 2: Product Management</strong></td>
<td><em>Adding, editing, deleting products, managing variants,
inventory: [ ]</em></td>
</tr>
<tr>
<td><strong>Chapter 3: Order Management</strong></td>
<td><em>Processing orders, refunds, fulfillment, shipping: [ ]</em></td>
</tr>
<tr>
<td><strong>Chapter 4: Content Editing</strong></td>
<td><em>Page editing, blog management, section editing, menu updates: [
]</em></td>
</tr>
<tr>
<td><strong>Chapter 5: Marketing Tools</strong></td>
<td><em>Discount codes, gift cards, email marketing, social media: [
]</em></td>
</tr>
<tr>
<td><strong>Chapter 6: Analytics &amp; Reporting</strong></td>
<td><em>Shopify analytics, GA4 overview, key metrics to monitor: [
]</em></td>
</tr>
<tr>
<td><strong>Chapter 7: Troubleshooting</strong></td>
<td><em>Common issues, who to contact, escalation: [ ]</em></td>
</tr>
<tr>
<td><strong>Guide Delivered to Client</strong></td>
<td><em>Delivered: [ ] / Date: ___ / Client confirmed receipt: [
]</em></td>
</tr>
<tr>
<td colspan="2"><strong>4. CREDENTIALS &amp; ACCESS
HANDOFF</strong></td>
</tr>
<tr>
<td><strong>Shopify Admin</strong></td>
<td><em>URL: ___ / Owner email transferred to client: [ ] / Collaborator
access cleaned up: [ ]</em></td>
</tr>
<tr>
<td><strong>Domain Registrar</strong></td>
<td><em>Provider: ___ / Account: ___ / Ownership with client: [
]</em></td>
</tr>
<tr>
<td><strong>Google Analytics (GA4)</strong></td>
<td><em>Property ID: ___ / Client has owner access: [ ] / Fancy Lab has
viewer access: [ ]</em></td>
</tr>
<tr>
<td><strong>Google Search Console</strong></td>
<td><em>Property: ___ / Client has owner access: [ ]</em></td>
</tr>
<tr>
<td><strong>Google Tag Manager</strong></td>
<td><em>Container ID: ___ / Client has admin access: [ ]</em></td>
</tr>
<tr>
<td><strong>Email Marketing Platform</strong></td>
<td><em>Platform: ___ / Account owner: ___ / Client has admin access: [
]</em></td>
</tr>
<tr>
<td><strong>Social Media Accounts</strong></td>
<td><em>Platforms: ___ / Pixel/tag IDs documented: [ ] / Client manages:
[ ]</em></td>
</tr>
<tr>
<td><strong>Third-Party Apps / Services</strong></td>
<td><em>List each: App: ___ / Account owner: Client [ ] / Billing:
Client [ ] / Documented: [ ]</em></td>
</tr>
<tr>
<td><strong>Git Repository (if applicable)</strong></td>
<td><em>Transferred to client: [ ] / Read-only access for client: [ ] /
Fancy Lab retains for support: [ ]</em></td>
</tr>
<tr>
<td><strong>Credentials Document Delivered</strong></td>
<td><em>Secure document with all access info: [ ] / Method: ___ / Client
confirmed: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>5. 30-DAY ANALYTICS BASELINE
REPORT</strong></td>
</tr>
<tr>
<td><strong>Report Period</strong></td>
<td><em>From: ___ / To: ___ (30 days post-launch)</em></td>
</tr>
<tr>
<td><strong>Total Sessions</strong></td>
<td><em>Sessions: ___ / Users: ___ / New users: ___</em></td>
</tr>
<tr>
<td><strong>Traffic Sources</strong></td>
<td><em>Organic: ___% / Direct: ___% / Social: ___% / Referral: ___% /
Paid: ___%</em></td>
</tr>
<tr>
<td><strong>Top Landing Pages</strong></td>
<td><em>1) ___ 2) ___ 3) ___ 4) ___ 5) ___</em></td>
</tr>
<tr>
<td><strong>Device Breakdown</strong></td>
<td><em>Desktop: ___% / Mobile: ___% / Tablet: ___%</em></td>
</tr>
<tr>
<td><strong>E-Commerce Metrics</strong></td>
<td><em>Conversion rate: ___% / Revenue: $___ / Average order value:
$___ / Total orders: ___</em></td>
</tr>
<tr>
<td><strong>Page Speed (30-day avg)</strong></td>
<td><em>Desktop LCP: ___s / Mobile LCP: ___s / CLS: ___ / INP:
___ms</em></td>
</tr>
<tr>
<td><strong>SEO Indexing Status</strong></td>
<td><em>Pages indexed in Google: ___ / Impressions: ___ / Clicks: ___ /
Avg position: ___</em></td>
</tr>
<tr>
<td><strong>Comparison to Pre-Launch</strong></td>
<td><em>Traffic change: ___% / Conversion change: ___% / Bounce rate
change: ___% / Speed improvement: ___</em></td>
</tr>
<tr>
<td><strong>Recommendations</strong></td>
<td><em>Top 3 optimization opportunities identified: 1) ___ 2) ___ 3)
___</em></td>
</tr>
<tr>
<td colspan="2"><strong>6. INTERNAL RETROSPECTIVE (FANCY LAB
ONLY)</strong></td>
</tr>
<tr>
<td><strong>Retrospective Date</strong></td>
<td><em>Date: ___ / Facilitator: ___ / Attendees: ___</em></td>
</tr>
<tr>
<td><strong>What Went Well</strong></td>
<td><em>List top 3-5 successes: ___</em></td>
</tr>
<tr>
<td><strong>What Could Be Improved</strong></td>
<td><em>List top 3-5 improvement areas: ___</em></td>
</tr>
<tr>
<td><strong>Timeline Accuracy</strong></td>
<td><em>Estimated: ___ weeks / Actual: ___ weeks / Variance: ___ /
Cause: ___</em></td>
</tr>
<tr>
<td><strong>Budget Accuracy</strong></td>
<td><em>Estimated hours: ___ / Actual hours: ___ / Variance: ___% /
Cause: ___</em></td>
</tr>
<tr>
<td><strong>Client Relationship</strong></td>
<td><em>Communication quality: 1-5 / Responsiveness: 1-5 / Scope creep:
None / Moderate / Significant</em></td>
</tr>
<tr>
<td><strong>Process Improvements</strong></td>
<td><em>SOPs to update: ___ / New templates needed: ___ / Tools to
add/remove: ___</em></td>
</tr>
<tr>
<td><strong>Team Performance Notes</strong></td>
<td><em>Shoutouts: ___ / Growth areas: ___ / Training needs:
___</em></td>
</tr>
<tr>
<td colspan="2"><strong>7. MAINTENANCE AGREEMENT (IF
APPLICABLE)</strong></td>
</tr>
<tr>
<td><strong>Maintenance Offered?</strong></td>
<td><em>Yes / No / Client Declined — Date discussed: ___</em></td>
</tr>
<tr>
<td><strong>Maintenance Tier</strong></td>
<td><em>Basic (updates only) / Standard (updates + minor changes) /
Premium (dedicated hours) — Selected: ___</em></td>
</tr>
<tr>
<td><strong>Monthly Hours Included</strong></td>
<td><em>Hours: ___ / Rollover: Yes / No / Overage rate:
$___/hr</em></td>
</tr>
<tr>
<td><strong>Monthly Fee</strong></td>
<td><em>$___ / Billing cycle: Monthly / Quarterly / Annual — Start date:
___</em></td>
</tr>
<tr>
<td><strong>Scope of Maintenance</strong></td>
<td><em>[ ] Shopify updates [ ] App updates [ ] Security patches [ ]
Content changes [ ] Bug fixes [ ] Performance monitoring [ ] Analytics
reporting</em></td>
</tr>
<tr>
<td><strong>Response SLA</strong></td>
<td><em>Critical: ___ hours / Standard: ___ business days / Feature
requests: ___ business days</em></td>
</tr>
<tr>
<td><strong>Agreement Signed</strong></td>
<td><em>[ ] Signed by client [ ] Signed by Fancy Lab — Date: ___ /
Document URL: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>8. FORMAL PROJECT CLOSURE</strong></td>
</tr>
<tr>
<td><strong>All Deliverables Completed</strong></td>
<td><em>Every phase gate item from P0-P9 verified complete: [
]</em></td>
</tr>
<tr>
<td><strong>Client Satisfaction Survey</strong></td>
<td><em>Sent: [ ] / Completed: [ ] / Score: ___/10 / Testimonial
provided: [ ]</em></td>
</tr>
<tr>
<td><strong>Case Study Permission</strong></td>
<td><em>Client approved case study: [ ] / Portfolio use: [ ] /
Before/after screenshots: [ ]</em></td>
</tr>
<tr>
<td><strong>Final Invoice</strong></td>
<td><em>All project billing complete: [ ] / Outstanding: $0 [ ] /
Payment received: [ ]</em></td>
</tr>
<tr>
<td><strong>Internal Access Cleaned Up</strong></td>
<td><em>Removed Fancy Lab staff from client accounts not needed for
maintenance: [ ]</em></td>
</tr>
<tr>
<td><strong>ClickUp Board Archived</strong></td>
<td><em>Project board archived: [ ] / Date: ___ / Accessible for
reference: [ ]</em></td>
</tr>
<tr>
<td><strong>Google Drive Organized</strong></td>
<td><em>All final files in correct folders: [ ] / Naming conventions
followed: [ ]</em></td>
</tr>
<tr>
<td><strong>Project Closure Email Sent</strong></td>
<td><em>Sent to client: [ ] / Includes: Thank you, warranty info,
maintenance info, support contact / Date: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>9. ONGOING SUPPORT TRANSITION (DAY 90+)</strong></td>
</tr>
<tr>
<td><strong>Warranty Exit Date</strong></td>
<td><em>Day 90 from launch: ___ / Notification email sent: [ ]</em></td>
</tr>
<tr>
<td><strong>Support Owner (Fancy Lab)</strong></td>
<td><em>Client-facing: ___ (default Carlos) / Technical: ___ (default Asya) / Accountable: Rinaldo</em></td>
</tr>
<tr>
<td><strong>Support Owner (Client)</strong></td>
<td><em>Name: ___ / Email: ___</em></td>
</tr>
<tr>
<td><strong>Intake Convention</strong></td>
<td><em>Dedicated SUPPORT list: [ ] / Tag in client list — `support` [ ] / `ticket` [ ]</em></td>
</tr>
<tr>
<td><strong>Weekly Support Follow-Up</strong></td>
<td><em>Recurring checklist instantiated: [ ] / Cadence: weekly / First run date: ___</em></td>
</tr>
<tr>
<td><strong>Retention Incentive Issued</strong></td>
<td><em>1 month free of Base Plan applied: [ ] / Confirmed to client (date): ___</em></td>
</tr>
<tr>
<td><strong>Marketing Handoff</strong></td>
<td><em>`Ascend Proposals to Marketing` task: created [ ] / accepted by Marketing [ ] / handoff date: ___</em></td>
</tr>
<tr>
<td><strong>Escalation Thresholds Configured</strong></td>
<td><em>>14 days: [ ] / >5 comments: [ ] / Surfaces in PM weekly review: [ ]</em></td>
</tr>
<tr>
<td><strong>Aging Policy Acknowledged</strong></td>
<td><em>>180 days → weekly PM review: [ ] / >365 days → archive-or-keep decision: [ ]</em></td>
</tr>
</tbody>
</table>

**Project Closure Sign-Off**

By signing below, both parties confirm that all project deliverables
have been completed, all access and credentials have been transferred,
and the project is formally closed (warranty period). Ongoing support,
if any, continues per Sub-Section B and is governed by either the
maintenance agreement or the default SLAs in Step B.4.

Project Manager:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Account Director:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Client Representative:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

*This project is now formally closed. Thank you for choosing Fancy Lab.
We look forward to a continued partnership through our ongoing support
relationship.*
