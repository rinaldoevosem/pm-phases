**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P6**

**DEVELOPMENT**

Standard Operating Procedure & Phase Gate Document

v2.0 \| April 2026 \| Confidential

**REVISION HISTORY**

- v1.0 → v2.0 (April 2026): Folded ClickUp export findings (2026-04-22) into the SOP.
- Added new Appendix B — **Iframe / Third-Party Integration Micro-SOP** (Nivoda, MyDiamonds, BOSS Logics, custom ring builders, Diamond Search). Per `data/analysis/03_sop_gap_and_recommendations.md` §B (RING BUILDER list 56 tasks, DIAMOND SEARCH 6, `iframe` tag 22) and §D item 3.
- Reinforced RACI: explicitly named **Ishkhan as dev WIP owner** and **Narine as integration / cross-origin lead**, per gap doc §A and §B (Ishkhan 196 tasks / 122 open; Narine heavy on comments).
- Added Phase Gate item #13: **all iframe / third-party integrations validated in staging with vendor-signed acceptance**, per gap doc §B and `Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md` lines 428–435.
- Added new Process Step "0. Duplicate-Ticket Sweep" — sprint planning must check ClickUp for existing open duplicates by SKU / endpoint / vendor before creating a new dev task. Evidence: BOSS Logics integration ticket re-created with 8 comments each, twice (`Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md` line 432).
- Added an explicit **WIP cap: max 20 concurrent open tasks per developer** to Escalation table (Ishkhan currently runs ~6× over).
- Added comment-volume escalation rule: any task exceeding **10 comments** routes to Asya for scope review (per spawn brief).
- Appended `## Data Enrichment (ClickUp export, 2026-04-22)` section after the phase gate sign-off block, ported verbatim from the merged rollup doc.

**PURPOSE & SCOPE**

This SOP defines the standard process for building the website based on
approved designs, content, and product data. It covers front-end and
back-end development, platform configuration, third-party integrations,
and the structured development workflow that ensures quality code
delivery.

**Phase Objective**

Deliver a fully functional website on the target platform that
accurately implements all approved designs, incorporates all content and
product data, integrates all required third-party services, and is ready
for QA testing.

**Scope Includes**

> \- Front-end development (HTML, CSS, JavaScript, Liquid/PHP)
>
> \- Theme customization or custom theme build
>
> \- Responsive implementation (desktop, tablet, mobile)
>
> \- E-commerce functionality (cart, checkout, payments)
>
> \- Third-party integrations (analytics, marketing, CRM, etc.)
>
> \- Iframe / cross-origin embeds (Ring Builder, Diamond Search, vendor catalogs) — see Appendix B
>
> \- Content population from approved content package
>
> \- Navigation and internal linking implementation
>
> \- SEO technical implementation (schema, sitemap, redirects)
>
> \- Performance optimization (image compression, lazy loading,
> minification)
>
> \- Shipping and tax configuration (if applicable)

**Scope Excludes**

> \- Design changes (route back to P4 for Change Order)
>
> \- Content changes (route back to P3 for Change Order)
>
> \- New product data entry (route back to P5)
>
> \- Custom app or plugin development (unless in scope)
>
> \- Server infrastructure or hosting setup (unless in scope)

**WHO - RACI MATRIX**

|  |  |  |
|:---|:---|:---|
| **Role** | **Person(s)** | **Responsibility** |
| **Responsible** | Narine + Ishkhan | *Performs the work for this phase. Ishkhan owns dev WIP / build throughput (196 total tasks, 122 open per 2026-04-22 export). Narine owns third-party / iframe integration ownership and is the primary author of integration-thread comments.* |
| **Accountable** | Asya | *Ultimately answerable for completion; receives all comment-volume and WIP escalations.* |
| **Consulted** | Rinaldo + Aida | *Provides input and approves deliverables (PM scope decisions; design fidelity).* |
| **Informed** | Harry + Carlos | *Kept up to date on progress.* |

**WHAT - DELIVERABLES**

|  |  |  |
|:---|:---|:---|
| **Deliverable** | **Format / Location** | **Owner** |
| **Functional Development Site** | Staging URL / Dev Store | Narine + Ishkhan |
| **Development Checklist (completed)** | ClickUp / Google Sheets | Asya |
| **Third-Party Integration Documentation** | Google Docs | Narine |
| **Iframe / Cross-Origin Integration Spec (per integration)** | Google Docs (template per Appendix B) | Narine |
| **SEO Technical Implementation Report** | Google Docs / Sheets | Narine |
| **Performance Optimization Report** | Google Docs | Ishkhan |
| **Development Handoff to QA** | ClickUp + Slack | Asya |

**WHERE - TOOLS & PLATFORMS**

|  |  |
|:---|:---|
| **Tool** | **Purpose in This Phase** |
| **Shopify / WordPress / Custom Platform** | Primary development environment |
| **Figma** | Design reference via Dev Mode |
| **VS Code / IDE** | Code editing and development |
| **GitHub / Version Control** | Code repository and version management |
| **ClickUp** | Sprint planning, task tracking, bug logging, duplicate-ticket sweep |
| **Slack** | Daily standups, blocker communication, team coordination |
| **Google PageSpeed Insights** | Performance testing during development |
| **BrowserStack / Device Lab** | Cross-browser and device testing |

**HOW - PROCESS STEPS**

> **0. Duplicate-Ticket Sweep (pre-sprint)**
>
> Before creating any new dev ticket, search ClickUp by SKU, endpoint
> name, vendor name, and integration name for existing open duplicates.
> If a matching open task exists, append to it rather than re-creating.
> Evidence base: the BOSS Logics / Frederick Goldman integration was
> ticketed twice with 8 comments each — both stuck. Add a sprint-planning
> checklist item: "duplicate scan completed".
>
> **1. Development Sprint Planning**
>
> Break down the full build into development sprints (typically 1-2
> weeks each). Prioritize: global elements first (header, footer,
> navigation), then homepage, then interior pages, then specialized
> features. Create ClickUp tasks for each page/feature with clear
> acceptance criteria referencing Figma designs. Confirm WIP per
> developer is at or under the 20-task cap (see Escalation).
>
> **2. Build Global Elements**
>
> Develop shared components used across all pages: header (desktop +
> mobile navigation), footer, announcement bar, newsletter signup,
> cookie consent, and any global modals or popups. Ensure responsive
> behavior matches Figma designs exactly.
>
> **3. Build Page Templates**
>
> Develop each page template according to Figma designs. Populate with
> approved content from P3. Ensure: pixel-accurate implementation,
> responsive behavior at all breakpoints, all interactive elements
> functioning, proper heading hierarchy for SEO, and accessible markup
> (ARIA labels, alt text).
>
> **4. Implement E-Commerce Features**
>
> If applicable, configure: product page functionality (variants,
> quantity, add to cart), collection/category pages with filtering and
> sorting, cart page/drawer with upsells, checkout customization,
> payment gateway integration, shipping rate configuration, tax
> settings, and order notification emails.
>
> **5. Integrate Third-Party Services**
>
> Set up all required integrations: Google Analytics 4, Google Tag
> Manager, Meta Pixel (Facebook), email marketing platform (Klaviyo,
> Mailchimp, etc.), CRM connection, live chat or support widget, review
> platform, and any custom API integrations. Document each integration
> with account details and configuration notes. **Iframe / cross-origin
> embeds (Ring Builder, Diamond Search, Nivoda, MyDiamonds, BOSS Logics,
> custom ring builders) follow the dedicated micro-SOP in Appendix B.**
>
> **6. Implement SEO Technical Requirements**
>
> Configure: XML sitemap generation, robots.txt, canonical URLs,
> structured data/schema markup (Organization, Product, BreadcrumbList,
> FAQ), meta tags from P3 content, Open Graph and Twitter Card tags, 301
> redirects (if migration), hreflang tags (if multi-language), and
> proper URL structure.
>
> **7. Performance Optimization**
>
> Optimize site performance: compress and lazy-load images, minify CSS
> and JavaScript, implement critical CSS, optimize font loading, review
> and minimize third-party script impact, test with Google PageSpeed
> Insights (target 90+ mobile, 95+ desktop), and implement caching
> strategies.
>
> **8. Cross-Browser and Device Testing (Dev QA)**
>
> Before formal QA handoff, developers conduct initial testing: Chrome,
> Firefox, Safari, Edge (latest versions), iOS Safari, Android Chrome,
> tablet breakpoints, screen readers (basic accessibility check).
> Document any known issues or intentional design decisions.
>
> **9. Development Handoff to QA**
>
> Prepare for QA handoff: ensure all ClickUp dev tasks are marked
> complete, document staging site URL and any test credentials, list all
> third-party integrations with testing instructions, note any known
> issues or edge cases, update ClickUp with QA-ready status. Notify QA
> team via Slack.

**COMMUNICATION - STAKEHOLDER UPDATES**

|  |  |  |  |
|:---|:---|:---|:---|
| **Type** | **Frequency** | **Audience** | **Channel** |
| Sprint Planning | Start of each sprint | Dev Team + PM | ClickUp + Google Meet |
| Daily Standup | Daily | Dev Team | Slack |
| Sprint Review | End of each sprint | Dev Team + PM + Design Lead | Google Meet |
| Blocker Alerts | As needed (immediately) | PM | Slack |
| Client Progress Update | Bi-weekly or per sprint | Client | Email |
| QA Handoff Notification | Once (at phase close) | QA Team + PM | Slack + ClickUp |

**ESCALATION - BLOCKED PHASE PROTOCOL**

|  |  |  |  |
|:---|:---|:---|:---|
| **Trigger** | **Timeframe** | **Escalation Action** | **Escalated To** |
| Design implementation issue (cannot build as designed) | Immediately | Flag to design lead for design adjustment or alternative approach | Aida + Asya |
| Third-party integration failure | 2 business days | Escalate to PM; contact vendor support | Asya + Rinaldo |
| **Iframe / cross-origin integration fails to load or render** | Immediately | Engage Narine; verify CSP, vendor sandbox, fallback path per Appendix B | Narine + Asya |
| Development behind schedule (\>2 days slippage) | End of sprint | Sprint retrospective; re-prioritize or add resources | Asya + Rinaldo |
| Client requests changes during development | Immediately | Route to PM for Change Order evaluation | Rinaldo |
| Performance targets not achievable | During optimization | Present tradeoffs to PM; get client input if needed | Asya + Rinaldo |
| Critical bug blocking other development | Immediately | All hands on fix; notify PM of timeline impact | Asya |
| **Per-developer WIP exceeds 20 concurrent open tasks** | Sprint planning | Stop creating new tickets for that developer; PM redistributes load | Asya |
| **Any task exceeds 10 comments without resolution** | Immediately upon hitting threshold | Hand to Asya for scope review; consider Change Order or split into sub-tasks | Asya |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **Fully Approved Designs (Desktop + Mobile)** | P4 - Branding & Design | Cannot build without final approved designs |
| **Approved Content Package** | P3 - Content Strategy & Copywriting | Cannot populate pages without final copy |
| **Imported Product Catalog** | P5 - Inventory Management | Cannot build product pages without product data |
| **Dev Store / Staging Environment** | P2 - Project Kickoff | Need platform access to begin development |
| **Third-Party Account Credentials** | P1 - Client Onboarding / Client | Cannot integrate services without API keys and account access |
| **Vendor Integration Spec (API docs, sandbox creds, rate limits, CSP)** | P1 / Vendor | Cannot begin iframe / third-party integrations without complete intake (see Appendix B) |

**REVISION LIMITS & SCOPE CONTROL**

Development Implementation: Bugs and design accuracy fixes are unlimited
during dev phase; feature changes require Change Order

Third-Party Integrations: Standard integrations included; custom API
work beyond initial scope requires Change Order

Iframe / Cross-Origin Integrations: One round of vendor-side spec
clarification included per integration. Additional vendor escalations,
SDK upgrades, or scope expansion require Change Order.

Performance Optimization: Best-effort optimization included; advanced
optimization (custom CDN, edge computing) scoped separately

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

**PHASE GATE - COMPLETION CHECKLIST**

*ALL items below must be completed before the project can advance to
P7 - Testing & QA. The site must be feature-complete and functional
before entering the formal testing phase.*

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **1** | All page templates built and matching Figma designs |  |  |
| **2** | Responsive layouts verified (desktop, tablet, mobile) |  |  |
| **3** | All content populated from approved content package |  |  |
| **4** | E-commerce functionality working (if applicable) |  |  |
| **5** | All third-party integrations configured and functional |  |  |
| **6** | SEO technical implementation complete (schema, sitemap, redirects) |  |  |
| **7** | Performance optimization completed (PageSpeed targets met) |  |  |
| **8** | Developer cross-browser testing completed |  |  |
| **9** | All ClickUp development tasks marked as complete |  |  |
| **10** | Third-party integration documentation created |  |  |
| **11** | Staging URL shared with QA team |  |  |
| **12** | Slack notification posted confirming development phase completion |  |  |
| **13** | All iframe / third-party integrations validated in staging with vendor-signed acceptance (per Appendix B) |  |  |

**Phase Gate Sign-Off**

|                        |                   |          |
|:-----------------------|:------------------|:---------|
| **Field**              | **Details**       | **Date** |
| **Project Name**       |                   |          |
| **Approved By**        |                   |          |
| **Client Rep**         |                   |          |
| **Next Phase**         | P7 - Testing & QA |          |
| **Notes / Conditions** |                   |          |

## Data Enrichment (ClickUp export, 2026-04-22)

- **`development` is by far the top tag** (187 tasks). Dev volume is highest on `hawaiilabgrown.com` (54 In-Progress tasks — more than any other list) and `Steindiamonds.com` (22 In-Progress).
- **Ishkhan is the dev-side bottleneck.** 196 total tasks, **122 open** (tied for 2nd-highest open WIP in the entire org). Juan FancyLab (220 total, 184 open) and Luis Grosso (198/154) also sit primarily in dev territory. Recommend a WIP limit per developer (e.g., max 20 concurrent open tasks) — Ishkhan is 6× that now.
- **Third-party integration is the top comment-heavy theme.** `Integrate Frederick Goldman Inventory via BOSS Logics API - Artcarved & Triton` (breadiamonddirect.com) has appeared twice with 8 comments each — duplicate task evidence that the team is re-creating tickets when stuck. Add a "check for existing open duplicate by SKU/endpoint name" step to sprint planning.
- **iframe-tag cluster.** 22 tasks tagged `iframe` — specific enough to warrant an **iframe-integration micro-SOP** (Diamond Search, Ring Builder, Nivoda, MyDiamonds use iframes heavily).

**APPENDIX A: DEVELOPMENT SPECIFICATION & BUILD TRACKER**

*This specification documents all technical requirements, page-by-page
build status, integration configurations, and performance targets. It
serves as the development team's single reference for building the site
and tracking progress against design handoff specifications.*

*Prerequisites: P4 Design Handoff (approved designs, asset export,
interaction specs) and P5 Inventory (complete product catalog) must be
finalized.*

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 65%" />
</colgroup>
<tbody>
<tr>
<td colspan="2"><strong>1. TECHNICAL ARCHITECTURE &amp;
ENVIRONMENT</strong></td>
</tr>
<tr>
<td><strong>Shopify Theme</strong></td>
<td><em>Base theme: ___ / Version: ___ / OS 2.0 compliant: [ ] / JSON
templates: [ ]</em></td>
</tr>
<tr>
<td><strong>Theme Customization Approach</strong></td>
<td><em>[ ] Section-based [ ] Custom sections + blocks [ ] Hybrid
(sections + custom Liquid) [ ] Headless (Hydrogen)</em></td>
</tr>
<tr>
<td><strong>CSS Framework / Approach</strong></td>
<td><em>Vanilla CSS / Tailwind / SCSS / CSS Modules — Approach:
___</em></td>
</tr>
<tr>
<td><strong>JavaScript Approach</strong></td>
<td><em>Vanilla JS / Alpine.js / Web Components / React (sections) —
Bundle strategy: ___</em></td>
</tr>
<tr>
<td><strong>Build Tools</strong></td>
<td><em>[ ] Theme CLI [ ] Webpack [ ] Vite [ ] Rollup [ ] None — Config:
___</em></td>
</tr>
<tr>
<td><strong>Staging Environment</strong></td>
<td><em>URL: ___ / Theme ID: ___ / Password: ___ / Synced with dev
branch: [ ]</em></td>
</tr>
<tr>
<td><strong>Version Control</strong></td>
<td><em>Repo: ___ / Branch strategy: ___ / PR review required: [ ] /
CI/CD: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>2. PAGE-BY-PAGE BUILD TRACKER</strong></td>
</tr>
<tr>
<td><strong>Header / Navigation</strong></td>
<td><em>Status: Not Started / In Progress / Complete / QA — Dev: ___ /
Notes: ___</em></td>
</tr>
<tr>
<td><strong>Footer</strong></td>
<td><em>Status: ___ / Dev: ___ / Newsletter form: [ ] / Social links: [
] / Nav: [ ]</em></td>
</tr>
<tr>
<td><strong>Homepage</strong></td>
<td><em>Status: ___ / Dev: ___ / Sections: ___ of ___ complete / Mobile
responsive: [ ]</em></td>
</tr>
<tr>
<td><strong>Collection Page Template</strong></td>
<td><em>Status: ___ / Dev: ___ / Filters: [ ] / Sort: [ ] / Pagination:
[ ] / Quick view: [ ]</em></td>
</tr>
<tr>
<td><strong>Product Detail Page</strong></td>
<td><em>Status: ___ / Dev: ___ / Gallery: [ ] / Variants: [ ] / Add to
cart: [ ] / Reviews: [ ] / Related: [ ]</em></td>
</tr>
<tr>
<td><strong>Cart (Page/Drawer)</strong></td>
<td><em>Status: ___ / Dev: ___ / Quantity update: [ ] / Remove: [ ] /
Upsell: [ ] / Notes: [ ]</em></td>
</tr>
<tr>
<td><strong>About Page</strong></td>
<td><em>Status: ___ / Dev: ___ / Sections: ___ of ___ complete</em></td>
</tr>
<tr>
<td><strong>Contact Page</strong></td>
<td><em>Status: ___ / Dev: ___ / Form: [ ] / Map: [ ] / Validation: [
]</em></td>
</tr>
<tr>
<td><strong>Blog / Article Templates</strong></td>
<td><em>Status: ___ / Dev: ___ / List view: [ ] / Article: [ ] / Social
share: [ ] / Related: [ ]</em></td>
</tr>
<tr>
<td><strong>Search Results Page</strong></td>
<td><em>Status: ___ / Dev: ___ / Predictive search: [ ] / No results
state: [ ]</em></td>
</tr>
<tr>
<td><strong>404 Page</strong></td>
<td><em>Status: ___ / Dev: ___ / Branded: [ ] / Search bar: [ ] /
Popular links: [ ]</em></td>
</tr>
<tr>
<td><strong>Custom Pages</strong></td>
<td><em>List each: Page: ___ / Status: ___ / Dev: ___ / Notes:
___</em></td>
</tr>
<tr>
<td colspan="2"><strong>3. E-COMMERCE FEATURE
IMPLEMENTATION</strong></td>
</tr>
<tr>
<td><strong>Variant Selector</strong></td>
<td><em>Type: Dropdown / Swatch / Button / Image — Color swatches: [ ] /
Size guide link: [ ]</em></td>
</tr>
<tr>
<td><strong>Dynamic Checkout Buttons</strong></td>
<td><em>Shopify Pay: [ ] / Apple Pay: [ ] / Google Pay: [ ] / PayPal
Express: [ ]</em></td>
</tr>
<tr>
<td><strong>Product Recommendations</strong></td>
<td><em>Method: Shopify native / App / Custom algorithm — Sections: PDP
[ ] Cart [ ] Homepage [ ]</em></td>
</tr>
<tr>
<td><strong>Wishlist / Favorites</strong></td>
<td><em>App: ___ / Persistent (requires account)? [ ] / Guest wishlist?
[ ]</em></td>
</tr>
<tr>
<td><strong>Product Filtering</strong></td>
<td><em>App: ___ / Filter types: ___ / Mobile filter UI: Drawer / Modal
/ Inline</em></td>
</tr>
<tr>
<td><strong>Discount / Promo Configuration</strong></td>
<td><em>Auto-discounts: [ ] / Discount codes: [ ] / Free shipping
threshold: $__ / BOGO: [ ]</em></td>
</tr>
<tr>
<td><strong>Gift Cards</strong></td>
<td><em>Enabled: [ ] / Custom amounts: [ ] / Custom design: [
]</em></td>
</tr>
<tr>
<td><strong>Customer Accounts</strong></td>
<td><em>Classic / New (B2C) / B2B / Optional / Required — Account
features: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>4. THIRD-PARTY INTEGRATION TRACKER</strong></td>
</tr>
<tr>
<td><strong>Email Marketing (Klaviyo/etc.)</strong></td>
<td><em>App: ___ / Installed: [ ] / API connected: [ ] / Forms
integrated: [ ] / Flows configured: [ ] / Tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Reviews (Judge.me/etc.)</strong></td>
<td><em>App: ___ / Installed: [ ] / Widget styled: [ ] / Import existing
reviews: [ ] / Star ratings: [ ] / Tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Shipping (ShipStation/etc.)</strong></td>
<td><em>App: ___ / Installed: [ ] / Rates configured: [ ] / Label
printing: [ ] / Tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Analytics (GA4 + GTM)</strong></td>
<td><em>GA4 installed: [ ] / GTM container: [ ] / E-commerce tracking: [
] / Events: ___ / Tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Live Chat / Support</strong></td>
<td><em>App: ___ / Installed: [ ] / Widget styled: [ ] / Hours
configured: [ ] / Tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Loyalty / Rewards</strong></td>
<td><em>App: ___ / Installed: [ ] / Points configured: [ ] / Widget
styled: [ ] / Tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Social Commerce</strong></td>
<td><em>Instagram Shop: [ ] / Facebook Shop: [ ] / TikTok: [ ] /
Pinterest: [ ] / Pixel/tags installed: [ ]</em></td>
</tr>
<tr>
<td><strong>Custom Integrations</strong></td>
<td><em>List each: Integration: ___ / Method: API / Webhook / App /
Status: ___ / Tested: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>5. SEO TECHNICAL IMPLEMENTATION</strong></td>
</tr>
<tr>
<td><strong>Meta Tags (from P3 plan)</strong></td>
<td><em>Title tags: [ ] / Meta descriptions: [ ] / OG tags: [ ] /
Twitter cards: [ ] — All pages: [ ]</em></td>
</tr>
<tr>
<td><strong>Schema Markup</strong></td>
<td><em>[ ] Organization [ ] Product [ ] BreadcrumbList [ ] FAQ [ ]
Article [ ] LocalBusiness — Validated: [ ]</em></td>
</tr>
<tr>
<td><strong>Canonical URLs</strong></td>
<td><em>Self-referencing: [ ] / Collection pagination: [ ] / Variant
handling: [ ]</em></td>
</tr>
<tr>
<td><strong>XML Sitemap</strong></td>
<td><em>Auto-generated: [ ] / Custom entries: ___ / Submitted to GSC: [
]</em></td>
</tr>
<tr>
<td><strong>Robots.txt</strong></td>
<td><em>Configured: [ ] / Blocked paths: ___ / Allow all public pages: [
]</em></td>
</tr>
<tr>
<td><strong>301 Redirects (Migrations)</strong></td>
<td><em>Total redirects: ___ / Method: Shopify URL redirects / App /
Custom — Imported: [ ] / Verified: [ ]</em></td>
</tr>
<tr>
<td><strong>Page Speed Targets</strong></td>
<td><em>Desktop LCP: &lt; ___s / Mobile LCP: &lt; ___s / CLS: &lt; 0.1 /
FID: &lt; 100ms / TBT: &lt; ___ms</em></td>
</tr>
<tr>
<td><strong>Image Optimization</strong></td>
<td><em>WebP: [ ] / Lazy loading: [ ] / Responsive srcset: [ ] /
Compression: ___ / CDN: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>6. PERFORMANCE BUDGET &amp;
OPTIMIZATION</strong></td>
</tr>
<tr>
<td><strong>Total Page Weight Target</strong></td>
<td><em>Homepage: &lt; ___KB / PDP: &lt; ___KB / Collection: &lt;
___KB</em></td>
</tr>
<tr>
<td><strong>JavaScript Budget</strong></td>
<td><em>Total JS: &lt; ___KB / Third-party: &lt; ___KB / First-party:
&lt; ___KB / Defer non-critical: [ ]</em></td>
</tr>
<tr>
<td><strong>CSS Budget</strong></td>
<td><em>Total CSS: &lt; ___KB / Critical CSS inlined: [ ] / Unused CSS
removed: [ ]</em></td>
</tr>
<tr>
<td><strong>Font Loading Strategy</strong></td>
<td><em>Display: swap / Preload critical fonts: [ ] / Subset: [ ] / Max
font files: ___</em></td>
</tr>
<tr>
<td><strong>Third-Party Script Impact</strong></td>
<td><em>Audit each script: App: ___ / Impact: ___ms / Async/Defer: [ ] /
Necessary: [ ]</em></td>
</tr>
<tr>
<td><strong>Core Web Vitals Baseline</strong></td>
<td><em>Measured: [ ] / LCP: ___ / CLS: ___ / INP: ___ / Tool: PageSpeed
Insights / WebPageTest</em></td>
</tr>
<tr>
<td colspan="2"><strong>7. ACCESSIBILITY COMPLIANCE</strong></td>
</tr>
<tr>
<td><strong>Target Standard</strong></td>
<td><em>WCAG 2.1 AA / WCAG 2.1 AAA / Section 508 / ADA — Selected:
___</em></td>
</tr>
<tr>
<td><strong>Color Contrast Verified</strong></td>
<td><em>All text passes contrast ratio check? [ ] / Tool: ___ / Ratio: ≥
4.5:1 (body) ≥ 3:1 (large)</em></td>
</tr>
<tr>
<td><strong>Keyboard Navigation</strong></td>
<td><em>All interactive elements reachable by keyboard: [ ] / Focus
indicators visible: [ ] / Skip to content: [ ]</em></td>
</tr>
<tr>
<td><strong>Screen Reader Testing</strong></td>
<td><em>ARIA labels added: [ ] / Tested with: VoiceOver / NVDA / JAWS —
Tester: ___</em></td>
</tr>
<tr>
<td><strong>Alt Text Complete</strong></td>
<td><em>All images have descriptive alt text: [ ] / Decorative images
marked aria-hidden: [ ]</em></td>
</tr>
<tr>
<td><strong>Form Accessibility</strong></td>
<td><em>Labels associated: [ ] / Error messages: [ ] / Required fields
indicated: [ ] / Autocomplete: [ ]</em></td>
</tr>
</tbody>
</table>

Development Completed By:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Tech Lead Review:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

PM Sign-Off for QA Handoff:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

*Once all pages are built, integrations are configured, and the
developer self-check is complete, this phase gate can be evaluated for
advancement to P7 — Testing & QA.*

**APPENDIX B: IFRAME / THIRD-PARTY INTEGRATION MICRO-SOP**

*Scope: any embedded third-party experience that runs in an iframe or
loads cross-origin content into the storefront. This appendix is
mandatory for all such integrations and supersedes the generic
Step 5 process for these specific cases.*

*Evidence base (per `data/analysis/03_sop_gap_and_recommendations.md` §B
and the 2026-04-22 ClickUp export): RING BUILDER list = 56 tasks,
DIAMOND SEARCH list = 6 tasks, `iframe` tag = 22 tasks. These
integrations are the single largest source of multi-comment "sticky"
tickets on the dev team. The duplicate BOSS Logics / Frederick Goldman
tickets (8 comments each, twice) are a direct consequence of skipping
this intake.*

**B.1 — Named Integration Partners (in current rotation)**

| Vendor | Integration Type | Typical Footprint | Primary Owner |
|:---|:---|:---|:---|
| **Nivoda** | Diamond catalog feed + search iframe | PDP + Diamond Search page | Narine |
| **MyDiamonds** | Diamond search iframe | Dedicated search page | Narine |
| **BOSS Logics** | Inventory API (Frederick Goldman / Artcarved / Triton) | Collection + PDP | Narine + Ishkhan |
| **Custom Ring Builders** (per-client; e.g., breadiamonddirect, hawaiilabgrown) | Multi-step iframe configurator | Dedicated builder page | Ishkhan |
| **Other vendor catalogs** | API or iframe | Varies | Narine |

**B.2 — Standardized Vendor Intake (REQUIRED before any code is
written)**

The vendor must supply, in writing, all of the following. If any item is
missing, the integration is blocked at intake — escalate to Asya / Rinaldo
to chase the vendor. Do NOT begin development against a partial spec.

|  |  |
|:---|:---|
| **Intake Item** | **What's Required** |
| **API Documentation** | Public or NDA-protected URL; version pinned |
| **Sandbox / Test Credentials** | Working test environment, not production |
| **Production Credentials** | Delivered separately, after sandbox sign-off |
| **Rate Limits** | Per-second / per-day caps; throttling behavior |
| **CSP / Embedding Requirements** | Allowed parent origins, `frame-ancestors`, `X-Frame-Options` posture |
| **Required HTTP Headers** | `Content-Security-Policy`, `Permissions-Policy`, `Referrer-Policy` |
| **Webhook / Callback Spec** | If applicable: URLs we must expose, signing keys |
| **Vendor Support Channel** | Email or Slack contact + SLA in business hours |
| **Branding / Theming Hooks** | Whether iframe contents are themable; CSS variables exposed |
| **Mobile / Responsive Behavior** | Documented breakpoints; expected min/max iframe dimensions |
| **Failure / Timeout Behavior** | What the iframe does if the vendor backend is down |

**B.3 — Sandbox-First Rule**

Every integration MUST be proven end-to-end in a Shopify dev store
before being touched in production. Sandbox proof = a recorded Loom or
written acceptance note from Narine confirming the integration loads,
renders, completes a full happy-path interaction, and degrades
gracefully on simulated failure. Skipping the sandbox round is the
documented root cause of multiple re-ticketed integrations.

**B.4 — Cross-Origin / Iframe Embedding Checklist**

Before marking an iframe integration done, verify each item:

|  |  |  |
|:---|:---|:---|
| **\#** | **Check** | **Status** |
| 1 | Vendor's allowed `frame-ancestors` includes our staging + production domains | [ ] |
| 2 | Our storefront's `Content-Security-Policy` permits the vendor origin in `frame-src` and (if needed) `connect-src` / `script-src` | [ ] |
| 3 | `X-Frame-Options` is not set in a way that conflicts with the vendor's embedding | [ ] |
| 4 | Iframe is responsive at all standard breakpoints (320, 375, 768, 1024, 1440, 1920) | [ ] |
| 5 | Iframe height adjusts dynamically (postMessage handler if vendor supports it) | [ ] |
| 6 | Loading state is shown while iframe initializes | [ ] |
| 7 | Fallback UI is shown if iframe fails to load within a defined timeout (default 8s) | [ ] |
| 8 | Fallback includes a documented support path for the customer (email / phone / chat) | [ ] |
| 9 | Iframe is keyboard-accessible and focus is managed correctly on entry/exit | [ ] |
| 10 | Iframe's contents don't break the parent page's scroll position on mobile | [ ] |
| 11 | All cookies / localStorage usage by the vendor is documented and cookie-banner-compliant | [ ] |
| 12 | GA4 / GTM events fire for key iframe interactions where the vendor exposes them | [ ] |
| 13 | Vendor sandbox sign-off recorded in Google Drive | [ ] |
| 14 | Vendor production sign-off (post-deploy smoke test) recorded | [ ] |

**B.5 — Ownership & Tagging**

- Every iframe / third-party integration task in ClickUp MUST be tagged
  `iframe`. Untagged integration tasks are bounced back at sprint
  planning.
- **Narine** is the integration / cross-origin owner; **Ishkhan** is the
  build owner for ring builders and any custom front-end glue. Both are
  jointly accountable to Asya.
- The vendor name MUST appear in the ClickUp task title (e.g.,
  `[Nivoda] PDP diamond search iframe — sandbox round 1`) so duplicate
  searches succeed.

**B.6 — Escalation**

|  |  |  |
|:---|:---|:---|
| **Trigger** | **Action** | **Owner** |
| Iframe fails to load in sandbox after 1 day | Re-engage vendor support; document the failure mode | Narine |
| Any iframe / integration task exceeds **10 comments** without resolution | Escalate to Asya for scope review; consider splitting the task or issuing a Change Order | Asya |
| Duplicate iframe ticket detected (same vendor + same surface area) | Merge into the older ticket; archive the duplicate; note the merge in the comment thread | Asya |
| Vendor unresponsive for 3 business days | Escalate to PM (Rinaldo) for vendor-side leverage | Rinaldo |
| CSP / browser policy change breaks an iframe in production | Treat as P0 incident; revert or hotfix within 4 hours | Ishkhan + Asya |

**B.7 — Phase-Gate Coupling**

Phase Gate item **#13** ("All iframe / third-party integrations
validated in staging with vendor-signed acceptance") cannot be ticked
unless Appendix B sections B.2 (intake), B.3 (sandbox), and B.4
(checklist) are complete for every integration in scope. Sign-offs live
in the project's Google Drive folder under `Integrations/<vendor>/`.
