# P4 — Design

**FANCY LAB** · Web Development Department
Standard Operating Procedure & Phase Gate Document

| Version | Date | Status |
|---|---|---|
| v4.0 | April 2026 | Confidential |

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
- [Appendix A: Design Brief & Visual Direction Worksheet](#appendix-a-design-brief--visual-direction-worksheet)

## Revision History

<details>
<summary>v4.0 (April 2026) — GitHub-render pass</summary>

- Restructured headings: `**BOLD CAPS**` paragraphs → `##` / `###`, so GitHub's outline sidebar populates.
- Replaced empty-header pandoc tables (`|  |  |  |` + bolded content row) with proper pipe tables.
- Converted nested-blockquote process steps (`> **1. Step**`) to ordered lists.
- Unescaped pandoc backslash noise (`\|`, `\-`, `\#`, `\<`, `\>`, `\_`).
- Added TOC, metadata table; wrapped long appendices in `<details>`.
- Converted the raw HTML `<table>` in Appendix A to GFM pipe tables grouped under `###` sub-section headings.
- No content changes — every fact, number, named person, client, and cell preserved verbatim from v3.0.

</details>

<details>
<summary>v3.0 (April 2026) — ClickUp enrichment</summary>

- **v3.0 (April 2026):** Minimal-change version bump to align with the portfolio-wide v2 enrichment pass. Added a **Data Enrichment** section porting ClickUp export figures (per `Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md` lines 312–318 and `data/analysis/03_sop_gap_and_recommendations.md`). No process steps, RACI, deliverables, or phase-gate items were changed. The gap analysis raised no P4-specific corrections; the design-token enforcement concern in gap doc §C is being hardened in **P7_v4** (QA enforcement) rather than here (authoring).

- **v2.0 (February 2026):** Introduced the multi-scheme color system (Base + Primary BTN + Secondary BTN tokens), expanded the UI Kit to cover separate Desktop/Mobile typography scales, button states per scheme, and the Page Width / Container Width layout system. Added Section Component documentation and Figma Dev Mode handoff steps.

</details>

## Purpose & Scope

This SOP defines the standard process for researching, planning, and delivering the complete visual design of the website. It covers the Research Wall (discovery and strategic direction), Sitemap creation, UI Kit development (logos, typography, colors, buttons, layout system), wireframing, full UI/UX design, responsive layouts, and the iterative client approval process to ensure the final design is fully approved before development begins.

### Phase Objective

Deliver a complete, client-approved Figma design package — including Research Wall, Sitemap, UI Kit (with multi-scheme color system, typography scale, button states, and page layout specifications), wireframes, and pixel-perfect page designs (desktop and mobile) — that the development team can implement without design ambiguity or missing assets.

### Scope Includes

- Research Wall creation (discovery, brand direction, user problems, website goals, messaging strategy)
- Sitemap creation (page hierarchy, navigation structure, utility pages)
- UI Kit development (logos, fonts, colors, buttons, page layout system)
- Multi-scheme color system definition (Base tokens, Primary/Secondary button tokens per scheme)
- Typography scale (desktop and mobile) with font specifications
- Button component design (Primary and Secondary with Default and Hover states)
- Page layout specifications (Page Width, Container Width for desktop and mobile)
- Wireframe creation for all pages
- Full UI/UX design (desktop and mobile)
- Section-level component design with color scheme application
- Interactive prototype creation (if applicable)
- Client design review and approval process
- Design handoff to development team with UI Kit and asset export

### Scope Excludes

- Logo design or full brand identity (unless in project scope)
- Content writing or copy changes (handled in P3)
- Front-end development or coding (covered in P6)
- Photography, videography, or illustration production
- Print design or non-web collateral

## WHO — RACI Matrix

| Role | Person(s) | Responsibility |
|---|---|---|
| Responsible | Aida | *Performs the work for this phase* |
| Accountable | Aida | *Ultimately answerable for completion* |
| Consulted | Rinaldo + Asya + Carlos | *Provides input and approves deliverables* |
| Informed | Harry | *Kept up to date on progress* |

## WHAT — Deliverables

| Deliverable | Format / Location | Owner |
|---|---|---|
| Research Wall | Figma / FigJam | Aida |
| Sitemap (visual page hierarchy) | Figma / FigJam | Aida |
| UI Kit (Logos, Fonts, Colors, Buttons, Layout) | Figma | Aida |
| Wireframes (all pages) | Figma | Aida |
| Desktop Design (all pages) | Figma | Aida |
| Mobile Design (all pages) | Figma | Aida |
| Section Components with Color Scheme Application | Figma | Aida |
| Interactive Prototype (if applicable) | Figma | Aida |
| Exported Assets Package | Google Drive / Figma | Aida |
| Design Handoff Document | Figma Dev Mode / Google Docs | Aida |

## WHERE — Tools & Platforms

| Tool | Purpose in This Phase |
|---|---|
| Figma | Research Wall, Sitemap, UI Kit, wireframing, UI design, prototyping, component library, design handoff |
| FigJam | Research Wall collaboration, Sitemap brainstorming, discovery workshops |
| Google Drive | Asset storage, reference materials, client-provided images, font files |
| ClickUp | Design task tracking, approval status, milestone management |
| Slack | Internal design reviews, feedback loops, team notifications |
| Google Meet | Design presentation meetings with client, discovery sessions |
| Email | Client design review links and approval requests |

## HOW — Process Steps

1. **Review Content and Requirements.** Before beginning design, thoroughly review: the approved content package from P3, project requirements document from P2, brand guidelines and assets from P1, and the project brief from P0. Identify any design-specific questions or missing information and resolve before proceeding.

2. **Create Research Wall.** Build a structured Research Wall in Figma or FigJam documenting: Product (core problem being solved, the solution, product format), Brand & Visual Direction (inspiration references, visual style, logo and color direction, visual theme), User Problem (pain points, frustrations, existing confusion, decision barriers), Website Goals (engagement, conversion, friction reduction), Product Page (page structure, selection flow, visual updates), Messaging (tone, language approach, social proof strategy), Sizing & Education (selection method, visual guides, educational approach), and Key Insights (policies, trust builders, pricing strategy). The Research Wall becomes the strategic foundation for all design decisions.

3. **Create Sitemap.** Build a visual Sitemap in Figma showing the complete page hierarchy. Include: project name, facilitator, and date. Document all main pages (Home, Shop, How It Works, Fit & Sizing, About, Contact, etc.) with sub-pages nested visually. Include Utility Pages (Privacy Policy, Customer Account, Search, Terms & Conditions, Cart, Checkout). Use color-coding to distinguish page categories (e.g., purple for home, green for main pages, yellow for utility pages). The sitemap defines the scope and navigation structure for all subsequent design work.

4. **Develop UI Kit — Logos.** Define the logo system in the UI Kit: Default logo (primary usage), Inverse logo (for dark backgrounds), and Favicon. Document usage rules, minimum sizes, and clear space requirements. Include all logo file formats needed for web implementation.

5. **Develop UI Kit — Typography.** Define the complete typography scale in the UI Kit with separate Desktop and Mobile specifications. For each level (H1 through H5, Paragraph large/medium/small, and Accent text) document: font family, font size, line height, letter spacing, font weight, and text case. Include font download links or embed codes. Example structure: H1 — 72/76, H2 — 42/46, H3 — 32/36, H4 — 24/28, H5 — 20/20, Paragraph lg — 24/32, Paragraph md — 20/28, Paragraph sm — 16/24, Accent — 20/28.

6. **Develop UI Kit — Color Schemes.** Define multiple color schemes (e.g., Pink, Green, Brand Pink, Brand Green) where each scheme includes three token groups: Base (background, heading, text, link, link-hover, border), Primary Button (bg, text, border, hover-bg, hover-text, hover-border), and Secondary Button (bg, text, border, hover-bg, hover-text, hover-border). Document all color values as hex codes. Show how each scheme applies to Section components (headings + buttons on backgrounds) so developers understand the theming system.

7. **Develop UI Kit — Buttons & Components.** Design Primary and Secondary button components with Default and Hover states for each color scheme. Document per-state values: background color, text color, and border color. Include button sizing, padding, border-radius, and font specifications. Build additional reusable components: form elements, cards, modals, badges, icons, and loading states as needed by the project.

8. **Develop UI Kit — Page Layout.** Define the page layout system with Desktop and Mobile specifications. Document Page Width (max viewport), Container Width (content area), margins, gutters, and column grid. Include visual diagrams showing the relationship between Page Width and Container Width on both Desktop and Mobile breakpoints.

9. **Create Wireframes.** Design wireframes for all pages defined in the Sitemap. Focus on: page layout and content hierarchy per the Research Wall insights, navigation flow, CTA placement, responsive behavior considerations, user journey mapping, and section structure using the color scheme system. Present wireframes to PM and content lead for internal review before client presentation.

10. **Present Wireframes to Client.** Schedule a design meeting to walk the client through wireframes. Explain layout decisions, user flow, and content placement rationale in context of the Research Wall findings. Collect feedback and document all requested changes. Allow 1 round of wireframe revisions.

11. **Design Desktop Layouts.** Create full-fidelity desktop designs for all pages using approved wireframes, UI Kit, and content. Apply the color scheme system to page sections. Use the defined typography scale, button components, and layout system consistently. Build section components showing how different color schemes apply across the site. Ensure designs accommodate all content from the approved content package.

12. **Design Mobile Layouts.** Create responsive mobile designs for all pages using the mobile typography scale from the UI Kit. Ensure: touch-friendly navigation and buttons, readable typography at mobile sizes using the defined mobile type scale, proper content reflow and hierarchy, mobile-specific UX patterns (hamburger menu, collapsible sections, etc.), mobile Container Width adherence, and consistent color scheme application across breakpoints.

13. **Internal Design Review.** Present complete designs (Research Wall, Sitemap, UI Kit, and all page designs) to the PM, content lead, and dev lead for internal review. Check for: brand consistency with Research Wall direction, content accuracy, development feasibility of the color scheme system, responsive behavior clarity between desktop and mobile type scales, accessibility considerations (contrast ratios across all color schemes), and completeness.

14. **Client Design Review.** Send the client Figma prototype links for desktop and mobile. Schedule a walkthrough meeting to present the full design package: Research Wall insights, Sitemap, UI Kit (explaining the color scheme system, typography, and component library), and page designs. Document all client feedback. Allow up to 2 rounds of design revisions. After each round, get explicit written approval before proceeding.

15. **Prepare Design Handoff.** Once designs are fully approved: enable Figma Dev Mode for the project, export all required assets (icons, images, illustrations, font files) to Google Drive, document the color scheme token system for developer implementation, document the typography scale with exact CSS values for desktop and mobile, list all button states and their color values per scheme, document any animations, transitions, or interactive behaviors, and create a design handoff checklist noting any developer-specific instructions.

16. **Hand Off to Development.** Notify the development team that designs are ready. Share: Figma project link with Dev Mode access (including Research Wall, Sitemap, UI Kit, and all page designs), exported assets folder in Drive (including font files), design handoff document with color scheme tokens, typography specs, and button state values, and section component documentation showing how color schemes apply. Update ClickUp and post in Slack confirming design phase completion.

## Communication — Stakeholder Updates

| Type | Frequency | Audience | Channel |
|---|---|---|---|
| Research Wall & Sitemap Presentation | Once | Client + PM | Google Meet |
| UI Kit Review | Once | Client + PM + Dev Lead | Google Meet / Figma |
| Wireframe Presentation | Once | Client + PM | Google Meet |
| Desktop Design Review | Once (per revision round) | Client + PM | Google Meet / Figma |
| Mobile Design Review | Once (per revision round) | Client + PM | Google Meet / Figma |
| Internal Design Review | Once (before client review) | PM + Dev Lead + Content Lead | Slack / Google Meet |
| Design Handoff Notification | Once (at phase close) | Development Team + PM | Slack |
| Weekly Design Update | Weekly (during design phase) | Internal Team | Slack |

## Escalation — Blocked Phase Protocol

| Trigger | Timeframe | Escalation Action | Escalated To |
|---|---|---|---|
| Client delays design feedback | 5 business days | Send reminder with timeline impact statement | Aida |
| Design feedback still pending | 10 business days | Escalate to PM for direct client outreach | Rinaldo |
| Client requests design changes beyond 2 rounds | Immediately | Notify PM; discuss additional design revision fees | Rinaldo |
| Client wants to change approved content during design | Immediately | Route back to P3 for content revision; pause design on affected pages | Aida + Rinaldo |
| Design complexity exceeds development capability | During internal review | Consult dev lead; simplify design or adjust timeline/budget | Asya + Rinaldo |
| Missing or insufficient brand assets | 2 business days | Request from client; use placeholder with client acknowledgment | Aida + Carlos |
| Color scheme system too complex for platform | During internal review | Simplify scheme count or discuss custom development scope | Asya + Aida + Rinaldo |

## Dependencies — Required Inputs

| Dependency | Source Phase | Impact if Missing |
|---|---|---|
| Approved Content Package | P3 - Project Setup | Cannot design page layouts without final copy and content structure |
| Brand Guidelines & Assets | P1 - Client Onboarding | Need logos, fonts, colors, and brand direction to design |
| Project Requirements Document | P2 - Project Specification | Need to know all pages, features, and functionality to design for |
| Image/Media Direction | P3 - Project Setup | Need to know image requirements per page for layout design |

## Revision Limits & Scope Control

Research Wall: 1 round of revisions included; major strategic changes require PM sign-off

Sitemap: 1 round of structural revisions included; additions after approval may impact timeline

UI Kit: 1 round of revisions included; changes after design phase require Change Order

Wireframes: 1 round of revisions included

Desktop Design: Up to 2 rounds of revisions included; additional rounds billed at hourly rate

Mobile Design: Up to 2 rounds of revisions included; additional rounds billed at hourly rate

Design System: Finalized with design approval; changes after handoff require Change Order

> [!IMPORTANT]
> Any additional revisions beyond the limits above require a Change Order approved by the Project Lead and communicated to the client with associated timeline and cost impact.

## PHASE GATE — Completion Checklist

> [!IMPORTANT]
> ALL items below must be completed before the project can advance to P5 - Inventory (if applicable) or P6 - Development. No development work should begin until designs are fully approved in writing by the client.

| # | Gate Requirement | Status | Date |
|---|---|---|---|
| 1 | Research Wall completed with all discovery sections documented |  |  |
| 2 | Sitemap completed with full page hierarchy and utility pages |  |  |
| 3 | UI Kit completed — Logos (Default, Inverse, Favicon) |  |  |
| 4 | UI Kit completed — Typography scale (Desktop and Mobile) |  |  |
| 5 | UI Kit completed — Color Schemes with Base and Button tokens |  |  |
| 6 | UI Kit completed — Button components (Primary/Secondary with Default/Hover states) |  |  |
| 7 | UI Kit completed — Page Layout system (Desktop and Mobile widths) |  |  |
| 8 | Wireframes completed and client-approved |  |  |
| 9 | Desktop designs completed for all pages with color scheme application |  |  |
| 10 | Mobile designs completed for all pages with mobile typography scale |  |  |
| 11 | Section components documented with color scheme usage examples |  |  |
| 12 | Internal design review completed (PM + Dev Lead sign-off) |  |  |
| 13 | Client design approval received in writing (all pages, desktop + mobile) |  |  |
| 14 | Interactive prototype created (if in scope) |  |  |
| 15 | All assets exported and organized in Google Drive (including font files) |  |  |
| 16 | Design handoff document created with color tokens, typography specs, and dev instructions |  |  |
| 17 | Figma Dev Mode enabled and shared with development team |  |  |
| 18 | ClickUp design tasks marked as complete |  |  |
| 19 | Slack notification posted confirming design phase completion |  |  |

### Phase Gate Sign-Off

| Field | Details | Date |
|---|---|---|
| Project Name |  |  |
| Approved By |  |  |
| Client Rep |  |  |
| Next Phase | P5 - Inventory (if applicable) or P6 - Development |  |
| Notes / Conditions |  |  |

## Data Enrichment (ClickUp export, 2026-04-22)

*Source: portfolio-wide ClickUp export analyzed in `data/analysis/03_sop_gap_and_recommendations.md` and the rollup at `Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md` lines 312–318. Figures preserved verbatim from the analysis pack.*

- **Design volume is material.** 160 tasks begin with the word
  "design"; 23 tasks carry the `design` tag explicitly. Biggest design
  spikes (by task count in client lists): `Steindiamonds.com` (182
  total), `hawaiilabgrown.com` (162), `christopher-salon.com` (130),
  `erikarecords.com` (98). Each of those projects has >50 Figma-linked
  artifacts in the comments/attachments.
- **Design-review bottleneck is real.** 42 tasks sit in `Review`
  status on `hawaiilabgrown.com` alone — this is the single largest
  pile of Review-status work in the portfolio. Consider a time-boxed
  "Design Review Friday" cadence or a second reviewer for Aida.
- **SOP already addresses design-token discipline** (P4 v2). The
  dataset validates why: `Update the design of PDP`
  (1800loosediamonds) and `Update design of Collection page` both
  collected 15–20 comments — exactly the class of issue token/spec
  discipline prevents. Enforcement of token compliance at QA time is
  being hardened in **P7_v4** (per gap doc §C); P4 authoring practice
  remains as documented here.

## Appendix A: Design Brief & Visual Direction Worksheet

<details>
<summary>Expand — Design Brief & Visual Direction Worksheet</summary>

*This worksheet consolidates all design inputs into a single actionable brief for the design team. It follows the Fancy Lab design workflow: Research Wall → Sitemap → UI Kit → Wireframes → Full Design. It synthesizes information from the Project Brief (P0), Onboarding Intake (P1), and Project Setup (P3) into specific design direction, component requirements, and visual standards.*

*Prerequisites: P3 Project Setup must be complete — the designer needs final content strategy, page copy, and image direction before beginning the design workflow.*

### 1. Research Wall — Discovery & Strategic Direction

| Field | Details |
|---|---|
| **Project Name** | *Client/brand name for this project: ___* |
| **Facilitator** | *Design lead name: ___ (e.g., @Aida EVOSEM)* |
| **Date Created** | *Research Wall creation date: ___* |
| **Product — Core Problem** | *What is the core problem the product solves? ___* |
| **Product — The Solution** | *What is the product and how does it solve the problem? ___* |
| **Product — Format** | *Physical product / Digital / Service / SaaS — Details: ___* |
| **Brand & Visual Direction — Inspiration** | *Reference brands or sites that inspire the visual direction: ___* |
| **Brand & Visual Direction — Visual Style** | *Bold & vibrant / Minimal & clean / Luxury / Playful / Editorial — Selected: ___* |
| **Brand & Visual Direction — Logo & Color** | *Keep existing logo: [ ] / Keep core colors: [ ] / New direction needed: [ ] — Notes: ___* |
| **Brand & Visual Direction — Visual Theme** | *Theme or motif for visuals (e.g., fruit-inspired, geometric, organic): ___* |
| **User Problem — Pain Points** | *List key user pain points: 1) ___ 2) ___ 3) ___ 4) ___* |
| **User Problem — Existing Confusion** | *What confuses users about the product/market today? ___* |
| **User Problem — Decision Barriers** | *What prevents users from purchasing? ___* |
| **Website Goals — Engagement** | *Primary engagement goal: ___* |
| **Website Goals — Conversion** | *Primary conversion goal: ___* |
| **Website Goals — Friction Reduction** | *What friction points must the site eliminate? ___* |
| **Product Page — Structure** | *Unified page / Multiple templates / Custom per product — Selected: ___* |
| **Product Page — Selection Flow** | *How users select variants: Dropdown / Visual swatch / Shape-based / Other: ___* |
| **Product Page — Visual Updates** | *Live visual updates on variant selection: [ ] / Static images: [ ] — Notes: ___* |
| **Messaging — Tone** | *Language approach: Softer/empathetic / Direct / Humorous / Clinical — Selected: ___* |
| **Messaging — Social Proof Strategy** | *Reviews strategy: Let reviews support claims / Verified reviews / UGC — Details: ___* |
| **Sizing & Education — Selection Method** | *Traditional sizing: [ ] / Shape-based: [ ] / Quiz: [ ] / Custom: [ ] — Method: ___* |
| **Sizing & Education — Visual Guides** | *Visual education over text: [ ] / Printable PDF: [ ] / Interactive tool: [ ] — Notes: ___* |
| **Key Insights — Return Policy** | *Return policy summary and how it should be communicated: ___* |
| **Key Insights — Trust Builders** | *What builds trust? (e.g., honest messaging, verified reviews, transparency): ___* |
| **Key Insights — Pricing Strategy** | *Discounts: Yes / No / Seasonal only — Strategy: ___* |

### 2. Sitemap — Page Hierarchy & Navigation Structure

| Field | Details |
|---|---|
| **Facilitator** | *Sitemap creator: ___ / Last updated: ___* |
| **Home Page** | *Included: [ ] — Hero concept: ___ — Key sections below fold: ___* |
| **Main Page 1** | *Page name: ___ / Sub-pages: ___ / Color code: ___* |
| **Main Page 2** | *Page name: ___ / Sub-pages: ___ / Color code: ___* |
| **Main Page 3** | *Page name: ___ / Sub-pages: ___ / Color code: ___* |
| **Main Page 4** | *Page name: ___ / Sub-pages: ___ / Color code: ___* |
| **Main Page 5** | *Page name: ___ / Sub-pages: ___ / Color code: ___* |
| **Additional Main Pages** | *List any additional pages with sub-page hierarchy: ___* |
| **Utility Pages** | *[ ] Privacy Policy [ ] Terms & Conditions [ ] Customer Account [ ] Search [ ] Cart [ ] Checkout — Other: ___* |
| **Navigation Structure** | *Desktop: Top nav / Mega menu / Sidebar — Mobile: Hamburger / Bottom nav / Slide drawer — Notes: ___* |
| **Sitemap Color Coding** | *Home: ___ / Main pages: ___ / Sub-pages: ___ / Utility: ___ (document color system used)* |
| **Total Pages in Scope** | *Main pages: ___ / Sub-pages: ___ / Utility pages: ___ / Total: ___* |

### 3. UI Kit — Logo System

| Field | Details |
|---|---|
| **Default Logo** | *Primary logo for standard backgrounds — File format: SVG + PNG — Provided: [ ]* |
| **Inverse Logo** | *Logo for dark backgrounds — File format: SVG + PNG — Provided: [ ]* |
| **Favicon** | *Browser tab icon — Size: 32x32px / 16x16px — File format: ICO / PNG / SVG — Provided: [ ]* |
| **Logo Minimum Size** | *Minimum display width: ___px / Clear space: ___px around logo* |
| **Logo Usage Rules** | *Usage restrictions or guidelines: ___* |

### 4. UI Kit — Typography Scale

| Field | Details |
|---|---|
| **Font Family** | *Primary font: ___ (e.g., Hornbill) / Download link: ___ / License: ___* |
| **Secondary Font (if any)** | *Font: ___ / Usage: ___ / Download link: ___* |
| **H1 — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H2 — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H3 — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H4 — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H5 — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **Paragraph Large — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___* |
| **Paragraph Medium — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___* |
| **Paragraph Small — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___* |
| **Accent Text — Desktop** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H1 — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H2 — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H3 — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H4 — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **H5 — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |
| **Paragraph Large — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___* |
| **Paragraph Medium — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___* |
| **Paragraph Small — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___* |
| **Accent Text — Mobile** | *Size: ___px / Line height: ___px / Letter spacing: ___ / Weight: ___ / Case: ___* |

### 5. UI Kit — Color Scheme System

| Field | Details |
|---|---|
| **Number of Color Schemes** | *Total schemes defined: ___ (e.g., Pink, Green, Brand Pink, Brand Green)* |
| **Scheme 1 — Name** | *Name: ___ (e.g., Pink)* |
| **Scheme 1 — Base Tokens** | *Background: #___ / Heading: #___ / Text: #___ / Link: #___ / Link-hover: #___ / Border: #___* |
| **Scheme 1 — Primary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Scheme 1 — Secondary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Scheme 2 — Name** | *Name: ___ (e.g., Green)* |
| **Scheme 2 — Base Tokens** | *Background: #___ / Heading: #___ / Text: #___ / Link: #___ / Link-hover: #___ / Border: #___* |
| **Scheme 2 — Primary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Scheme 2 — Secondary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Scheme 3 — Name** | *Name: ___ (e.g., Brand Pink)* |
| **Scheme 3 — Base Tokens** | *Background: #___ / Heading: #___ / Text: #___ / Link: #___ / Link-hover: #___ / Border: #___* |
| **Scheme 3 — Primary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Scheme 3 — Secondary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Scheme 4 — Name** | *Name: ___ (e.g., Brand Green)* |
| **Scheme 4 — Base Tokens** | *Background: #___ / Heading: #___ / Text: #___ / Link: #___ / Link-hover: #___ / Border: #___* |
| **Scheme 4 — Primary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Scheme 4 — Secondary BTN** | *BG: #___ / Text: #___ / Border: #___ / Hover-BG: #___ / Hover-Text: #___ / Hover-Border: #___* |
| **Additional Schemes** | *If more than 4 schemes, list additional scheme names and note they follow the same Base + Primary BTN + Secondary BTN structure: ___* |
| **Error/Success Colors** | *Error: #___ / Success: #___ / Warning: #___ / Info: #___* |

### 6. UI Kit — Buttons & Section Components

| Field | Details |
|---|---|
| **Primary Button — Default** | *Each scheme defines: BG / Text / Border colors — Border-radius: ___px / Padding: ___* |
| **Primary Button — Hover** | *Each scheme defines: Hover-BG / Hover-Text / Hover-Border — Transition: ___ms* |
| **Secondary Button — Default** | *Each scheme defines: BG / Text / Border colors — Border-radius: ___px / Padding: ___* |
| **Secondary Button — Hover** | *Each scheme defines: Hover-BG / Hover-Text / Hover-Border — Transition: ___ms* |
| **Button Font Specs** | *Font family: ___ / Size: ___px / Weight: ___ / Case: ___ / Letter spacing: ___* |
| **Section Component Pattern** | *How color schemes apply to page sections: Section Heading + Body + CTAs on scheme background — Documented: [ ]* |
| **Section Heading Component** | *Section heading with color-schemed background — Font: ___ / Size: ___px / Color per scheme: [ ] Documented* |
| **Additional Button Types** | *[ ] Ghost [ ] Text link [ ] Icon button [ ] Disabled state — Notes: ___* |

### 7. UI Kit — Page Layout System

| Field | Details |
|---|---|
| **Desktop — Page Width** | *Max viewport/frame width: ___px (e.g., 1440px)* |
| **Desktop — Container Width** | *Content area max width: ___px (e.g., 1200px)* |
| **Desktop — Margins** | *Left/right page margin: ___px* |
| **Desktop — Grid System** | *Columns: ___ / Gutter: ___px / Column width: ___px* |
| **Mobile — Page Width** | *Mobile frame width: ___px (e.g., 375px)* |
| **Mobile — Container Width** | *Mobile content area width: ___px (e.g., 335px)* |
| **Mobile — Margins** | *Left/right margin: ___px* |
| **Spacing System** | *Base unit: ___px / Section padding: ___ / Component spacing: ___* |

### 8. Wireframe Specifications

| Field | Details |
|---|---|
| **Pages to Wireframe** | *Per Sitemap — list all pages: ___* |
| **Above-the-Fold Priority** | *Homepage: ___ / Collection: ___ / PDP: ___ (what must be visible without scrolling)* |
| **Navigation Wireframe** | *[ ] Header (desktop + mobile) [ ] Mega menu [ ] Mobile drawer [ ] Footer [ ] Breadcrumbs* |
| **Color Scheme Mapping** | *Which color scheme applies to which page sections? Document per page: ___* |
| **Wireframe Revision Rounds** | *Included: 1 round / Additional rounds require change order* |
| **Wireframe Approval Required From** | *Name: ___ (from P1 approval authority map)* |

### 9. Page-by-Page Design Specifications

| Field | Details |
|---|---|
| **Homepage Sections** | *List each section in order: 1) Hero 2) ___ 3) ___ 4) ___ 5) ___ 6) ___ 7) Footer — Color schemes per section: ___* |
| **Homepage Hero Concept** | *Type: Image / Video / Slider / Split / Full-bleed — CTA: ___ — Animation: ___* |
| **Collection Page Layout** | *Grid: 3-col / 4-col / List / Sidebar filters / Top filters / Products per page: ___* |
| **Product Page Layout** | *Per Research Wall: Unified page / Multiple templates — Selection flow: ___ — Live visual updates: [ ]* |
| **Cart Page or Drawer** | *Full page / Slide-out drawer / Both — Upsell section: [ ] — Trust badges: [ ]* |
| **About Page Sections** | *List sections: Story / FAQ / Team / Values / Press — Order: ___* |
| **Education/Sizing Page** | *Per Research Wall: Shape-based selection / Visual education / Printable PDF — Layout: ___* |
| **Custom Page Specifications** | *List each custom page with layout description: ___* |

### 10. Interaction & Animation Specifications

| Field | Details |
|---|---|
| **Page Transition Style** | *None / Fade / Slide / Custom — Duration: ___ms* |
| **Scroll Animations** | *None / Fade-in / Slide-up / Parallax / Stagger — Trigger: On viewport enter / percentage: ___%* |
| **Hover Effects (Desktop)** | *Buttons: ___ / Cards: ___ / Images: ___ / Links: ___ / Nav items: ___* |
| **Micro-Interactions** | *[ ] Add to cart [ ] Wishlist [ ] Variant selection [ ] Search expand — Describe each: ___* |
| **Image Zoom Behavior** | *Hover zoom / Click to lightbox / Pinch on mobile — Selected: ___* |
| **Reduced Motion Support** | *Reduced motion media query support: [ ] / GPU-accelerated only: [ ]* |

### 11. Design Review & Approval Process

| Field | Details |
|---|---|
| **Research Wall Review** | *Client reviewed: [ ] / Internal reviewed: [ ] / Approved: [ ] — Date: ___* |
| **Sitemap Review** | *Client reviewed: [ ] / Approved: [ ] — Date: ___* |
| **UI Kit Review** | *Client reviewed: [ ] / Dev lead reviewed: [ ] / Approved: [ ] — Date: ___* |
| **Desktop Design Revision Rounds** | *Included: 2 rounds / Per-page or holistic review? ___* |
| **Mobile Design Revision Rounds** | *Included: 2 rounds / Reviewed simultaneously with desktop? [ ]* |
| **Client Review Method** | *Figma comments / Email screenshots / Live walkthrough / Combination — Per P1 preference: ___* |
| **Feedback Consolidation** | *Who consolidates client feedback before sending? (from P1): ___* |
| **Design Approval Authority** | *Who gives final design sign-off? (from P1 approval authority map): ___* |
| **Client Feedback SLA** | *Days to provide feedback per round (from P1): ___ business days* |
| **Design Freeze Date** | *Date after which no design changes accepted: ___ / Aligned with P6 dev start: [ ]* |

### 12. Asset Export & Development Handoff

| Field | Details |
|---|---|
| **Figma Dev Mode Enabled** | *All pages inspectable: [ ] / Component documentation added: [ ]* |
| **Font Files Exported** | *Font files provided to dev team: [ ] / Format: OTF / TTF / WOFF2 — Download link shared: [ ]* |
| **Color Scheme Tokens Exported** | *All scheme tokens (Base + Button) documented for dev: [ ] / Format: JSON / CSS variables / Figma tokens: ___* |
| **Typography Specs Exported** | *Desktop + Mobile scale with exact CSS values: [ ] / Responsive breakpoint: ___px* |
| **Button State Values Exported** | *All button states per scheme documented with hex values: [ ]* |
| **Asset Export Format** | *Images: WebP + PNG fallback / Icons: SVG / Illustrations: SVG / Photos: WebP — Compression: ___* |
| **Responsive Behavior Notes** | *Document per component: How does it reflow from desktop → mobile? In Figma: [ ]* |
| **Section Component Documentation** | *How color schemes apply to sections documented for dev: [ ] — Notes: ___* |
| **Interaction Specifications** | *All animations/interactions documented with: Trigger / Duration / Easing / Before+After states: [ ]* |
| **Design-to-Dev Handoff Meeting** | *Scheduled: [ ] / Date: ___ / Attendees: Designer + Lead Dev + PM* |
| **Handoff Document URL** | *Link to design handoff document/page: ___* |

Design Brief Prepared By: ____________________________________ Date: _______________

Design Lead Approval: ____________________________________ Date: _______________

Client Design Sign-Off: ____________________________________ Date: _______________

*Once all designs are client-approved and the development handoff package is complete, this phase gate can be evaluated for advancement to P5 — Inventory.*

</details>
