**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P7**

**TESTING & QA**

Standard Operating Procedure & Phase Gate Document

v4.0 \| April 2026 \| Confidential

**REVISION HISTORY**

> v3 → v4 (April 2026)
>
> \- Upgraded design-token verification from a soft check to a **HARD
> PHASE GATE**: QA cannot sign off until a Design-Token Compliance
> Report is produced showing zero deviations from the Figma token set,
> or each deviation is explicitly signed off by Aida (per
> `data/analysis/03_sop_gap_and_recommendations.md` §C item 3 — high
> comment density on design-update tasks such as "Update the design of
> PDP" with 20 comments indicates partial enforcement under v3).
> Codified in PROCESS step 3, a new Deliverable, ESCALATION row, and
> new gate item #3a.
>
> \- Defined the **Design-Token Compliance Report format** (automated
> Figma-variable diff + Manuk-signed acknowledgment + per-deviation
> Aida sign-off block) and added it to the Appendix as Section 3a.
>
> \- Strengthened RACI to make explicit that **Manuk owns QA
> end-to-end** with single-name responsibility (per
> `data/analysis/03_sop_gap_and_recommendations.md` §A — Manuk holds
> 155 QA-side tasks; the `qa` tag aligns). Aida added as a named
> Approver for design-token deviation exceptions.
>
> \- Added a **Bug-Fix SLA**: any bug sitting in `Review` status >5
> business days auto-escalates to Asya (per `§ Data Enrichment` —
> 42 Review-status tasks on `hawaiilabgrown.com` and 7 on `ian.club`
> are stalled re-QA items). New ESCALATION row + sign-off prompt.
>
> \- Added a `qa`-tag enforcement note: every QA task must carry the
> `qa` tag at creation (data shows the tag only used on 29/155 QA
> tasks; QA work is identified by list position, which breaks
> cross-list reporting).
>
> \- Appended new section **Data Enrichment (ClickUp export,
> 2026-04-22)** with the evidence base from the rollup doc.

**PURPOSE & SCOPE**

This SOP defines the standard process for systematically testing the
completed website across all functional, visual, performance, and
accessibility dimensions. It incorporates targeted checklists addressing
the most common recurring issue categories identified across past
projects: Spacing & Layout, Navigation & Links, Buttons & CTAs,
Shopify-Specific issues, and Design Fidelity. It ensures that every
defect is identified, documented, and resolved before the site is
presented to the client for final approval.

**Phase Objective**

Deliver a thoroughly tested, bug-free website that meets all design
specifications, functional requirements, performance benchmarks, and
accessibility standards — ready for client review with confidence.
Pre-QA developer self-review, design token verification (hard gate as
of v4), and systematic link audits are used to reduce QA cycle time and
catch preventable issues before they reach QA.

**Scope Includes**

> \- Pre-QA developer self-review checklist (mandatory before QA
> handoff)
>
> \- Spacing & Layout verification against design tokens
>
> \- **Design-Token Compliance Report (hard gate, v4)** — automated
> diff vs. Figma variables, with per-deviation Aida sign-off
>
> \- Navigation & link audit — all links, menus, anchors, breadcrumbs
>
> \- Button & CTA testing — states, visibility, sizing, click handlers
>
> \- Shopify-specific testing — sections, metafields, schema, Liquid
> rendering
>
> \- Design Fidelity — Figma overlay comparison, pixel-level accuracy
>
> \- Section management verification — ordering, visibility, duplication
>
> \- Animation & interaction testing — sliders, hover effects, scroll
> behavior
>
> \- Typography & text style verification against UI Kit type scale
>
> \- Color & visual style verification against color scheme tokens
>
> \- Forms & inputs testing — validation, dropdowns, search, submission
> feedback
>
> \- Visual QA (design-to-development accuracy)
>
> \- Functional testing (all features, forms, interactions)
>
> \- Responsive testing (all breakpoints and devices)
>
> \- Cross-browser testing (Chrome, Firefox, Safari, Edge)
>
> \- E-commerce testing (cart, checkout, payments, orders)
>
> \- Third-party integration testing
>
> \- SEO validation (meta tags, schema, sitemap, redirects)
>
> \- Performance testing (speed, Core Web Vitals)
>
> \- Accessibility testing (WCAG 2.1 AA basics)
>
> \- Content proofing (typos, broken links, missing images)
>
> \- Product page verification (variants, pricing, metafield data,
> collection linking)
>
> \- Image quality check (sizing, cropping, format, resolution)
>
> \- Video & media functionality
>
> \- Footer & header testing (links, styling, announcement bar)
>
> \- Multi-language / i18n testing (if applicable)
>
> \- Bug documentation and tracking via Pastel + ClickUp
>
> \- Regression testing after fixes
>
> \- Bug-fix SLA enforcement (Review-status bugs >5 business days
> escalate to Asya)

**Scope Excludes**

> \- Security penetration testing (unless in scope)
>
> \- Load/stress testing (unless in scope)
>
> \- Content changes or copywriting (route to P3)
>
> \- Design changes (route to P4)
>
> \- New feature development (route to P6)

**WHO - RACI MATRIX**

|  |  |  |
|:---|:---|:---|
| **Role** | **Person(s)** | **Responsibility** |
| **Responsible (QA end-to-end)** | Manuk | *Owns QA execution single-handedly: test plan, all audit checklists, bug logging in Pastel + ClickUp, regression cycles, and the QA Sign-Off Report. Per data, Manuk holds 155 QA-side tasks across the portfolio.* |
| **Accountable** | Asya | *Ultimately answerable for completion; receives Bug-Fix SLA escalations and signs the phase gate.* |
| **Approved By (design-token deviations)** | Aida | *Sole approver of any design-token deviation that ships. Without Aida's per-deviation sign-off, the Design-Token Compliance Report cannot show "approved exceptions" and the phase gate is blocked.* |
| **Consulted** | Narine + Ishkhan | *Receive bug reports, perform fixes, re-submit for QA. Consulted on Pre-QA self-review failures and link-audit failures.* |
| **Informed** | Rinaldo + Harry | *Kept up to date on progress; receive escalations on stalled Review-status bugs and missed performance targets.* |

**WHAT - DELIVERABLES**

|  |  |  |
|:---|:---|:---|
| **Deliverable** | **Format / Location** | **Owner** |
| **Pre-QA Developer Self-Review Checklist (completed)** | ClickUp Subtask | Narine / Ishkhan |
| **QA Test Plan** | Google Docs / ClickUp | Manuk |
| **Link Map & Audit Report** | Google Sheets | Manuk |
| **Bug Report Log** | Pastel + ClickUp (every task tagged `qa`) | Manuk |
| **Design-Token Compliance Report (HARD GATE)** | Google Sheets (auto-diff export) + Manuk sign + per-deviation Aida sign block | Manuk (compile) / Aida (per-deviation approval) |
| **Visual QA Comparison Report (Figma overlay)** | Pastel / Google Docs | Manuk |
| **Cross-Browser Test Results** | Google Sheets | Manuk |
| **Performance Test Results** | Google Docs / Sheets | Manuk |
| **SEO Validation Checklist** | Google Sheets | Manuk |
| **Bug-Fix SLA Log** | ClickUp (Review-status age tracker) | Manuk |
| **QA Sign-Off Report** | Google Docs | Asya |

**WHERE - TOOLS & PLATFORMS**

|  |  |
|:---|:---|
| **Tool** | **Purpose in This Phase** |
| **Pastel** | Visual QA commenting, screenshot annotation, bug documentation on live pages |
| **ClickUp** | Bug tracking, QA task management, pre-QA checklist subtask, test case tracking, Bug-Fix SLA timer (Review-status age) |
| **Figma** | Design reference for visual QA comparison; **source of truth for the design-token set used in the Compliance Report diff** |
| **BrowserStack / LambdaTest** | Cross-browser and device testing |
| **PixelPerfect (browser extension)** | Figma overlay comparison for design fidelity checks |
| **Google PageSpeed Insights / Lighthouse** | Performance and accessibility testing |
| **Google Search Console** | SEO validation, indexing verification |
| **Screaming Frog / Sitebulb** | Technical SEO audit, broken link detection, full site link crawl |
| **WAVE / axe DevTools** | Accessibility testing |
| **Slack** | Bug communication, QA status updates, Bug-Fix SLA escalations |

**HOW - PROCESS STEPS**

> **1. Verify Pre-QA Developer Self-Review**
>
> BEFORE accepting the build for QA, confirm the developer has completed
> the mandatory Pre-QA Developer Self-Review Checklist (Appendix Section
> 1). This checklist covers: all links verified and clickable, spacing
> matches Figma design tokens, responsive tested on
> mobile/tablet/desktop, all buttons functional with correct states,
> text content matches source, Shopify metafields rendering, section
> schemas configured, collection filters working, variant swatches
> updating images, and breadcrumbs present. The checklist must be
> submitted as a completed ClickUp subtask before QA starts. The QA
> ClickUp task that opens the cycle must carry the `qa` tag at
> creation.
>
> **2. Create QA Test Plan**
>
> Create a structured test plan covering: all pages to be tested
> (prioritize Homepage, Custom Pages, Collection Pages, and Product
> Pages as these tend to have the highest concentration of issues), test
> categories, testing tools to be used, pass/fail criteria for each
> category, device and browser matrix, and assigned testers. Include the
> link map document mapping every menu item, CTA, and internal link to
> its destination URL. Share the plan with the development team.
>
> **3. Spacing & Layout Audit + Design-Token Compliance Report (HARD
> GATE)**
>
> Verify: consistent spacing between sections using design tokens (not
> arbitrary values), elements aligned to Figma grid (check margins and
> padding at pixel level), no content overflowing containers (especially
> on collection and product pages), section heights stable on hover and
> interaction, text staying on single lines where expected, and
> responsive spacing adjustments applied correctly across breakpoints.
> Use the design token system from P4 UI Kit as the single source of
> truth.
>
> **HARD GATE — Design-Token Compliance Report.** QA cannot sign off
> on this phase until Manuk produces a Design-Token Compliance Report
> (template in Appendix Section 3a) showing **zero deviations** from
> the Figma token set, OR each deviation listed is explicitly signed
> off by Aida (per P4 authoring RACI). The report format is:
>
> > a. **Automated diff vs. Figma variables.** Pull the canonical
> > token set from the project's Figma file (variables panel — colors,
> > spacing, radii, typography scale, shadows). Pull the implemented
> > token values from the Shopify theme/CSS. Produce a side-by-side
> > diff in a Google Sheets export with one row per token. Flag every
> > divergence (missing, renamed, or value-mismatched).
> >
> > b. **Manuk-signed acknowledgment.** Manuk signs the report
> > confirming the diff was generated against the current Figma file
> > version (record the Figma version timestamp).
> >
> > c. **Per-deviation Aida sign-off.** For every flagged divergence
> > the team intends to ship as-is, Aida signs the corresponding row
> > with rationale (design intent change, technical constraint, etc.).
> > Unsigned deviations BLOCK the phase gate — they must be either
> > fixed by Narine/Ishkhan or signed off by Aida; Manuk cannot
> > self-approve, Asya cannot override.
>
> **4. Navigation & Link Audit**
>
> Verify against the link map: all navigation links point to correct
> destinations, mega menu items link to correct collections/pages, all
> CTAs navigate to intended URLs, all anchor/scroll-to links function
> (IDs match between nav and target sections), breadcrumbs present on
> product and collection pages, navigation behavior consistent between
> desktop and mobile. Run Screaming Frog link crawl to catch broken
> links automatically.
>
> **5. Buttons & CTAs Audit**
>
> Verify: no buttons present that should be hidden for specific pages or
> conditions, all required product inquiry and contact buttons present,
> button sizes match design specs per color scheme, hover states do not
> cause layout shifts or jumping effects, slider/carousel arrow buttons
> function correctly, all CTA click handlers work and navigate
> correctly, and button states (default, hover, active, disabled) render
> per UI Kit.
>
> **6. Shopify-Specific Audit**
>
> Verify: all sections have proper schema settings for content
> management (colors, spacing, visibility toggles), metafield data
> displays correctly on product pages, sections are modular — content
> updates possible without code changes, collection filtering and
> sorting work as expected, color/variant swatches update product images
> correctly, conditional rendering using metafields and section settings
> (not hardcoded content), visibility toggles function so sections can
> be shown/hidden without code changes, and metafield definitions
> enforce correct data types.
>
> **7. Design Fidelity Check (Figma Match)**
>
> Use PixelPerfect or Figma overlay comparison for pixel-level accuracy.
> Verify: font sizes, weights, and families match Figma specifications
> exactly, colors match design (especially grays and brand colors per
> scheme), component layouts match Figma structure, all design elements
> in Figma are implemented (no missing elements), icon quality and
> format correct (SVG, correct resolution), and acceptance criteria
> within 2px tolerance of Figma spec. Compare the implementation against
> the UI Kit typography scale (desktop and mobile) and color scheme
> tokens. Any divergence found here that is also a token divergence
> must be reflected in the Design-Token Compliance Report (step 3).
>
> **8. Section & Component Management Check**
>
> Verify: no missing sections that should be present, no duplicate or
> orphaned sections, section ordering matches the approved design and
> sitemap, section visibility correct per page context, animation and
> interaction on sections works (sliders, carousels, hover effects,
> scroll behavior), and no jumping or layout shift on interaction.
>
> **9. Visual QA (Comprehensive)**
>
> Compare every page (desktop and mobile) against Figma designs. Covers:
> Typography & Text Style (font sizes, families, colors, weights match
> UI Kit), Color & Visual Style (background colors, borders, shadows
> match color scheme tokens), Image Issues (sizes, quality, cropping,
> icons), and Video & Media (videos play, embeds work). Document all
> discrepancies with Pastel screenshots and Figma references.
>
> **10. Functional Testing**
>
> Test all interactive elements: forms (submission, validation, error
> messages, dropdown behavior, search functionality, form submission
> feedback), product pages (variant display, pricing, product data,
> collection linking, product inquiry), navigation (desktop and mobile),
> accordions, tabs, modals, video players, anchor links, back-to-top
> buttons, and any custom functionality. Test both expected and
> edge-case inputs.
>
> **11. Responsive Testing**
>
> Test at standard breakpoints: desktop (1440px+, 1280px, 1024px),
> tablet (768px landscape and portrait), mobile (375px, 390px, 414px).
> Verify: layouts reflow correctly, no horizontal scroll, touch targets
> adequate size (min 44x44px), text readable, images scale properly,
> navigation works on all devices, touch interactions separate from
> desktop hover, and Shopify section settings correct per breakpoint
> where applicable. Test mobile-first then enhance for larger screens.
>
> **12. Cross-Browser Testing**
>
> Test on: Chrome (latest), Firefox (latest), Safari (latest), Edge
> (latest), iOS Safari (iPhone + iPad), Android Chrome. Document any
> browser-specific issues. Prioritize fixes based on analytics data or
> target audience. Note any intentional progressive enhancement
> decisions.
>
> **13. E-Commerce Testing**
>
> If applicable, test the full purchase flow: browse products,
> filter/sort, view product details, select variants (verify swatches
> update images correctly), add to cart, update cart, apply discount
> codes, proceed to checkout, enter shipping info, select shipping
> method, complete payment (test mode), receive order confirmation
> email. Test edge cases: empty cart, out-of-stock, maximum quantities,
> and data integrity for migrated products (pricing, descriptions,
> images, variants, metafields).
>
> **14. Third-Party Integration Testing**
>
> Verify all integrations: Google Analytics tracking on all pages, Meta
> Pixel firing on key events, email signup forms connecting to marketing
> platform, live chat widget loading properly, review widgets displaying
> correctly, CRM data flowing correctly, and any custom API integrations
> functioning.
>
> **15. SEO Validation**
>
> Verify: all pages have unique meta titles and descriptions, H1 tags
> present and correct on every page, schema markup validating (Google
> Rich Results Test), XML sitemap generated and accessible, robots.txt
> configured correctly, 301 redirects working (if migration), canonical
> URLs set, image alt text present, Open Graph tags rendering correctly.
>
> **16. Performance Testing**
>
> Run Google PageSpeed Insights and Lighthouse on key pages. Verify:
> mobile score 90+, desktop score 95+, Core Web Vitals passing (LCP \<
> 2.5s, INP \< 200ms, CLS \< 0.1), total page weight reasonable, no
> render-blocking resources, images optimized and lazy-loaded,
> third-party script impact measured. Document any items that cannot
> meet targets with justification.
>
> **17. Accessibility Testing**
>
> Run automated tests with WAVE or axe DevTools. Manually verify:
> keyboard navigation works throughout the site, focus indicators are
> visible, color contrast meets WCAG AA (4.5:1 for text, 3:1 for large
> text) across all color schemes, form labels are properly associated,
> images have meaningful alt text, and skip navigation link is present.
>
> **18. Footer, Header & Multi-Language Check**
>
> Verify: all footer links correct and functional, header styling
> correct, announcement bar displays properly. If multi-language: no
> layout breaks on language change, translations render correctly,
> RTL/CJK text handled properly.
>
> **19. Bug Fixing Cycle (with SLA)**
>
> Developers fix reported bugs prioritized as: Critical (site-breaking),
> High (major feature broken), Medium (visual or minor functional), Low
> (cosmetic or nice-to-have). After each fix cycle, QA performs
> regression testing on fixed items plus surrounding functionality.
> Repeat until all Critical and High bugs are resolved.
>
> **Bug-Fix SLA (v4).** Any bug sitting in `Review` status for more
> than 5 business days auto-escalates to Asya for triage (per `§ Data
> Enrichment` evidence: 42 Review-status tasks on `hawaiilabgrown.com`
> and 7 on `ian.club` were stalled re-QA items). Manuk maintains a
> Bug-Fix SLA Log in ClickUp showing age-in-status for every
> Review-status item; entries crossing the 5-day threshold get a
> Slack ping to Asya plus a `sla-breach` tag.
>
> **20. QA Sign-Off**
>
> Once all Critical and High bugs are resolved, Medium/Low issues are
> documented (with client disclosure plan), and the **Design-Token
> Compliance Report shows zero open deviations (or each deviation
> Aida-signed)**: compile the QA Sign-Off Report summarizing test
> results by issue category, remaining known issues, performance
> benchmarks, the Design-Token Compliance Report status, and the
> Bug-Fix SLA Log. Get PM sign-off. Notify the team that the site is
> ready for client review.

**COMMUNICATION - STAKEHOLDER UPDATES**

|  |  |  |  |
|:---|:---|:---|:---|
| **Type** | **Frequency** | **Audience** | **Channel** |
| Pre-QA Checklist Verification | Once (before QA starts) | QA Lead + Dev Team | ClickUp |
| QA Kickoff | Once | QA + Dev Team + PM | Slack / Google Meet |
| Daily Bug Report | Daily (during QA) | Dev Team + PM | Slack + ClickUp + Pastel |
| Design-Token Compliance Report | Once per QA round (before sign-off) | Aida + Asya + Dev Team | Google Sheets + Slack |
| Bug-Fix SLA Breach Alert | On 5-day Review-status threshold | Asya + Dev Team | Slack + ClickUp tag `sla-breach` |
| Fix Verification | After each fix cycle | QA + Dev Team | ClickUp + Slack |
| QA Status Update | Daily | PM | Slack |
| QA Sign-Off | Once (at phase close) | PM + Full Team | Google Docs + Slack |

**ESCALATION - BLOCKED PHASE PROTOCOL**

|  |  |  |  |
|:---|:---|:---|:---|
| **Trigger** | **Timeframe** | **Escalation Action** | **Escalated To** |
| Critical bug found | Immediately | Alert dev team and PM; prioritize fix above all other tasks | Asya + Narine/Ishkhan |
| Bug fix introduces new issues (regression) | Immediately | Revert fix; reassess approach with dev team | Asya |
| **Design-token deviation without Aida sign-off** | Before QA sign-off | **Phase gate BLOCKED. Either fix the deviation or obtain Aida's per-row sign-off in the Compliance Report. Asya cannot override.** | **Aida + Asya** |
| Design implementation significantly off (\>10 issues per page) | During visual QA | Schedule design-dev alignment meeting; verify design tokens are being used | Aida + Asya |
| Pre-QA developer checklist not completed | Before QA starts | Return build to developer; QA will not begin until checklist is submitted | Asya + Rinaldo |
| Excessive spacing & layout issues on a page | During QA | Halt QA on that page; developer must implement design token system before continuing | Asya + Narine/Ishkhan |
| Navigation link audit shows widespread broken or wrong links | During QA | Return to developer for systematic link fix before continuing other QA | Asya + Narine/Ishkhan |
| **Bug stuck in Review status \>5 business days (SLA breach)** | At day 5 | Auto-escalate to Asya; tag `sla-breach`; Slack ping; Asya triages owner & priority | Asya |
| Performance targets not met after optimization | After performance testing | Present tradeoffs to PM; get client input | Rinaldo + Asya |
| QA timeline exceeding allocated time | 3+ days over estimate | Assess remaining scope; prioritize critical items | Rinaldo |
| Third-party integration failing in QA | 2 business days | Contact vendor support; assess workaround | Asya + Narine |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **Feature-Complete Development Build** | P6 - Development | Cannot begin QA on incomplete features |
| **Pre-QA Developer Self-Review Checklist (completed)** | P6 - Development | QA will not start without completed self-review checklist |
| **Figma Designs + UI Kit + Token Set (for visual comparison and Compliance Report diff)** | P4 - Design | Need final designs, UI Kit (color tokens, typography scale, button states), and the Figma variables panel as the canonical token set for the Design-Token Compliance Report |
| **Aida availability for deviation sign-off** | P4 - Design | Without Aida available to sign per-deviation rows, the Design-Token Compliance Report cannot close and the phase gate is blocked |
| **SEO Requirements (for validation)** | P3 - Project Setup | Need meta data and SEO specs to validate against |
| **Product Catalog (for e-commerce testing)** | P5 - Inventory | Need products imported to test purchase flow |
| **Link Map Document** | P4/P6 - Design/Development | Need link map matching every menu item, CTA, and internal link to its destination URL |

**REVISION LIMITS & SCOPE CONTROL**

Bug Fixes: Unlimited during QA phase for issues caused by development;
design or content change requests route back to respective phases

QA Rounds: Up to 3 full QA rounds included; additional rounds require PM
approval and timeline adjustment

Performance Optimization: Best-effort optimization within allocated
time; advanced optimization scoped separately

Pre-QA Checklist Failure: Developer must pass self-review checklist
before each QA round; failures delay QA start

Design-Token Deviations: Each unfixed deviation must carry Aida's
sign-off per row of the Compliance Report; otherwise it is treated as
a defect, not an exception, and blocks sign-off.

Bug-Fix SLA: Bugs in `Review` >5 business days auto-escalate to Asya;
the bug remains in Review until re-tested — the SLA tracks dev
turnaround, not QA backlog.

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

**PHASE GATE - COMPLETION CHECKLIST**

*ALL items below must be completed before the project can advance to
P8 - Client Review & Pre-Launch. The site must be thoroughly tested and stable
before the client reviews it.*

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **1** | Pre-QA Developer Self-Review Checklist completed and submitted in ClickUp |  |  |
| **2** | QA Test Plan created and shared with team |  |  |
| **3** | Spacing & Layout audit completed |  |  |
| **3a** | **HARD GATE — Design-Token Compliance Report attached, zero open deviations (or each deviation sign-off'd by Aida per row)** |  |  |
| **4** | Navigation & Link audit completed (all links verified against link map) |  |  |
| **5** | Buttons & CTAs audit completed (states, visibility, sizing, functionality) |  |  |
| **6** | Shopify-specific audit completed (sections, metafields, schema, Liquid) |  |  |
| **7** | Design Fidelity check completed (Figma overlay comparison, within 2px tolerance) |  |  |
| **8** | Section management verified (ordering, visibility, no duplicates) |  |  |
| **9** | Visual QA completed (all pages, desktop + mobile — typography, colors, images, media) |  |  |
| **10** | Functional testing completed (all features, forms, interactions, product pages) |  |  |
| **11** | Responsive testing completed (all breakpoints) |  |  |
| **12** | Cross-browser testing completed (all target browsers) |  |  |
| **13** | E-commerce testing completed (full purchase flow - if applicable) |  |  |
| **14** | Third-party integration testing completed |  |  |
| **15** | SEO validation completed (meta, schema, sitemap, redirects) |  |  |
| **16** | Performance testing completed (PageSpeed targets met, Core Web Vitals passing) |  |  |
| **17** | Accessibility testing completed (WCAG AA basics, contrast across all color schemes) |  |  |
| **18** | Footer, header, and multi-language checks completed |  |  |
| **19** | All Critical and High priority bugs resolved |  |  |
| **20** | Regression testing completed after bug fixes |  |  |
| **20a** | **Bug-Fix SLA Log attached; zero items currently breaching the 5-business-day Review threshold (or all breaches Asya-acknowledged)** |  |  |
| **21** | QA Sign-Off Report completed and PM-approved |  |  |
| **22** | ClickUp QA tasks marked as complete (all carry the `qa` tag) |  |  |
| **23** | Slack notification posted confirming QA phase completion |  |  |

**Phase Gate Sign-Off**

|                        |                      |          |
|:-----------------------|:---------------------|:---------|
| **Field**              | **Details**          | **Date** |
| **Project Name**       |                      |          |
| **QA Lead (Manuk)**    |                      |          |
| **Design Approver (Aida — token deviations)** |   |          |
| **Approved By (Asya)** |                      |          |
| **Client Rep**         |                      |          |
| **Next Phase**         | P8 - Client Review & Pre-Launch |          |
| **Notes / Conditions** |                      |          |

## Data Enrichment (ClickUp export, 2026-04-22)

- **QA templating already exists in the data.** 31 tasks contain the
  checklist items `Create Pastel Dashboard`, `Client training and
  tutorial on how to use Pastel`, `Product Detail Checklist`,
  `Product Collection Checklist`, `Header & Navigation Checklist`,
  `Footer Checklist`, `Homepage Checklist`, `Additional Pages
  Checklist`, `Shopping Cart and Checkout checklist`, `Transactional
  E-mails checklist`. These exactly match this SOP. **P7 is the most
  faithfully executed SOP in the portfolio** — treat it as the
  reference model.
- **Manuk owns QA in practice.** 155 tasks total, 54 open — healthy
  ratio. The `qa` tag is used on only 29 tasks; narrower than
  expected, suggests QA work is mostly identified by *list position*
  (inside dev lists) rather than tagged. v4 enforces the `qa` tag at
  task creation (gate item #22) so cross-list reporting works.
- **Bug-fix cycle (step 19) is the typical stall point.** 42
  Review-status tasks on `hawaiilabgrown.com` and 7 Review-status
  tasks on `ian.club` are effectively "waiting on bug fix to re-QA."
  v4 codifies the SLA: bugs in Review > 5 business days auto-escalate
  to Asya (gate item #20a, ESCALATION row, sign-off prompt).
- **Design-token enforcement was partial under v3.** High comment
  density on design-update tasks such as `Update the design of PDP`
  (20 comments) is the evidence that "should be verified" did not
  hold up in practice. v4 promotes design-token compliance to a hard
  gate (#3a) with Aida as the sole exception-approver.

**APPENDIX A: QA TEST PLAN & BUG REPORT TEMPLATE**

*This comprehensive test plan incorporates lessons learned from past
FancyLab projects. It includes a mandatory Pre-QA Developer Self-Review
Checklist, issue-category-specific audit checklists targeting the most
common recurring problems, the v4 Design-Token Compliance Report
(Section 3a), and systematic testing across all dimensions.*

*Prerequisites: P6 Development must be complete — all pages built,
integrations configured, and the Pre-QA Developer Self-Review Checklist
submitted as a completed ClickUp subtask.*

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 65%" />
</colgroup>
<tbody>
<tr>
<td colspan="2"><strong>1. PRE-QA DEVELOPER SELF-REVIEW CHECKLIST
(MANDATORY — MUST PASS BEFORE QA STARTS)</strong></td>
</tr>
<tr>
<td><strong>Developer Name</strong></td>
<td><em>Name: ___ / Date completed: ___ / ClickUp subtask ID:
___</em></td>
</tr>
<tr>
<td><strong>Links Verified</strong></td>
<td><em>All navigation links tested and clickable: [ ] / No dead links:
[ ] / Anchor links work: [ ]</em></td>
</tr>
<tr>
<td><strong>Spacing Matches Figma</strong></td>
<td><em>Design tokens used (not arbitrary values): [ ] / Section spacing
consistent: [ ] / No content overflow: [ ]</em></td>
</tr>
<tr>
<td><strong>Responsive Self-Test</strong></td>
<td><em>Mobile (375px): [ ] / Tablet (768px): [ ] / Desktop (1440px): [
] / No horizontal scroll: [ ] / No layout breaks: [ ]</em></td>
</tr>
<tr>
<td><strong>All Buttons Functional</strong></td>
<td><em>CTAs click and navigate: [ ] / Hover states work: [ ] / No
layout shift on hover: [ ] / Correct visibility per page: [ ]</em></td>
</tr>
<tr>
<td><strong>Text Content Matches Source</strong></td>
<td><em>Copy matches approved content: [ ] / No placeholder text: [ ] /
No typos spotted: [ ]</em></td>
</tr>
<tr>
<td><strong>Metafields Rendering</strong></td>
<td><em>All product metafields display correctly: [ ] / No missing data:
[ ] / Types validated: [ ]</em></td>
</tr>
<tr>
<td><strong>Section Schema Configured</strong></td>
<td><em>All sections have schema settings: [ ] / Content editable
without code: [ ] / Visibility toggles work: [ ]</em></td>
</tr>
<tr>
<td><strong>Collection Filters Working</strong></td>
<td><em>Filtering works: [ ] / Sorting works: [ ] / URL updates: [ ] /
Clear filters: [ ]</em></td>
</tr>
<tr>
<td><strong>Variant Swatches</strong></td>
<td><em>Swatches update images: [ ] / Price updates: [ ] / Sold out
states: [ ] / Inventory correct: [ ]</em></td>
</tr>
<tr>
<td><strong>Breadcrumbs Present</strong></td>
<td><em>Product pages: [ ] / Collection pages: [ ] / Custom pages (if
applicable): [ ]</em></td>
</tr>
<tr>
<td><strong>Figma Overlay Check</strong></td>
<td><em>Screenshot compared to Figma: [ ] / Within 2px tolerance: [ ] /
Key pages checked: ___</em></td>
</tr>
<tr>
<td><strong>Self-Review Result</strong></td>
<td><em>PASS (all items checked) / FAIL (list items to fix):
___</em></td>
</tr>
<tr>
<td colspan="2"><strong>2. TEST ENVIRONMENT CONFIGURATION</strong></td>
</tr>
<tr>
<td><strong>Staging URL</strong></td>
<td><em>URL: ___ / Password: ___ / Theme ID: ___ / Matches latest dev
branch: [ ]</em></td>
</tr>
<tr>
<td><strong>Test Data Loaded</strong></td>
<td><em>Products: [ ] / Collections: [ ] / Blog posts: [ ] / Pages: [ ]
/ Customer accounts: [ ]</em></td>
</tr>
<tr>
<td><strong>Test Devices</strong></td>
<td><em>Desktop: ___ / Laptop: ___ / Tablet: ___ / Mobile (iOS): ___ /
Mobile (Android): ___</em></td>
</tr>
<tr>
<td><strong>Browsers to Test</strong></td>
<td><em>[ ] Chrome (latest) [ ] Safari (latest) [ ] Firefox (latest) [ ]
Edge (latest) [ ] Safari iOS [ ] Chrome Android</em></td>
</tr>
<tr>
<td><strong>Screen Resolutions</strong></td>
<td><em>[ ] 1920x1080 [ ] 1440x900 [ ] 1366x768 [ ] 768x1024 (tablet) [
] 375x812 (iPhone) [ ] 390x844 (iPhone Pro)</em></td>
</tr>
<tr>
<td><strong>Test Payment Credentials</strong></td>
<td><em>Shopify test mode: [ ] / Test card: 4242... / Bogus gateway: [ ]
/ PayPal sandbox: [ ]</em></td>
</tr>
<tr>
<td><strong>QA Lead Assigned</strong></td>
<td><em>Name: Manuk (default per RACI) / Start date: ___ / Estimated QA
duration: ___ days</em></td>
</tr>
<tr>
<td><strong>Link Map Document</strong></td>
<td><em>Link map URL: ___ / All menu items mapped: [ ] / All CTAs
mapped: [ ] / All internal links mapped: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>3. SPACING &amp; LAYOUT AUDIT</strong></td>
</tr>
<tr>
<td><strong>Design Token Compliance</strong></td>
<td><em>Spacing values from design token system (not arbitrary): [ ] /
Token system documented: [ ] / Compliance Report (Section 3a) generated:
[ ]</em></td>
</tr>
<tr>
<td><strong>Section Spacing Consistency</strong></td>
<td><em>Consistent gaps between all sections: [ ] / No unexpected
large/small gaps: [ ] / Desktop: [ ] / Mobile: [ ]</em></td>
</tr>
<tr>
<td><strong>Figma Grid Alignment</strong></td>
<td><em>Elements aligned to Figma grid: [ ] / Margins match spec: [ ] /
Padding match spec: [ ] / Pixel-level verified: [ ]</em></td>
</tr>
<tr>
<td><strong>Content Overflow Check</strong></td>
<td><em>No content overflowing containers: [ ] / Collection pages: [ ] /
Product pages: [ ] / Custom pages: [ ]</em></td>
</tr>
<tr>
<td><strong>Section Height Stability</strong></td>
<td><em>Heights stable on hover/interaction: [ ] / No jumping: [ ] / No
unexpected resizing: [ ]</em></td>
</tr>
<tr>
<td><strong>Text Line Behavior</strong></td>
<td><em>Text stays on one line where expected: [ ] / Line breaks at
correct points: [ ] / No orphaned words: [ ]</em></td>
</tr>
<tr>
<td><strong>Responsive Spacing</strong></td>
<td><em>Desktop spacing tokens applied: [ ] / Tablet adjustments: [ ] /
Mobile adjustments: [ ] / Not same values across all breakpoints: [
]</em></td>
</tr>
<tr>
<td><strong>Homepage Spacing</strong></td>
<td><em>All homepage sections verified: [ ] / Issue count: ___ / Notes:
___</em></td>
</tr>
<tr>
<td colspan="2"><strong>3a. DESIGN-TOKEN COMPLIANCE REPORT (HARD GATE —
v4)</strong></td>
</tr>
<tr>
<td><strong>Figma File Version</strong></td>
<td><em>Figma file URL: ___ / Variables panel snapshot timestamp: ___ /
Confirmed current with P4: [ ]</em></td>
</tr>
<tr>
<td><strong>Implemented Token Source</strong></td>
<td><em>Theme/CSS export source: ___ / Branch / commit: ___ /
Date: ___</em></td>
</tr>
<tr>
<td><strong>Diff Method</strong></td>
<td><em>Automated side-by-side diff (Google Sheets export): [ ] / One
row per token (color / spacing / radius / typography / shadow): [ ]
/ Diff file URL: ___</em></td>
</tr>
<tr>
<td><strong>Diff Summary</strong></td>
<td><em>Total tokens: ___ / Matching: ___ / Missing in code: ___ /
Renamed: ___ / Value-mismatched: ___</em></td>
</tr>
<tr>
<td><strong>Manuk Sign — Diff Acknowledgment</strong></td>
<td><em>Diff was generated against the current Figma file version
recorded above: [ ] / Manuk signature: ___ / Date: ___</em></td>
</tr>
<tr>
<td><strong>Per-Deviation Aida Sign-Off (one row per deviation
shipped)</strong></td>
<td><em>Deviation 1: token = ___ / Figma value = ___ / Code value = ___
/ Rationale = ___ / Aida signed: [ ] / Date: ___ /// Deviation 2: ___
/// Deviation 3: ___ /// Add rows as needed.</em></td>
</tr>
<tr>
<td><strong>Open (Unsigned) Deviations</strong></td>
<td><em>Count must be ZERO before phase gate item #3a can be checked:
___ / If non-zero, route back to Narine/Ishkhan for fix or Aida for
sign-off.</em></td>
</tr>
<tr>
<td><strong>Final Status</strong></td>
<td><em>PASS (zero open) / BLOCKED (open deviations remain): ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>4. NAVIGATION &amp; LINK AUDIT</strong></td>
</tr>
<tr>
<td><strong>All Links Verified vs Link Map</strong></td>
<td><em>Every link tested against link map document: [ ] / Total links:
___ / Broken: ___ / Wrong destination: ___</em></td>
</tr>
<tr>
<td><strong>Mega Menu Links</strong></td>
<td><em>All mega menu items correct: [ ] / Link to correct collections:
[ ] / Link to correct pages: [ ]</em></td>
</tr>
<tr>
<td><strong>CTA Destination Check</strong></td>
<td><em>All CTA buttons navigate to intended URL: [ ] / Homepage CTAs: [
] / Collection CTAs: [ ] / PDP CTAs: [ ]</em></td>
</tr>
<tr>
<td><strong>Anchor / Scroll-to Links</strong></td>
<td><em>All anchor links function: [ ] / IDs match between nav and
target: [ ] / Smooth scroll: [ ]</em></td>
</tr>
<tr>
<td><strong>Breadcrumbs</strong></td>
<td><em>Present on product pages: [ ] / Present on collection pages: [ ]
/ Correct hierarchy: [ ] / All links work: [ ]</em></td>
</tr>
<tr>
<td><strong>Desktop vs Mobile Navigation</strong></td>
<td><em>Desktop nav works: [ ] / Mobile nav works: [ ] / Behavior
consistent: [ ] / No broken links on either: [ ]</em></td>
</tr>
<tr>
<td><strong>Link Crawl Results</strong></td>
<td><em>Screaming Frog / Sitebulb crawl completed: [ ] / Total URLs: ___
/ 404s found: ___ / Redirect chains: ___</em></td>
</tr>
<tr>
<td><strong>External Links</strong></td>
<td><em>All external links open in new tab: [ ] / No broken external
links: [ ] / rel='noopener' present: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>5. BUTTONS &amp; CTAS AUDIT</strong></td>
</tr>
<tr>
<td><strong>Button Visibility</strong></td>
<td><em>No unwanted buttons showing: [ ] / All required buttons present:
[ ] / Conditional visibility correct: [ ]</em></td>
</tr>
<tr>
<td><strong>Button Sizing</strong></td>
<td><em>All buttons match Figma size specs: [ ] / Padding correct: [ ] /
Border-radius correct: [ ] / Per UI Kit: [ ]</em></td>
</tr>
<tr>
<td><strong>Hover States</strong></td>
<td><em>Hover states render correctly: [ ] / No layout shift on hover: [
] / No jumping effects: [ ] / Transition smooth: [ ]</em></td>
</tr>
<tr>
<td><strong>Click Handlers</strong></td>
<td><em>All buttons clickable: [ ] / Navigate to correct destination: [
] / Form submit buttons work: [ ] / No dead clicks: [ ]</em></td>
</tr>
<tr>
<td><strong>Slider/Carousel Arrows</strong></td>
<td><em>Previous/next arrows work: [ ] / Auto-play (if applicable): [ ]
/ Loop behavior correct: [ ] / Mobile swipe: [ ]</em></td>
</tr>
<tr>
<td><strong>Primary vs Secondary Buttons</strong></td>
<td><em>Correct button type per design: [ ] / Per color scheme: [ ] /
States per scheme (Default/Hover): [ ]</em></td>
</tr>
<tr>
<td><strong>Product Inquiry/Contact</strong></td>
<td><em>Inquiry buttons present where needed: [ ] / Contact CTAs work: [
] / Product-specific CTAs correct: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>6. SHOPIFY-SPECIFIC AUDIT</strong></td>
</tr>
<tr>
<td><strong>Section Schema Settings</strong></td>
<td><em>All sections have schema settings: [ ] / Colors configurable: [
] / Spacing configurable: [ ] / Content editable: [ ]</em></td>
</tr>
<tr>
<td><strong>Visibility Toggles</strong></td>
<td><em>Sections can be shown/hidden without code: [ ] / Blocks can be
toggled: [ ] / Works correctly: [ ]</em></td>
</tr>
<tr>
<td><strong>Metafield Display</strong></td>
<td><em>All metafields render on product pages: [ ] / Correct data
types: [ ] / No missing values: [ ] / Fallback text: [ ]</em></td>
</tr>
<tr>
<td><strong>Metafield Definitions</strong></td>
<td><em>Definitions created (not just values): [ ] / Types enforced: [ ]
/ Validation rules set: [ ]</em></td>
</tr>
<tr>
<td><strong>Section Modularity</strong></td>
<td><em>Content updates possible without code: [ ] / No hardcoded
content: [ ] / Conditional rendering via settings: [ ]</em></td>
</tr>
<tr>
<td><strong>Collection Filtering &amp; Sorting</strong></td>
<td><em>Filters work correctly: [ ] / Sort options function: [ ] / URL
updates on filter: [ ] / Counts accurate: [ ]</em></td>
</tr>
<tr>
<td><strong>Variant Swatch Behavior</strong></td>
<td><em>Color swatches update images: [ ] / Size swatches work: [ ] /
Sold out states correct: [ ] / Price updates: [ ]</em></td>
</tr>
<tr>
<td><strong>Liquid Rendering</strong></td>
<td><em>No Liquid errors in console: [ ] / Objects render correctly: [ ]
/ Loops work: [ ] / Conditionals correct: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>7. DESIGN FIDELITY — FIGMA MATCH</strong></td>
</tr>
<tr>
<td><strong>Figma Overlay Comparison</strong></td>
<td><em>PixelPerfect overlay used: [ ] / Key pages compared: Homepage: [
] / Collection: [ ] / PDP: [ ] / About: [ ] / Contact: [ ]</em></td>
</tr>
<tr>
<td><strong>Typography Match (Desktop)</strong></td>
<td><em>H1 matches UI Kit: [ ] / H2: [ ] / H3: [ ] / H4: [ ] / H5: [ ] /
Paragraph lg/md/sm: [ ] / Accent: [ ]</em></td>
</tr>
<tr>
<td><strong>Typography Match (Mobile)</strong></td>
<td><em>H1 matches mobile scale: [ ] / H2: [ ] / H3: [ ] / H4: [ ] / H5:
[ ] / Paragraph lg/md/sm: [ ] / Accent: [ ]</em></td>
</tr>
<tr>
<td><strong>Color Scheme Accuracy</strong></td>
<td><em>Scheme 1 tokens match: [ ] / Scheme 2: [ ] / Scheme 3: [ ] /
Scheme 4: [ ] / Grays accurate: [ ] / Brand colors: [ ]</em></td>
</tr>
<tr>
<td><strong>Component Layout Match</strong></td>
<td><em>Components structured per Figma: [ ] / No structural
differences: [ ] / No missing elements: [ ]</em></td>
</tr>
<tr>
<td><strong>Icon Quality</strong></td>
<td><em>SVG format used: [ ] / Correct resolution: [ ] / No degradation:
[ ] / Consistent sizing: [ ]</em></td>
</tr>
<tr>
<td><strong>Pixel Tolerance</strong></td>
<td><em>All elements within 2px of Figma spec: [ ] / Exceptions
documented: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>8. SECTION &amp; COMPONENT
MANAGEMENT</strong></td>
</tr>
<tr>
<td><strong>Missing Sections</strong></td>
<td><em>All designed sections present: [ ] / Cross-checked against Figma
page designs: [ ]</em></td>
</tr>
<tr>
<td><strong>Duplicate Sections</strong></td>
<td><em>No unintended duplicate sections: [ ] / No orphaned sections: [
]</em></td>
</tr>
<tr>
<td><strong>Section Ordering</strong></td>
<td><em>Section order matches approved design: [ ] / Per page: Homepage:
[ ] / Collection: [ ] / PDP: [ ] / Custom: [ ]</em></td>
</tr>
<tr>
<td><strong>Animation &amp; Interaction</strong></td>
<td><em>Sliders/carousels work: [ ] / Hover effects correct: [ ] / No
jumping: [ ] / Scroll behavior smooth: [ ] / Arrow nav: [ ]</em></td>
</tr>
<tr>
<td><strong>Section Visibility per Page</strong></td>
<td><em>Correct sections shown per page context: [ ] / Hidden sections
not rendering: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>9. VISUAL QA — TYPOGRAPHY, COLORS, IMAGES &amp;
MEDIA</strong></td>
</tr>
<tr>
<td><strong>Typography &amp; Text Style</strong></td>
<td><em>Font sizes correct: [ ] / Font families correct: [ ] / Text
colors match: [ ] / Bold/weights correct: [ ] / Line heights: [
]</em></td>
</tr>
<tr>
<td><strong>Color &amp; Visual Style</strong></td>
<td><em>Background colors correct: [ ] / Borders correct: [ ] / Shadows
correct: [ ] / Color scheme application per section: [ ]</em></td>
</tr>
<tr>
<td><strong>Image Quality</strong></td>
<td><em>All images loading: [ ] / Correct sizes: [ ] / No
stretching/cropping: [ ] / Quality acceptable: [ ] / Icons correct size:
[ ]</em></td>
</tr>
<tr>
<td><strong>Video &amp; Media</strong></td>
<td><em>Videos play: [ ] / Embeds load: [ ] / Media players functional:
[ ] / Mobile playback: [ ] / Autoplay settings: [ ]</em></td>
</tr>
<tr>
<td><strong>Desktop Visual Match</strong></td>
<td><em>Compare each page against Figma: [ ] Header [ ] Footer [ ]
Homepage [ ] Collection [ ] PDP [ ] Cart [ ] About [ ] Contact [ ] Blog
[ ] Custom pages</em></td>
</tr>
<tr>
<td><strong>Mobile Visual Match</strong></td>
<td><em>Compare each page at 375px: [ ] Header [ ] Footer [ ] Homepage [
] Collection [ ] PDP [ ] Cart [ ] About [ ] Contact [ ] Blog</em></td>
</tr>
<tr>
<td colspan="2"><strong>10. FUNCTIONAL TESTING</strong></td>
</tr>
<tr>
<td><strong>Forms &amp; Inputs</strong></td>
<td><em>Dropdowns work: [ ] / Form validation: [ ] / Error messages: [ ]
/ Search function: [ ] / Submission feedback: [ ]</em></td>
</tr>
<tr>
<td><strong>Product Page Issues</strong></td>
<td><em>Variant display: [ ] / Pricing correct: [ ] / Product data
matches: [ ] / Collection linking: [ ] / Inquiry features: [ ]</em></td>
</tr>
<tr>
<td><strong>Search Functionality</strong></td>
<td><em>Search finds products: [ ] / Collections: [ ] / Pages: [ ] /
Predictive search: [ ] / No results state: [ ]</em></td>
</tr>
<tr>
<td><strong>Product Filtering</strong></td>
<td><em>All filters work: [ ] / Clear filters: [ ] / Filter count
updates: [ ] / URL updates: [ ] / Mobile filters: [ ]</em></td>
</tr>
<tr>
<td><strong>Product Sorting</strong></td>
<td><em>All sort options work: [ ] / Default sort correct: [ ] /
Persists on pagination: [ ]</em></td>
</tr>
<tr>
<td><strong>Add to Cart</strong></td>
<td><em>Adds correctly: [ ] / Quantity works: [ ] / Cart counter
updates: [ ] / Drawer opens: [ ] / Multiple variants: [ ]</em></td>
</tr>
<tr>
<td><strong>Cart Functionality</strong></td>
<td><em>Update quantity: [ ] / Remove items: [ ] / Cart total correct: [
] / Discount code: [ ] / Shipping estimate: [ ]</em></td>
</tr>
<tr>
<td><strong>Checkout Flow</strong></td>
<td><em>Full flow tested: [ ] / Address validation: [ ] / Shipping
options: [ ] / Payment: [ ] / Confirmation: [ ] / Email receipt: [
]</em></td>
</tr>
<tr>
<td><strong>Account Functions</strong></td>
<td><em>Register: [ ] / Login: [ ] / Forgot password: [ ] / Order
history: [ ] / Address management: [ ] / Logout: [ ]</em></td>
</tr>
<tr>
<td><strong>Footer &amp; Header</strong></td>
<td><em>Footer links correct: [ ] / Header styling: [ ] / Announcement
bar: [ ] / Mobile header: [ ]</em></td>
</tr>
<tr>
<td><strong>Multi-Language / i18n</strong></td>
<td><em>No layout breaks on language switch: [ ] / Translations render:
[ ] / RTL text: [ ] / N/A: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>11. RESPONSIVE &amp; CROSS-BROWSER
TESTING</strong></td>
</tr>
<tr>
<td><strong>Desktop (1440px+)</strong></td>
<td><em>Layout correct: [ ] / No overflow: [ ] / Typography matches
desktop scale: [ ] / Spacing tokens: [ ]</em></td>
</tr>
<tr>
<td><strong>Small Desktop (1024px)</strong></td>
<td><em>Layout reflows: [ ] / No horizontal scroll: [ ] / Navigation
works: [ ]</em></td>
</tr>
<tr>
<td><strong>Tablet (768px)</strong></td>
<td><em>Layout reflows: [ ] / Touch targets 44px+: [ ] / No overlap: [ ]
/ Portrait: [ ] / Landscape: [ ]</em></td>
</tr>
<tr>
<td><strong>Mobile (375px/390px)</strong></td>
<td><em>Layout correct: [ ] / Typography matches mobile scale: [ ] /
Touch-friendly: [ ] / No horizontal scroll: [ ]</em></td>
</tr>
<tr>
<td><strong>Touch vs Hover</strong></td>
<td><em>Touch interactions work on mobile: [ ] / No hover-dependent
features on touch: [ ] / Separate touch handlers: [ ]</em></td>
</tr>
<tr>
<td><strong>Cross-Browser Results</strong></td>
<td><em>Chrome: [ ] / Safari: [ ] / Firefox: [ ] / Edge: [ ] / iOS
Safari: [ ] / Android Chrome: [ ] / Issues: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>12. THIRD-PARTY INTEGRATION
TESTING</strong></td>
</tr>
<tr>
<td><strong>Email Marketing</strong></td>
<td><em>Forms submit to platform: [ ] / Welcome flow triggers: [ ] /
Browse abandonment: [ ] / Cart abandonment: [ ]</em></td>
</tr>
<tr>
<td><strong>Reviews</strong></td>
<td><em>Widget displays: [ ] / Submission works: [ ] / Star ratings: [ ]
/ Photo reviews: [ ] / Moderation: [ ]</em></td>
</tr>
<tr>
<td><strong>Analytics</strong></td>
<td><em>GA4 pageviews: [ ] / E-commerce events: [ ] / Add to cart: [ ] /
Purchase: [ ] / GTM tags firing: [ ]</em></td>
</tr>
<tr>
<td><strong>Chat / Support</strong></td>
<td><em>Widget loads: [ ] / Opens correctly: [ ] / Sends messages: [ ] /
Mobile view: [ ] / Hours display: [ ]</em></td>
</tr>
<tr>
<td><strong>Social Feeds</strong></td>
<td><em>Instagram feed: [ ] / Facebook pixel: [ ] / Pinterest tag: [ ] /
TikTok pixel: [ ]</em></td>
</tr>
<tr>
<td><strong>Shipping App</strong></td>
<td><em>Rates calculate: [ ] / Labels generate: [ ] / Tracking updates:
[ ]</em></td>
</tr>
<tr>
<td><strong>Custom Integrations</strong></td>
<td><em>List each: ___ / Tested: [ ] / Data flow verified: [ ] / Error
handling: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>13. PERFORMANCE BENCHMARKING</strong></td>
</tr>
<tr>
<td><strong>PageSpeed Insights (Desktop)</strong></td>
<td><em>Homepage: ___ / Collection: ___ / PDP: ___ / All pages &gt; 90:
[ ]</em></td>
</tr>
<tr>
<td><strong>PageSpeed Insights (Mobile)</strong></td>
<td><em>Homepage: ___ / Collection: ___ / PDP: ___ / All pages &gt; 70:
[ ]</em></td>
</tr>
<tr>
<td><strong>Largest Contentful Paint (LCP)</strong></td>
<td><em>Desktop: ___s / Mobile: ___s / Target: &lt; 2.5s / Pass: [
]</em></td>
</tr>
<tr>
<td><strong>Cumulative Layout Shift (CLS)</strong></td>
<td><em>Desktop: ___ / Mobile: ___ / Target: &lt; 0.1 / Pass: [
]</em></td>
</tr>
<tr>
<td><strong>Interaction to Next Paint (INP)</strong></td>
<td><em>Desktop: ___ms / Mobile: ___ms / Target: &lt; 200ms / Pass: [
]</em></td>
</tr>
<tr>
<td><strong>Time to First Byte (TTFB)</strong></td>
<td><em>Average: ___ms / Target: &lt; 800ms / Pass: [ ]</em></td>
</tr>
<tr>
<td><strong>Total Page Weight</strong></td>
<td><em>Homepage: ___KB / PDP: ___KB / Collection: ___KB / Targets from
P6 met: [ ]</em></td>
</tr>
<tr>
<td><strong>Third-Party Script Impact</strong></td>
<td><em>Total third-party time: ___ms / Blocking scripts: ___ / Can
optimize: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>14. SEO VALIDATION CHECKLIST</strong></td>
</tr>
<tr>
<td><strong>Title Tags</strong></td>
<td><em>All pages have unique titles: [ ] / Within 60 chars: [ ] /
Keywords present: [ ]</em></td>
</tr>
<tr>
<td><strong>Meta Descriptions</strong></td>
<td><em>All pages have descriptions: [ ] / Within 155 chars: [ ] /
Unique: [ ]</em></td>
</tr>
<tr>
<td><strong>H1 Tags</strong></td>
<td><em>One per page: [ ] / Keywords present: [ ] / No duplicates across
pages: [ ]</em></td>
</tr>
<tr>
<td><strong>Image Alt Text</strong></td>
<td><em>All images have alt text: [ ] / Descriptive: [ ] / No keyword
stuffing: [ ]</em></td>
</tr>
<tr>
<td><strong>Schema Markup</strong></td>
<td><em>Valid: [ ] / Tested in Rich Results Test: [ ] / No errors: [
]</em></td>
</tr>
<tr>
<td><strong>301 Redirects (Migration)</strong></td>
<td><em>All redirects working: [ ] / No redirect chains: [ ] / No 404s
from old URLs: [ ]</em></td>
</tr>
<tr>
<td><strong>Sitemap</strong></td>
<td><em>Valid: [ ] / Submitted to GSC: [ ] / All pages included: [ ] /
No blocked pages: [ ]</em></td>
</tr>
<tr>
<td><strong>Robots.txt</strong></td>
<td><em>Correct: [ ] / Not blocking important pages: [ ] / Sitemap
referenced: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>15. DATA INTEGRITY &amp; PRODUCT CONTENT
VERIFICATION</strong></td>
</tr>
<tr>
<td><strong>Migrated Product Data</strong></td>
<td><em>Pricing correct: [ ] / Descriptions accurate: [ ] / Images
present: [ ] / Variants match: [ ] / Metafields imported: [ ]</em></td>
</tr>
<tr>
<td><strong>Automated Data Checks</strong></td>
<td><em>Missing prices check: [ ] / Duplicate colors check: [ ] / Broken
image URLs: [ ] / Empty descriptions: [ ]</em></td>
</tr>
<tr>
<td><strong>Collection Categorization</strong></td>
<td><em>Products in correct collections: [ ] / Automated rules working:
[ ] / Manual assignments verified: [ ]</em></td>
</tr>
<tr>
<td><strong>PM Content Review</strong></td>
<td><em>PM verified product data accuracy: [ ] / Sign-off date: ___ /
Issues found: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>16. BUG REPORT TEMPLATE (COPY FOR EACH
BUG)</strong></td>
</tr>
<tr>
<td><strong>Bug ID</strong></td>
<td><em>Format: QA-[number] (e.g., QA-001)</em></td>
</tr>
<tr>
<td><strong>ClickUp Tag</strong></td>
<td><em>Must include `qa` tag at creation: [ ] / Additional tags (e.g.,
`sla-breach` once SLA crossed): ___</em></td>
</tr>
<tr>
<td><strong>Issue Category</strong></td>
<td><em>Spacing / Navigation / Buttons / Shopify / Design Fidelity /
Section / Animation / Typography / Color / Forms / Product / Image /
Video / Responsive / Data / Footer-Header / i18n / Other</em></td>
</tr>
<tr>
<td><strong>Page / Feature</strong></td>
<td><em>Where was the bug found? ___ / Page type: Homepage / Collection
/ PDP / Custom / Blog / Other</em></td>
</tr>
<tr>
<td><strong>Device / Browser</strong></td>
<td><em>e.g., iPhone 14 Pro / Safari 17</em></td>
</tr>
<tr>
<td><strong>Severity</strong></td>
<td><em>Critical (blocks launch) / Major (significant issue) / Minor
(cosmetic) / Enhancement (nice-to-have)</em></td>
</tr>
<tr>
<td><strong>Steps to Reproduce</strong></td>
<td><em>1. ___ 2. ___ 3. ___</em></td>
</tr>
<tr>
<td><strong>Expected Behavior</strong></td>
<td><em>What should happen (reference Figma/UI Kit if applicable):
___</em></td>
</tr>
<tr>
<td><strong>Actual Behavior</strong></td>
<td><em>What actually happens: ___</em></td>
</tr>
<tr>
<td><strong>Figma Reference</strong></td>
<td><em>Figma frame/component link (if design fidelity issue):
___</em></td>
</tr>
<tr>
<td><strong>Screenshot / Video</strong></td>
<td><em>Pastel link: ___ / Loom URL: ___ / Attached: [ ]</em></td>
</tr>
<tr>
<td><strong>Assigned To</strong></td>
<td><em>Developer: ___ / Priority: ___ / Due: ___</em></td>
</tr>
<tr>
<td><strong>Resolution Status (with Review-age tracker)</strong></td>
<td><em>Open / In Progress / Fixed / In Review (entered Review on: ___
/ days in Review: ___ / SLA = 5 business days) / Verified / Won't Fix
— Notes: ___</em></td>
</tr>
</tbody>
</table>

Pre-QA Developer Self-Review Verified By:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

QA Testing Completed By (Manuk):
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Design-Token Compliance Report Acknowledged By (Manuk):
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Per-Deviation Sign-Off (Aida — required for any shipped deviation):
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Bug-Fix SLA Log Reviewed By (Manuk; escalations acknowledged by Asya):
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

QA Lead Sign-Off:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

PM Approval for Client Review:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

*Once all critical and major bugs are resolved, performance targets are
met, the Design-Token Compliance Report shows zero open deviations (or
all deviations Aida-signed), the Bug-Fix SLA Log shows zero unaddressed
breaches, and the QA sign-off is complete, this phase gate can be
evaluated for advancement to P8 — Client Review & Pre-Launch.*
