**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P8**

**CLIENT REVIEW & PRE-LAUNCH**

Standard Operating Procedure & Phase Gate Document

v2.0 \| April 2026 \| Confidential

**REVISION HISTORY / CHANGELOG**

- **v2.0 (April 2026)** — Codified the "Client Approval > 30 days" escalation ladder (Day 7 / 14 / 21 / 30) per `data/analysis/03_sop_gap_and_recommendations.md` section C and `02_portfolio_health.md` red-list. Added the `Client Approval → Client Stall → Parked` ClickUp status flow and the `client-block` routing tag.
- Added a new Phase Gate item (#13): "No open Client Approval task older than 30 days, or else `Client Stall` status applied."
- Reinforced RACI ownership: Carlos Responsible for cadence reminders (Day 7, Day 14); Rinaldo Accountable for Day 21 / Day 30 escalation decisions.
- Appended `## Data Enrichment (ClickUp export, 2026-04-22)` section porting evidence from `Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md` (lines 545–550).
- **Rollout action:** apply v2 escalation retroactively to four red clients identified in `02_portfolio_health.md` — `breadiamonddirect.com` (8 Client Approval tasks, oldest 862d), `ian.club` (7 tasks, oldest 457d), `Select Dental` (14 Client Approval + 38 Backlog), `barclaysjewelers.com` (55 Open, 580d oldest).
- Confirmed RACI alignment with observed practice: Carlos owns client-facing cadence end-to-end (184 tasks total per `03_sop_gap_and_recommendations.md` section A); Rinaldo retains accountability for park/unblock decisions.

**PURPOSE & SCOPE**

This SOP defines the standard process for presenting the completed
website to the client for review, collecting structured feedback,
implementing approved revisions, and obtaining formal sign-off that the
site is ready for launch.

**Phase Objective**

Obtain written client approval on the completed website, resolve all
client-requested revisions within the contracted scope, and secure
formal launch authorization before proceeding to the launch phase.

**Scope Includes**

> \- Client staging site access and walkthrough
>
> \- Structured feedback collection process
>
> \- Client revision implementation (within contract limits)
>
> \- Content corrections and final copy updates
>
> \- Final client walkthrough after revisions
>
> \- Formal written sign-off / launch approval
>
> \- Known issue disclosure and documentation
>
> \- Stalled-approval escalation ladder (Day 7 / 14 / 21 / 30)

**Scope Excludes**

> \- New feature requests (require Change Order)
>
> \- Redesign of approved pages (require Change Order)
>
> \- Additional QA rounds beyond what revisions require
>
> \- Training or documentation (covered in P10 - Post Launch)
>
> \- DNS or hosting changes (covered in P9 - Launch)

**WHO - RACI MATRIX**

|  |  |  |
|:---|:---|:---|
| **Role** | **Person(s)** | **Responsibility** |
| **Responsible** | Carlos | *Performs the work for this phase; owns Day 7 and Day 14 cadence reminders* |
| **Accountable** | Rinaldo | *Ultimately answerable for completion; owns Day 21 escalation and Day 30 park/unblock decision* |
| **Consulted** | Asya + Aida + Narine | *Provides input and approves deliverables* |
| **Informed** | Harry | *Kept up to date on progress; looped in at Day 21+ on at-risk accounts* |

**WHAT - DELIVERABLES**

|                                       |                         |           |
|:--------------------------------------|:------------------------|:----------|
| **Deliverable**                       | **Format / Location**   | **Owner** |
| **Client Review Guide**               | Google Docs / Email     | Carlos    |
| **Staging Site Access (credentials)** | Email                   | Carlos    |
| **Client Feedback Log**               | ClickUp / Google Sheets | Carlos    |
| **Revision Implementation Report**    | ClickUp                 | Asya      |
| **Known Issues Disclosure**           | Google Docs             | Asya      |
| **Formal Client Sign-Off Document**   | PandaDoc / Google Docs  | Carlos    |
| **Stall Escalation Brief (Day 21)**   | Google Docs / Slack DM  | Carlos → Rinaldo |

**WHERE - TOOLS & PLATFORMS**

|  |  |
|:---|:---|
| **Tool** | **Purpose in This Phase** |
| **Google Meet** | Client walkthrough presentations; Day 14 unblock call |
| **ClickUp** | Feedback tracking, revision task management, `Client Approval → Client Stall → Parked` status flow, `client-block` tag |
| **PandaDoc / Google Docs** | Formal sign-off document |
| **Slack** | Internal coordination on revisions; Day 21 escalation thread |
| **Email** | Client communication, staging access, review guides, Day 7/14 reminders |
| **Loom (optional)** | Video walkthroughs of specific features or pages |

**HOW - PROCESS STEPS**

> **1. Prepare Client Review Package**
>
> Before sharing the staging site, prepare: a Client Review Guide
> document explaining how to review the site (device recommendations,
> what to look for, how to provide feedback), staging site URL and
> credentials, a list of completed features and pages, any known issues
> or intentional design decisions to set expectations, and the revision
> policy (number of rounds, what constitutes a revision vs. new scope).
>
> **2. Send Staging Access to Client**
>
> Email the client the staging site access along with the Client Review
> Guide. Request they review on both desktop and mobile. Set a clear
> deadline for feedback submission (typically 5 business days). Include
> instructions on how to document feedback (page, section, description
> of requested change). Set the ClickUp task status to `Client Approval`
> and stamp the deliverable submission date — the escalation clock
> starts here (see Step 10).
>
> **3. Conduct Client Walkthrough Meeting**
>
> Schedule and conduct a live walkthrough of the staging site with the
> client. Present page by page: desktop and mobile views, interactive
> features, e-commerce flow (if applicable), third-party integrations in
> action. Answer questions in real-time. Record the meeting for
> reference.
>
> **4. Collect and Categorize Client Feedback**
>
> Compile all client feedback into a structured log. Categorize each
> item as: Content Change (text, image swap), Bug Fix (something not
> working as designed), Design Revision (within contracted scope), New
> Feature/Scope Change (requires Change Order), or Clarification Needed.
> Share the categorized list with the client for confirmation.
>
> **5. Implement Approved Revisions**
>
> Assign revision tasks to the appropriate team members (dev for bugs,
> content for copy, design for visual). Track progress in ClickUp. For
> each revision: implement the change, verify it works, mark as
> complete. If a requested change is out of scope, communicate this to
> the client with a Change Order option.
>
> **6. Conduct QA on Revisions**
>
> After all revisions are implemented, perform targeted QA on changed
> areas. Check that revisions are correct and haven't introduced new
> issues. Perform basic regression testing on surrounding
> pages/features.
>
> **7. Final Client Walkthrough**
>
> Present the revised site to the client, highlighting all changes made.
> Walk through the feedback log showing each item addressed. Disclose
> any remaining known issues (Low priority from QA) with explanation.
> Confirm the client is satisfied with the result.
>
> **8. Obtain Formal Sign-Off**
>
> Send the client a formal Launch Approval document via PandaDoc or
> Google Docs. The document should confirm: the client has reviewed the
> site, all agreed revisions have been implemented, any known issues
> have been disclosed and accepted, and the client authorizes the team
> to proceed with launch. Obtain electronic signature or written email
> confirmation.
>
> **9. Notify Team of Launch Readiness**
>
> Once sign-off is received, update ClickUp with launch-ready status.
> Post in Slack: client approval received, any final notes or
> conditions, and that the project is cleared for P9 - Launch.
>
> **10. Run the Stalled-Approval Cadence (NEW in v2)**
>
> Whenever a deliverable is sent to the client (Step 2 or Step 7) and
> a `Client Approval` task is opened in ClickUp, Carlos runs the
> escalation ladder defined in **Appendix B** without waiting for a
> manual trigger. The ladder fires automatically off the task's
> "deliverable submitted" date. Tag the task `client-block` the moment
> any reminder is sent so reporting can roll up at-risk accounts.

**COMMUNICATION - STAKEHOLDER UPDATES**

|  |  |  |  |
|:---|:---|:---|:---|
| **Type** | **Frequency** | **Audience** | **Channel** |
| Staging Access Email | Once | Client | Email |
| Client Walkthrough Meeting | 1-2 times (initial + post-revision) | Client + PM + Relevant Team | Google Meet |
| Feedback Categorization Review | Once (after feedback received) | Client + PM | Email / Google Meet |
| Revision Status Updates | As needed during revisions | Client | Email |
| **Day 7 Reminder** | Once per stalled deliverable | Client | Email + ClickUp comment |
| **Day 14 Unblock Offer** | Once per stalled deliverable | Client | Email + Google Meet invite |
| **Day 21 Escalation Brief** | Once per stalled deliverable | Rinaldo (cc Harry) | Slack DM + Google Doc |
| **Day 30 Stall Decision** | Once per stalled deliverable | Rinaldo + Harry + Carlos | Slack thread + ClickUp status change |
| Launch Readiness Notification | Once (at phase close) | Full Team | Slack |

**ESCALATION - BLOCKED PHASE PROTOCOL**

|  |  |  |  |
|:---|:---|:---|:---|
| **Trigger** | **Timeframe** | **Escalation Action** | **Escalated To** |
| Client not providing feedback | 5 business days after staging access | Send reminder with review deadline | Carlos |
| Feedback still not received | 10 business days | Escalate to PM; schedule direct call | Rinaldo |
| Client requests changes beyond contracted revisions | Immediately | Notify PM; prepare Change Order with additional costs and timeline | Rinaldo |
| Client refuses to sign off | After 2 revision rounds | Schedule meeting to identify specific concerns; involve account lead | Rinaldo + Harry |
| Scope creep disguised as revisions | During feedback categorization | Clearly communicate what is in-scope vs. Change Order territory | Rinaldo |
| Client wants to delay launch indefinitely | 14 business days after sign-off request | Discuss project closure options and maintenance agreement | Harry + Rinaldo |
| **Client Approval task aging > 30 calendar days** | **Day 30** | **Apply `Client Stall` status; if no executed unblock plan within 7 more days, move project to `PARKED` folder** | **Rinaldo (decision) + Carlos (execution)** |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **QA Sign-Off Report** | P7 - Testing & QA | Cannot present to client without internal QA completion |
| **Staging Site (functional and tested)** | P6 - Development + P7 - QA | Client needs a stable site to review |
| **Original Signed Contract (revision limits)** | P0 - Discovery & Sales | Need to reference contracted revision rounds |
| **Approval Authority Map** | P1 - Client Onboarding (gate item #5) | Without the correctly mapped approver, reminders go to the wrong person and the escalation ladder misfires |

**REVISION LIMITS & SCOPE CONTROL**

Client Revisions: Up to 2 rounds of revisions included per contract;
additional rounds require Change Order

Content Corrections: Typo and text corrections unlimited; new content or
rewriting requires Change Order

Bug Fixes: All bugs are fixed regardless of revision count (development
defects are not counted as revisions)

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

**PHASE GATE - COMPLETION CHECKLIST**

*ALL items below must be completed before the project can advance to
P9 - Launch. The site must not go live without formal written client
approval.*

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **1** | Client Review Guide sent with staging access |  |  |
| **2** | Client walkthrough meeting conducted |  |  |
| **3** | All client feedback collected and categorized |  |  |
| **4** | Out-of-scope items communicated (Change Orders if applicable) |  |  |
| **5** | All approved revisions implemented |  |  |
| **6** | QA on revisions completed (no new Critical/High bugs) |  |  |
| **7** | Final client walkthrough conducted |  |  |
| **8** | Known issues disclosed and accepted by client |  |  |
| **9** | Formal written client sign-off received |  |  |
| **10** | Launch Approval document signed |  |  |
| **11** | ClickUp tasks updated to launch-ready status |  |  |
| **12** | Slack notification posted confirming client approval and launch readiness |  |  |
| **13** | **No open Client Approval task older than 30 days, or else `Client Stall` status applied and Day 30 decision logged** |  |  |

**Phase Gate Sign-Off**

|                        |             |          |
|:-----------------------|:------------|:---------|
| **Field**              | **Details** | **Date** |
| **Project Name**       |             |          |
| **Approved By**        |             |          |
| **Client Rep**         |             |          |
| **Next Phase**         | P9 - Launch |          |
| **Notes / Conditions** |             |          |

## Data Enrichment (ClickUp export, 2026-04-22)

- **`client approval` status has 84 tasks**, unevenly distributed: `Select Dental` 14 · `Steindiamonds.com` 8 · `breadiamonddirect.com` 8 · `ian.club` 7 · `divinitymetals.com` 6 · `naimies.com` 6 · `OverstockCellars.com` 4 · `christopher-salon.com` 2 · others. The fact that 7/8 of `breadiamonddirect.com`'s non-completed tasks are in client approval but the list has **0% completion** is the single clearest bottleneck in the portfolio — clients are receiving approval packages but not returning sign-off.
- **Oldest "client approval" items are 400+ days old.** This is a hard escalation trigger that v1 P8 didn't quantify — v2 codifies it as: "Client Approval > 30 days → PM escalation; > 90 days → Rinaldo decision on parking the project." See Appendix B for the operational ladder.
- **v2 rollout action.** Apply the new escalation retroactively to the four red-list accounts cited in `data/analysis/02_portfolio_health.md`: `breadiamonddirect.com` (oldest 862d), `ian.club` (oldest 457d), `Select Dental` (14 Client Approval + 38 Backlog), `barclaysjewelers.com` (55 Open, 580d oldest). Carlos to triage each within 5 business days of v2 publication; Rinaldo to make the park/restart call by Day 30 of triage.

**APPENDIX A: CLIENT REVIEW GUIDE & FORMAL SIGN-OFF FORM**

*This document serves two purposes: (1) A structured review guide for
the client to systematically evaluate the staging site, and (2) A formal
sign-off form that authorizes the website for production launch. Both
sections must be completed before proceeding to launch.*

*Prerequisites: P7 QA must be complete — all critical/major bugs
resolved, performance targets met, QA lead has signed off.*

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 65%" />
</colgroup>
<tbody>
<tr>
<td colspan="2"><strong>1. REVIEW ACCESS &amp;
INSTRUCTIONS</strong></td>
</tr>
<tr>
<td><strong>Staging Site URL</strong></td>
<td><em>URL: ___</em></td>
</tr>
<tr>
<td><strong>Password (if applicable)</strong></td>
<td><em>Password: ___</em></td>
</tr>
<tr>
<td><strong>Review Start Date</strong></td>
<td><em>Date sent to client: ___ / Review deadline: ___</em></td>
</tr>
<tr>
<td><strong>Client Reviewers</strong></td>
<td><em>Name(s) and role(s) of everyone reviewing: ___</em></td>
</tr>
<tr>
<td><strong>Review Instructions Sent</strong></td>
<td><em>[ ] Email with review guide [ ] Video walkthrough [ ] Live
review meeting scheduled — Date: ___</em></td>
</tr>
<tr>
<td><strong>Feedback Submission Method</strong></td>
<td><em>How should the client submit feedback? Figma / Email / Shared
doc / ClickUp / Loom videos: ___</em></td>
</tr>
<tr>
<td><strong>Feedback Consolidation Contact</strong></td>
<td><em>Who consolidates all client feedback into one document? (from
P1): ___</em></td>
</tr>
<tr>
<td><strong>Feedback Deadline</strong></td>
<td><em>All feedback must be received by: ___ / SLA: ___ business days
(from P1)</em></td>
</tr>
<tr>
<td colspan="2"><strong>2. CLIENT REVIEW CHECKLIST — PAGE BY
PAGE</strong></td>
</tr>
<tr>
<td><strong>Homepage</strong></td>
<td><em>[ ] Hero section [ ] Content accurate [ ] Images correct [ ]
CTAs work [ ] Mobile view — Notes: ___</em></td>
</tr>
<tr>
<td><strong>Navigation</strong></td>
<td><em>[ ] All links work [ ] Structure matches agreement [ ] Mobile
menu — Notes: ___</em></td>
</tr>
<tr>
<td><strong>Collection Pages</strong></td>
<td><em>[ ] Products display correctly [ ] Filters work [ ] Sorting
works [ ] Mobile view — Notes: ___</em></td>
</tr>
<tr>
<td><strong>Product Pages</strong></td>
<td><em>[ ] Descriptions accurate [ ] Prices correct [ ] Variants work [
] Images correct [ ] Add to cart — Notes: ___</em></td>
</tr>
<tr>
<td><strong>Cart &amp; Checkout</strong></td>
<td><em>[ ] Cart updates correctly [ ] Discount codes work [ ] Checkout
flow smooth — Notes: ___</em></td>
</tr>
<tr>
<td><strong>About Page</strong></td>
<td><em>[ ] Content accurate [ ] Images correct [ ] Team info (if
applicable) — Notes: ___</em></td>
</tr>
<tr>
<td><strong>Contact Page</strong></td>
<td><em>[ ] Form works [ ] Info accurate [ ] Map correct (if applicable)
— Notes: ___</em></td>
</tr>
<tr>
<td><strong>Blog (if applicable)</strong></td>
<td><em>[ ] Posts display correctly [ ] Categories work [ ] Author info
— Notes: ___</em></td>
</tr>
<tr>
<td><strong>Legal Pages</strong></td>
<td><em>[ ] Privacy Policy [ ] Terms of Service [ ] Return Policy [ ]
Shipping Policy — Reviewed by legal? [ ]</em></td>
</tr>
<tr>
<td><strong>Custom Pages</strong></td>
<td><em>List each page: ___ / Reviewed: [ ] / Notes: ___</em></td>
</tr>
<tr>
<td><strong>Footer</strong></td>
<td><em>[ ] Links work [ ] Newsletter signup [ ] Social media links [ ]
Contact info — Notes: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>3. CONTENT ACCURACY VERIFICATION</strong></td>
</tr>
<tr>
<td><strong>Company Name / Branding</strong></td>
<td><em>Correct everywhere: [ ] / Logo placement: [ ] / Favicon: [
]</em></td>
</tr>
<tr>
<td><strong>Contact Information</strong></td>
<td><em>Phone: [ ] / Email: [ ] / Address: [ ] / Hours: [ ] — All
accurate: [ ]</em></td>
</tr>
<tr>
<td><strong>Product Information</strong></td>
<td><em>Prices: [ ] / Descriptions: [ ] / Specs: [ ] / Availability: [ ]
— Spot-checked ___% of catalog</em></td>
</tr>
<tr>
<td><strong>Legal Compliance</strong></td>
<td><em>Privacy policy accurate: [ ] / Terms current: [ ] / Cookie
consent: [ ] / Age gate (if needed): [ ]</em></td>
</tr>
<tr>
<td><strong>Spelling &amp; Grammar</strong></td>
<td><em>Client has proofread all pages: [ ] / No typos found: [ ] /
Corrections documented: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>4. CLIENT FEEDBACK SUMMARY &amp;
RESOLUTION</strong></td>
</tr>
<tr>
<td><strong>Round 1 Feedback Received</strong></td>
<td><em>Date: ___ / Total items: ___ / Critical: ___ / Major: ___ /
Minor: ___</em></td>
</tr>
<tr>
<td><strong>Round 1 Changes Implemented</strong></td>
<td><em>Date completed: ___ / Items addressed: ___ of ___ / Items
deferred: ___</em></td>
</tr>
<tr>
<td><strong>Round 1 Deferred Items</strong></td>
<td><em>List items moved to post-launch or requiring change order:
___</em></td>
</tr>
<tr>
<td><strong>Round 2 Feedback Received</strong></td>
<td><em>Date: ___ / Total items: ___ / Critical: ___ / Major: ___ /
Minor: ___</em></td>
</tr>
<tr>
<td><strong>Round 2 Changes Implemented</strong></td>
<td><em>Date completed: ___ / Items addressed: ___ of ___ / Items
deferred: ___</em></td>
</tr>
<tr>
<td><strong>Additional Rounds (if applicable)</strong></td>
<td><em>Round ___: Feedback date: ___ / Items: ___ / Change order
approved: [ ] / Cost: ___</em></td>
</tr>
<tr>
<td><strong>All Feedback Resolved?</strong></td>
<td><em>Yes / No — Outstanding items: ___ / Agreed to launch with known
items? [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>5. KNOWN ISSUES DISCLOSURE</strong></td>
</tr>
<tr>
<td><strong>Known Issue 1</strong></td>
<td><em>Description: ___ / Severity: Low / Impact: ___ / Plan: Fix
post-launch by ___</em></td>
</tr>
<tr>
<td><strong>Known Issue 2</strong></td>
<td><em>Description: ___ / Severity: Low / Impact: ___ / Plan: Fix
post-launch by ___</em></td>
</tr>
<tr>
<td><strong>Known Issue 3</strong></td>
<td><em>Description: ___ / Severity: Low / Impact: ___ / Plan: Fix
post-launch by ___</em></td>
</tr>
<tr>
<td><strong>Client Acknowledges Known Issues</strong></td>
<td><em>[ ] Client has reviewed and accepts launching with the above
known issues</em></td>
</tr>
<tr>
<td colspan="2"><strong>6. PRE-LAUNCH CONFIRMATIONS</strong></td>
</tr>
<tr>
<td><strong>DNS Ready to Switch</strong></td>
<td><em>Domain: ___ / Current nameservers: ___ / DNS access confirmed: [
] / TTL reduced: [ ]</em></td>
</tr>
<tr>
<td><strong>SSL Certificate</strong></td>
<td><em>Type: Let's Encrypt / Shopify-managed / Custom — Status:
___</em></td>
</tr>
<tr>
<td><strong>Email Service Verified</strong></td>
<td><em>Email forwarding or transactional email configured: [ ] /
Tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Payment Processing Live</strong></td>
<td><em>Payment gateway: ___ / Switch from test to live mode: [ ] / Test
transaction: [ ]</em></td>
</tr>
<tr>
<td><strong>Preferred Launch Date</strong></td>
<td><em>Client's preferred launch date: ___ / Launch window:
___</em></td>
</tr>
<tr>
<td><strong>Launch Day Availability</strong></td>
<td><em>Client available during launch window: [ ] / Emergency contact:
___</em></td>
</tr>
<tr>
<td><strong>Old Site Backup Required?</strong></td>
<td><em>Yes / No — Backup method: ___ / Backup completed: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>7. FORMAL LAUNCH AUTHORIZATION</strong></td>
</tr>
<tr>
<td><strong>Sign-Off Statement</strong></td>
<td><em>I have reviewed the staging website and authorize Fancy Lab to
proceed with the production launch. I understand that post-launch
changes beyond the 30-day warranty period will require a separate
agreement.</em></td>
</tr>
<tr>
<td><strong>Authorized By (Client)</strong></td>
<td><em>Name: ___ / Title: ___ / Company: ___</em></td>
</tr>
<tr>
<td><strong>Client Signature</strong></td>
<td><em>Signature: ________________________________ Date:
_______________</em></td>
</tr>
<tr>
<td><strong>Accepted By (Fancy Lab)</strong></td>
<td><em>Name: ___ / Title: ___</em></td>
</tr>
<tr>
<td><strong>Fancy Lab Signature</strong></td>
<td><em>Signature: ________________________________ Date:
_______________</em></td>
</tr>
<tr>
<td><strong>Witness (if required)</strong></td>
<td><em>Name: ___ / Title: ___ / Signature:
________________________________</em></td>
</tr>
</tbody>
</table>

*IMPORTANT: This signed document serves as the formal authorization to
deploy the website to production. Once signed, the project advances to
P9 — Launch. Any scope additions after sign-off require a separate
Change Order.*

**APPENDIX B: STALLED-APPROVAL ESCALATION LADDER (NEW IN v2)**

*This appendix codifies the "Client Approval > 30 days" escalation path.
The clock starts on the **deliverable submission date** stamped in
ClickUp at Step 2 (initial staging access) or Step 7 (post-revision
walkthrough). Days are calendar days.*

**Evidence base.** Per `data/analysis/02_portfolio_health.md`, four red
clients are stuck in client approval: `breadiamonddirect.com` (8 Client
Approval tasks, oldest 862d), `ian.club` (7 tasks, oldest 457d),
`Select Dental` (14 Client Approval + 38 Backlog), and
`barclaysjewelers.com` (55 Open, 580d oldest). Per
`data/analysis/03_sop_gap_and_recommendations.md` section C, oldest
`Client Approval` items in the portfolio are 400+ days old. v1 had no
quantified trigger; v2 fixes that.

### B.1 Escalation Ladder

| Day | Trigger | Owner | Action |
|---:|:---|:---|:---|
| **0** | Deliverable submitted (Step 2 or Step 7) | Carlos | Stamp `deliverable_submitted_date` on the ClickUp task; status = `Client Approval`. |
| **7** | No client response | **Carlos** | Gentle reminder via email + ClickUp comment referencing the agreed review deadline. Add `client-block` tag if not already present. |
| **14** | Still no client response | **Carlos** | Second reminder + offer to schedule a Google Meet to walk through blockers. Cc the secondary contact mapped in P1 (gate item #5). |
| **21** | Still no client response | **Carlos → Rinaldo** | Carlos files a one-page **Stall Escalation Brief** (Google Doc) summarizing: deliverable, days outstanding, prior touchpoints, hypothesized blocker, and **cost of delay** (downstream phase impact, team capacity tied up). Posted in Slack DM to Rinaldo (Accountable per RACI). |
| **30** | Still no client response | **Rinaldo (decision) + Carlos (execution)** | Apply ClickUp status `Client Stall`. Rinaldo decides on an unblock plan (executive call, contract amendment, scope cut). |
| **30 + 7** | No executed unblock plan | Rinaldo + Carlos | Project moved to `PARKED` folder. Phase Gate item #13 fails; project does not advance to P9. |

### B.2 ClickUp Status Flow

```
Client Approval  →  Client Stall  →  Parked
       ↑                ↑               ↑
   Day 0–29       Day 30 (auto)    Day 37 (manual,
                                    Rinaldo approval)
```

### B.3 Tag Conventions

- **`client-block`** — applied to any `Client Approval` task that has triggered Day 7+ on the ladder. Used to roll up at-risk accounts in PM dashboards.
- The tag stays on the task until either sign-off is obtained (status → next phase) or the project is parked.

### B.4 v2 Rollout Action — Retroactive Application

The four red clients below are subject to immediate ladder application
on v2 publication. Carlos owns triage; Rinaldo owns the park/restart
decision per RACI.

| Client | Open Client Approval tasks | Oldest open (days) | Initial action |
|:---|---:|---:|:---|
| `breadiamonddirect.com` | 8 | 862 | Skip to Day 21 brief; Rinaldo decision needed within 7 days |
| `ian.club` | 7 | 457 | Skip to Day 21 brief; Rinaldo decision needed within 7 days |
| `Select Dental` | 14 (+38 Backlog) | 78 | Day 14 unblock call; if no response, Day 21 brief |
| `barclaysjewelers.com` | 55 Open | 580 | Skip to Day 30 `Client Stall` status; confirm "active vs. abandoned" with Rinaldo |

*All four cases default to `PARKED` if no executed unblock plan within
7 days of `Client Stall` status, per Phase Gate item #13.*
