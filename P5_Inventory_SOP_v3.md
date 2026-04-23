# P5 — Inventory

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
- [Appendix A: Product Data Specification & Import Template](#appendix-a-product-data-specification--import-template)
- [Appendix B: Vendor Feed Validation Sub-SOP](#appendix-b-vendor-feed-validation-sub-sop-jewelry--watch-catalogs)

## Revision History

<details>
<summary>v3.0 (April 2026) — GitHub-render pass</summary>

- Restructured headings: `**BOLD CAPS**` paragraphs → `##` / `###`, so GitHub's outline sidebar populates.
- Replaced empty-header pandoc tables (`|  |  |  |` + bolded content row) with proper pipe tables.
- Converted nested-blockquote process steps (`> **1. Step**`) to ordered lists.
- Unescaped pandoc backslash noise (`\|`, `\-`, `\#`, `\<`, `\>`, `\_`).
- Added TOC, metadata table; wrapped long appendices in `<details>`.
- No content changes — every fact, number, named person, client, and cell preserved verbatim from v2.

</details>

<details>
<summary>v2.0 (April 2026) — ClickUp enrichment</summary>

- v1.0 → v2.0 (April 2026): Added **Vendor Feed Validation Sub-SOP** (new Appendix B + Process Step 9) per `data/analysis/03_sop_gap_and_recommendations.md` §B row "Vendor-feed validation for jewelry/watch catalogs". Evidence: 30 `inventory`-tagged tasks with recurring "fix diameter / fix carat / fix material" patterns on diamond and watch clients.
- Added two new phase-gate items (#13 vendor-feed diff report; #14 spot-check sampling validated) to enforce the new sub-SOP.
- Reinforced the inventory tracking source-of-truth: **all** inventory work must live in the central `Inventory Management` ClickUp list and carry the `inventory` tag, addressing the fragmentation observed in the data (inventory work scattered across client-domain lists).
- Added vendor escalation path and concrete error-rate thresholds for vendor-feed quality.
- Appended new `## Data Enrichment (ClickUp export, 2026-04-22)` section after the Phase Gate sign-off block, porting figures from `Fancy_Lab_Web_Dev_Phase_Gate_SOPs_v2.md` lines 369–376.
- Updated Appendix A internal cross-references from `_v1` to `_v2`.

</details>

## Purpose & Scope

This SOP defines the standard process for collecting, organizing, formatting, and importing all product or service data into the client's e-commerce or content platform. It ensures that all inventory is accurately structured, categorized, and ready for development integration before the build phase begins.

### Phase Objective

Deliver a complete, validated product/service catalog with all required data fields (titles, descriptions, images, pricing, variants, categories, tags, and metadata) imported into the target platform and verified for accuracy.

### Scope Includes

- Product/service data collection from client
- Data formatting and standardization
- Product photography coordination (if applicable)
- Category and tag taxonomy creation
- CSV/data import into platform (Shopify, WooCommerce, etc.)
- Product data validation and QA
- Variant and option configuration
- SEO metadata for products (titles, descriptions, alt text)
- Vendor-feed diffing, spot-checking, and escalation (jewelry / watch catalogs — see Appendix B)

### Scope Excludes

- Product photography or image creation (client responsibility unless contracted)
- Copywriting for marketing pages (covered in P3)
- Platform theme development (covered in P6)
- Pricing strategy or business consulting
- Fulfillment or shipping configuration (covered in P6 - Development)

## WHO — RACI Matrix

| Role | Person(s) | Responsibility |
|---|---|---|
| Responsible | Asya | *Performs the work for this phase, including vendor-feed diffing and spot-check sampling* |
| Accountable | Asya | *Ultimately answerable for completion and for vendor escalation* |
| Consulted | Rinaldo + Carlos | *Provides input and approves deliverables; Rinaldo signs off on vendor escalation letters* |
| Informed | Harry + Aida | *Kept up to date on progress* |

## WHAT — Deliverables

| Deliverable | Format / Location | Owner |
|---|---|---|
| Product Data Template (blank) | Google Sheets / CSV | Asya |
| Completed Product Data Sheet | Google Sheets / CSV | Asya + Client |
| Category & Tag Taxonomy | Google Sheets | Asya |
| Product Image Inventory | Google Drive | Client + Asya |
| Import Validation Report | Google Docs / Sheets | Asya |
| Vendor-Feed Diff Report | Google Sheets (per import) | Asya |
| Vendor-Feed Spot-Check Log | Google Sheets | Asya |
| Platform Product Catalog (imported) | Shopify / CMS | Asya |

## WHERE — Tools & Platforms

| Tool | Purpose in This Phase |
|---|---|
| Google Sheets | Product data template, data formatting, taxonomy planning, vendor-feed diff & spot-check logs |
| Google Drive | Product image storage, data file sharing, archived vendor feeds |
| Shopify / WooCommerce / CMS | Product import, catalog management |
| ClickUp | Inventory task tracking, import status — all inventory work tagged `inventory` and routed to the central `Inventory Management` list |
| Slack | Internal updates, data collection follow-ups |
| Email | Client communication for data collection; vendor escalation correspondence |
| CSV Import Tools | Matrixify (Shopify), WP All Import, or platform-native importers |

## HOW — Process Steps

1. **Send Product Data Template.** Provide the client with a structured product data template (Google Sheet or CSV) that includes all required fields: product title, description, price, compare-at price, SKU, barcode, weight, variants (size, color, etc.), images, category, tags, SEO title, SEO description, and any custom metafields. Include instructions and examples.

2. **Collect Product Data from Client.** Work with the client to populate the template. Schedule a call if needed to walk through the format. Set a clear deadline for data submission. Track progress and send reminders for incomplete data. Validate data as it comes in.

3. **Build Category and Tag Taxonomy.** Create a logical category hierarchy and tag system based on the product catalog. Consider: how users will browse and filter products, SEO keyword alignment, platform-specific collection/category limitations, and cross-selling/upselling groupings.

4. **Collect and Organize Product Images.** Coordinate product image collection from the client. Ensure: consistent image dimensions and quality, proper file naming convention (SKU-based), required views per product (front, back, detail, lifestyle), image optimization for web (file size and format). Organize in Google Drive by product/category.

5. **Format and Validate Data.** Review all submitted product data for: completeness (no empty required fields), consistency (standardized formatting, units, naming), accuracy (prices, descriptions, variants match), SEO optimization (titles and descriptions include target keywords), and platform compatibility (correct CSV format for import tool).

6. **Import Products to Platform.** Using the appropriate import tool (Matrixify for Shopify, WP All Import for WordPress, or native importer), import all product data. Run a test import with a small batch first. Verify: all fields mapped correctly, images linked properly, variants created accurately, categories/tags assigned correctly.

7. **Validate Imported Data.** Systematically review imported products on the platform: spot-check at least 20% of products for accuracy, verify all variants display correctly, confirm images are properly assigned, check pricing and inventory counts, validate SEO metadata, test category/collection pages. Document any issues in a validation report.

8. **Fix Issues and Finalize.** Address any issues found during validation. Re-import or manually fix incorrect data. Get PM sign-off on the final product catalog. Update ClickUp tasks and notify the team via Slack that inventory is complete and ready for development integration.

9. **Vendor-Feed Validation (jewelry / watch catalogs only).** For any client whose catalog is sourced from a third-party vendor feed (diamond suppliers, watch wholesalers, ERP exports), execute the Vendor Feed Validation Sub-SOP in **Appendix B** before considering the import complete. Produce the vendor-feed diff report, complete the spot-check sample, and — if the data-quality threshold is breached — trigger the vendor escalation path. All tasks generated by this step must carry the `inventory` tag and live in the central `Inventory Management` ClickUp list (not in the client-domain list).

## Communication — Stakeholder Updates

| Type | Frequency | Audience | Channel |
|---|---|---|---|
| Data Template Delivery | Once | Client | Email + Google Sheets |
| Data Collection Follow-up | As needed (max 3 reminders) | Client | Email |
| Import Status Update | Once (after import) | PM + Dev Team | Slack |
| Validation Report | Once (after QA) | PM | Google Docs + Slack |
| Vendor-Feed Diff Report | Per import (vendor-fed catalogs) | PM + Asya | Google Sheets + Slack |
| Vendor Escalation Letter | Per breach event | Vendor + Rinaldo (cc) | Email |
| Phase Completion | Once (at phase close) | Full Team | Slack |

## Escalation — Blocked Phase Protocol

| Trigger | Timeframe | Escalation Action | Escalated To |
|---|---|---|---|
| Client not submitting product data | 7 business days | Send reminder with impact on project timeline | Asya |
| Product data still incomplete | 14 business days | Escalate to PM; schedule call with client | Rinaldo |
| Product images not provided | 7 business days | Send specific missing image list; offer placeholder strategy | Asya + Rinaldo |
| Data quality issues (>20% error rate) | Immediately | Return data to client with specific issues; schedule working session | Asya |
| Import tool errors or platform issues | 2 business days | Escalate to dev team for technical resolution | Asya + Dev Lead |
| Product count significantly exceeds scope | Immediately | Notify PM; discuss scope adjustment or additional fees | Rinaldo |
| Vendor-feed error rate >5% in spot-check | Immediately | Trigger Appendix B vendor escalation path | Asya → Rinaldo → Vendor |
| Vendor-feed error rate >10% in spot-check | Immediately | Halt import; PM-led vendor call within 48h; consider alternate vendor | Rinaldo |

## Dependencies — Required Inputs

| Dependency | Source Phase | Impact if Missing |
|---|---|---|
| Approved Design (for product page layout) | P4 - Design | Need to know what product fields are displayed and how |
| Project Setup (for product SEO) | P3 - Project Setup | Keyword research informs product titles and descriptions |
| Platform Setup | P2 - Project Specification | Need dev store configured before product import |
| Client Product Data | Client | Cannot proceed without client-provided product information |
| Vendor Feed Access | Client / Vendor | Required for any catalog sourced from a third-party feed (Nivoda, IDEX, RapNet, vendor ERP, etc.) |

## Revision Limits & Scope Control

Product Data Template: Standard template used; custom fields require PM approval

Category Taxonomy: 1 round of restructuring included; further changes after import require additional effort

Data Re-imports: 1 full re-import included if client submits significantly updated data; additional re-imports billed hourly

Vendor-Feed Re-validation: 1 full vendor-feed validation cycle included per import; additional cycles caused by vendor data-quality regressions billed hourly and trigger an escalation letter to the vendor

*Any additional revisions beyond the limits above require a Change Order approved by the Project Lead and communicated to the client with associated timeline and cost impact.*

## PHASE GATE — Completion Checklist

> [!IMPORTANT]
> ALL items below must be completed before the project can advance to P6 - Development. The development team must have a complete, validated product catalog to integrate into the site build.

| # | Gate Requirement | Status | Date |
|---|---|---|---|
| 1 | Product data template sent to client |  |  |
| 2 | All product data received and validated |  |  |
| 3 | Category and tag taxonomy created and applied |  |  |
| 4 | Product images collected, optimized, and organized |  |  |
| 5 | Products successfully imported to platform |  |  |
| 6 | Import validation completed (min 20% spot-check) |  |  |
| 7 | All data issues identified and resolved |  |  |
| 8 | SEO metadata verified for all products |  |  |
| 9 | Variant and option configurations validated |  |  |
| 10 | PM sign-off on final product catalog |  |  |
| 11 | ClickUp inventory tasks marked as complete |  |  |
| 12 | Slack notification posted confirming inventory phase completion |  |  |
| 13 | Vendor-feed diff report produced (added / removed / changed SKUs) — required for any vendor-fed catalog |  |  |
| 14 | Spot-check sample validated against vendor source (min 5% of changed SKUs, floor 20) — required for any vendor-fed catalog |  |  |

### Phase Gate Sign-Off

| Field | Details | Date |
|---|---|---|
| Project Name |  |  |
| Approved By |  |  |
| Client Rep |  |  |
| Next Phase | P6 - Development |  |
| Notes / Conditions |  |  |

## Data Enrichment (ClickUp export, 2026-04-22)

- **Dedicated ops list exists.** `Inventory Management` list has 34 tasks (14 Completed, 12 Open, 2 Backlog, 4 In Progress, 2 Client Approval) — 41.2 % completion, health **yellow**.
- **Inventory is a persistent post-launch topic, not one-off.** The `inventory` tag shows up 30× across tasks — but many of those live in *client-domain* lists, not in the central `Inventory Management` list. That means inventory work is being tracked in two places; fragmenting it makes reporting unreliable. **v2 corrective action:** all inventory tasks must be created in or moved to the central `Inventory Management` list and carry the `inventory` tag. See Process Step 9 and Appendix B.
- **Representative stuck example:** `868hxpjwv — Correct mm information in the product description and search functionality` on `watchcollectorsllc.com` (Open since 2026-03-17). The same pattern ("fix data for all watches with X diameter") recurs across `beverlyhillswatch.com`, `Steindiamonds.com`, and `sellmewatch.com` — evidence that **diamond/watch-vendor feed validation** deserves its own sub-SOP under P5 (now codified in Appendix B).
- **Recommended checklist add** (from the data, now applied as Gate #13): "Run vendor-feed diff between last import and current feed; flag any SKUs where diameter / carat / material mismatch."

## Appendix A: Product Data Specification & Import Template

<details>
<summary>Expand — Product Data Specification & Import Template</summary>

*This specification defines the complete product data structure, import requirements, taxonomy, and quality standards for the e-commerce catalog. It ensures consistent product data across all collections, variants, and metafields before development begins.*

*Prerequisites: P0 brief (product scope), P1 intake (inventory management details), and P3 content strategy (collection hierarchy, SEO keywords) must be complete. For vendor-fed catalogs, also see Appendix B of this document (`P5_Inventory_SOP_v3.md`).*

### 1. Catalog Overview & Scope

| Field | Details |
|---|---|
| **Total SKUs at Launch** | *Number: ___ / Source: P0 brief / Verified: [ ]* |
| **Product Types** | *List all product types: ___ (e.g., Rings, Necklaces, Earrings, Bracelets — or Apparel, Accessories, Home)* |
| **Collections Planned** | *Total: ___ / Top-level: ___ / Sub-collections: ___ / Automated vs Manual: ___* |
| **Variant Types** | *What product options exist? [ ] Size [ ] Color [ ] Material [ ] Length [ ] Custom: ___* |
| **Max Variants per Product** | *Shopify limit: 100 variant combinations per product / Estimated max: ___* |
| **Product Data Source** | *[ ] CSV from client [ ] Existing Shopify export [ ] ERP feed [ ] Manual entry [ ] API import — Source: ___* |
| **Multi-Location Inventory?** | *Yes / No — Locations: ___ / Primary warehouse: ___* |
| **Vendor / Supplier List** | *List all vendors/brands: ___* |

### 2. Product Data Template Fields

| Field | Details |
|---|---|
| **Handle (URL slug)** | *Format: lowercase-hyphenated / Auto-generate or manual? ___ / Max length: 255 chars* |
| **Title** | *Convention: [Brand] [Product Name] [Variant Key] / Max recommended: 70 chars / Include target keyword: [ ]* |
| **Body HTML (Description)** | *From P3 content: [ ] / Rich text / Min length: ___ words / Include SEO keyword: [ ] / Template: ___* |
| **Vendor** | *Brand/vendor name for each product / Consistent naming: [ ]* |
| **Product Type** | *Standardized type from taxonomy above / Mapping to Shopify product type: ___* |
| **Tags** | *Tag conventions: ___ / Max per product: ___ / Automated collection tags: ___* |
| **Published Scope** | *Web / Point of Sale / Both — Default: ___* |
| **Option1 Name / Values** | *Option: ___ / Values: ___ (e.g., Size: S, M, L, XL)* |
| **Option2 Name / Values** | *Option: ___ / Values: ___ (e.g., Color: Black, White, Navy)* |
| **Option3 Name / Values** | *Option: ___ / Values: ___ (if applicable)* |
| **Variant SKU Convention** | *Format: [Brand]-[Type]-[Color]-[Size] / Example: ___* |
| **Variant Price** | *Currency: ___ / Tax-inclusive? [ ] / Compare-at price (original/sale)? [ ]* |
| **Variant Weight** | *Unit: g / kg / lb / oz / Required for shipping calculations: [ ]* |
| **Variant Barcode** | *UPC / EAN / ISBN — Available? [ ] / Required for POS? [ ]* |
| **Inventory Tracking** | *Track quantity: [ ] / Allow overselling: [ ] / Inventory policy: deny / continue* |

### 3. Product Metafields & Custom Data

| Field | Details |
|---|---|
| **Metafield Definitions Needed** | *List each custom data field: ___* |
| **Specifications / Attributes** | *e.g., Metal type, Carat weight, Stone type, Dimensions, Material composition: ___* |
| **Care Instructions** | *Standard per product type or custom per product? ___ / Format: Text / Icon-based / Both* |
| **Certifications / Compliance** | *e.g., Conflict-free, GIA certified, Fair Trade, Organic — Field type: ___* |
| **Shipping Attributes** | *Fragile? [ ] / Oversized? [ ] / Hazmat? [ ] / Special handling notes: ___* |
| **Cross-Sell / Upsell References** | *How are related products linked? Metafield / Tag-based / Manual / AI: ___* |
| **Custom Badge / Label** | *Sale / New / Bestseller / Limited Edition — Controlled by metafield? [ ] / Tag? [ ]* |

### 4. Product Image Specifications

| Field | Details |
|---|---|
| **Image Naming Convention** | *Format: [handle]-[angle]-[number].webp / Example: gold-ring-front-01.webp* |
| **Minimum Resolution** | *Width: ___px / Height: ___px / Recommended: 2048x2048px square* |
| **Aspect Ratio** | *Square 1:1 / Portrait 3:4 / Landscape 4:3 / Mixed (not recommended): ___* |
| **Required Angles per Product** | *[ ] Front [ ] Back [ ] Side [ ] Detail [ ] Lifestyle [ ] Scale — Min images: ___* |
| **Background Standard** | *Pure white (#FFFFFF) / Transparent / Lifestyle / Mixed: ___* |
| **Alt Text Convention** | *Format: [Brand] [Product Name] [Angle/Detail] — Keyword-optimized from P3: [ ]* |
| **Variant Image Mapping** | *Do color variants have unique images? [ ] / How are they matched? Filename / Position / Manual* |
| **Image Optimization** | *Format: WebP preferred / Max file size: ___KB / Compression: ___ / Lazy loading: [ ]* |

### 5. Collection Configuration

| Field | Details |
|---|---|
| **Manual Collections** | *List: ___ / Criteria for inclusion: ___* |
| **Automated Collections** | *List with conditions: ___ (e.g., Tag = 'new-arrival' AND Type = 'Ring')* |
| **Collection Sort Order** | *Default: Best selling / Manual / Price / Newest / Alphabetical — Per collection or global? ___* |
| **Collection Page SEO** | *Per collection: Title tag / Meta description / H1 / Intro text — From P3 keyword map: [ ]* |
| **Collection Image** | *Per collection: Featured image required? [ ] / Banner image? [ ] / Size: ___* |
| **Filters / Faceted Navigation** | *Filter by: [ ] Price [ ] Color [ ] Size [ ] Vendor [ ] Availability [ ] Custom: ___* |

### 6. Import Process & Data Validation

| Field | Details |
|---|---|
| **Import Method** | *[ ] Shopify CSV import [ ] Matrixify (bulk) [ ] API script [ ] Manual entry — Method: ___* |
| **Data Validation Rules** | *Required fields: ___ / Format checks: ___ / Price validation (> $0): [ ] / SKU uniqueness: [ ]* |
| **Test Import Count** | *Import first ___ products as test batch / Validate before full import: [ ]* |
| **Spot Check Coverage** | *Minimum: 20% of imported products manually verified / Method: ___* |
| **Image Upload Verification** | *All images uploaded? [ ] / Alt text populated? [ ] / Variant mapping correct? [ ]* |
| **Collection Assignment Verified** | *All products in correct collections? [ ] / Automated rules firing correctly? [ ]* |
| **Metafield Data Verified** | *All metafields populated? [ ] / Rendering correctly on PDP? [ ]* |
| **Import Error Log** | *Errors encountered: ___ / Resolution: ___ / Re-import needed? [ ]* |
| **Final Product Count Verified** | *Expected: ___ / Actual imported: ___ / Discrepancy: ___ / Resolved: [ ]* |

Inventory Setup Completed By: ____________________________ Date: _______________

Data Validation By: ____________________________ Date: _______________

PM Sign-Off: ____________________________ Date: _______________

*Once all product data is imported, validated, and organized into collections, this phase gate can be evaluated for advancement to P6 — Development.*

</details>

## Appendix B: Vendor Feed Validation Sub-SOP (jewelry / watch catalogs)

<details>
<summary>Expand — Vendor Feed Validation Sub-SOP</summary>

*This sub-SOP applies to any client whose product catalog is sourced — in whole or in part — from a third-party vendor feed. Typical examples: diamond suppliers (Nivoda, IDEX, RapNet, MyDiamonds), watch wholesalers (BOSS Logics, vendor ERP exports), and any recurring CSV/API feed that the client does not author by hand. It exists because 30 `inventory`-tagged ClickUp tasks across `watchcollectorsllc.com`, `beverlyhillswatch.com`, `Steindiamonds.com`, and `sellmewatch.com` show a recurring "fix diameter / fix carat / fix material" pattern — vendor data quality is a recurring post-launch fire and needs a hard gate, not a habit.*

**Owner:** Asya (per P5 RACI). **Escalation owner:** Rinaldo.

### B.1 — Required artifacts per import

| Artifact | Format / Location | Owner |
|---|---|---|
| Prior feed snapshot | CSV in Google Drive (`/Vendor Feeds/<client>/<YYYY-MM-DD>.csv`) | Asya |
| Current feed snapshot | CSV in Google Drive (same folder) | Asya |
| Vendor-Feed Diff Report | Google Sheet — tabs: `Added`, `Removed`, `Changed`, `Summary` | Asya |
| Spot-Check Log | Google Sheet — one row per sampled SKU, with vendor-source link/screenshot | Asya |
| Vendor Escalation Letter (if breached) | Email draft + Google Doc archive | Asya, signed by Rinaldo |

### B.2 — Vendor-feed diffing

Every inventory import must be diffed against the prior feed before any data is pushed to the platform. The diff must produce, at a minimum:

1. **Added SKUs** — present in current feed, absent in prior.
2. **Removed SKUs** — present in prior, absent in current. Removed SKUs on the live store must be unpublished or 301-redirected (coordinate with P6 dev).
3. **Changed SKUs** — present in both, but with at least one differing field. Field-level diff required for: `price`, `availability`, and the category-specific attributes below.

Tooling: Matrixify diff for Shopify-sourced feeds; otherwise a Google Sheets diff template (or a small script in Apps Script). Archive both the prior and current CSVs in Google Drive — never overwrite.

### B.3 — Spot-check sampling

After the diff, validate a random sample of **changed SKUs** against the vendor's source-of-truth (vendor portal, certificate PDF, or vendor API lookup):

- **Sample size:** 5% of changed SKUs, with a floor of **20 SKUs**. If fewer than 20 SKUs changed, validate **all** of them.
- **Watches — fields to verify against vendor source:** case diameter (mm), water resistance (ATM / m), movement type, case material, bezel material, dial color, reference number.
- **Diamonds — fields to verify against vendor source:** carat weight, cut, clarity, color, certificate number (GIA / IGI / AGS), measurements (mm × mm × mm), fluorescence.
- Each sampled SKU is logged in the Spot-Check Log with: SKU, fields checked, vendor source URL/screenshot, pass/fail, notes.

### B.4 — Error rate calculation

Error rate = (SKUs with at least one mismatched field) ÷ (SKUs sampled). Rates are evaluated per import:

| Error rate | Action |
|---|---|
| 0–2% | Pass. Proceed with import. Note in Vendor-Feed Diff Report `Summary` tab. |
| >2 – ≤5% | Conditional pass. Asya corrects the 2% delta manually before publish; logs each correction; flags pattern in Slack `#inventory`. |
| >5 – ≤10% | **Breach.** Trigger the escalation path in B.5. Do not publish until vendor responds or Rinaldo authorizes a manual cleanup pass. |
| >10% | **Hard breach.** Halt the import. PM-led vendor call within 48 business hours. Do not advance the P5 phase gate. Consider alternate vendor. |

The 5% threshold is the gating one — derived from the observed error volume in the ClickUp data; the 10% threshold is a stop-the-line boundary. Both thresholds are reviewed quarterly by Asya + Rinaldo and re-tuned as evidence accumulates.

### B.5 — Vendor escalation path

When the >5% threshold is breached, Asya executes the following within 2 business days:

1. **Compile evidence pack:** the Vendor-Feed Diff Report, the Spot-Check Log, and screenshots/PDFs of the vendor-source values for each mismatched SKU. Save to Google Drive under `/Vendor Feeds/<client>/escalations/<YYYY-MM-DD>/`.
2. **Draft escalation letter** (email + archived Google Doc): summary table of mismatched fields, error rate, business impact (catalog blocked / publish delayed), requested remediation (corrected feed within X business days, root-cause statement).
3. **Route to Rinaldo** for sign-off via Slack DM. Rinaldo sends from his address with Asya cc'd; the client's primary contact is also cc'd so they have visibility into the vendor relationship.
4. **Track vendor response** as a ClickUp task in the central `Inventory Management` list with the `inventory` tag and a 5-business-day due date. If no response by due date, Rinaldo escalates by phone.
5. **Close the loop:** when the vendor delivers a corrected feed, restart B.2–B.4 against the new feed. The spot-check sample for the re-validation must explicitly include every previously-mismatched SKU plus a fresh random sample of equal size.

### B.6 — ClickUp routing rules

- Every task generated under this sub-SOP carries the `inventory` tag.
- Every task lives in the central `Inventory Management` list — **not** in the client-domain list. (The current data shows inventory work fragmented across two locations; this rule eliminates that.)
- Task title convention: `[<client-domain>] <action> — <vendor>` (e.g., `[watchcollectorsllc.com] Vendor diff + spot-check — Nivoda`).
- Sub-tasks: one per artifact in B.1.

### B.7 — Phase-gate linkage

Items #13 and #14 in the main P5 Phase Gate Completion Checklist (vendor-feed diff report produced; spot-check sample validated) cannot be marked complete until the artifacts in B.1 exist in Google Drive and the Spot-Check Log shows an error rate at or below the 5% threshold (or a documented Rinaldo-authorized exception).

Vendor-Feed Validation Completed By: ____________________________ Date: _______________

Vendor Escalation (if any) Approved By: ____________________________ Date: _______________

</details>
