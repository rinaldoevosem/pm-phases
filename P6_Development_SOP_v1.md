**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P6**

**DEVELOPMENT**

Standard Operating Procedure & Phase Gate Document

v1.0 \| February 2026 \| Confidential

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
| **Responsible** | Narine + Ishkhan | *Performs the work for this phase* |
| **Accountable** | Asya | *Ultimately answerable for completion* |
| **Consulted** | Rinaldo + Aida | *Provides input and approves deliverables* |
| **Informed** | Harry + Carlos | *Kept up to date on progress* |

**WHAT - DELIVERABLES**

|  |  |  |
|:---|:---|:---|
| **Deliverable** | **Format / Location** | **Owner** |
| **Functional Development Site** | Staging URL / Dev Store | Narine + Ishkhan |
| **Development Checklist (completed)** | ClickUp / Google Sheets | Asya |
| **Third-Party Integration Documentation** | Google Docs | Narine |
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
| **ClickUp** | Sprint planning, task tracking, bug logging |
| **Slack** | Daily standups, blocker communication, team coordination |
| **Google PageSpeed Insights** | Performance testing during development |
| **BrowserStack / Device Lab** | Cross-browser and device testing |

**HOW - PROCESS STEPS**

> **1. Development Sprint Planning**
>
> Break down the full build into development sprints (typically 1-2
> weeks each). Prioritize: global elements first (header, footer,
> navigation), then homepage, then interior pages, then specialized
> features. Create ClickUp tasks for each page/feature with clear
> acceptance criteria referencing Figma designs.
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
> with account details and configuration notes.
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
| Development behind schedule (\>2 days slippage) | End of sprint | Sprint retrospective; re-prioritize or add resources | Asya + Rinaldo |
| Client requests changes during development | Immediately | Route to PM for Change Order evaluation | Rinaldo |
| Performance targets not achievable | During optimization | Present tradeoffs to PM; get client input if needed | Asya + Rinaldo |
| Critical bug blocking other development | Immediately | All hands on fix; notify PM of timeline impact | Asya |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **Fully Approved Designs (Desktop + Mobile)** | P4 - Branding & Design | Cannot build without final approved designs |
| **Approved Content Package** | P3 - Content Strategy & Copywriting | Cannot populate pages without final copy |
| **Imported Product Catalog** | P5 - Inventory Management | Cannot build product pages without product data |
| **Dev Store / Staging Environment** | P2 - Project Kickoff | Need platform access to begin development |
| **Third-Party Account Credentials** | P1 - Client Onboarding / Client | Cannot integrate services without API keys and account access |

**REVISION LIMITS & SCOPE CONTROL**

Development Implementation: Bugs and design accuracy fixes are unlimited
during dev phase; feature changes require Change Order

Third-Party Integrations: Standard integrations included; custom API
work beyond initial scope requires Change Order

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

**Phase Gate Sign-Off**

|                        |                   |          |
|:-----------------------|:------------------|:---------|
| **Field**              | **Details**       | **Date** |
| **Project Name**       |                   |          |
| **Approved By**        |                   |          |
| **Client Rep**         |                   |          |
| **Next Phase**         | P7 - Testing & QA |          |
| **Notes / Conditions** |                   |          |

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
