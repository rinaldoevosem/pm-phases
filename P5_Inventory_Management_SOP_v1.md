**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P5**

**INVENTORY MANAGEMENT**

Standard Operating Procedure & Phase Gate Document

v1.0 \| February 2026 \| Confidential

**PURPOSE & SCOPE**

This SOP defines the standard process for collecting, organizing,
formatting, and importing all product or service data into the client's
e-commerce or content platform. It ensures that all inventory is
accurately structured, categorized, and ready for development
integration before the build phase begins.

**Phase Objective**

Deliver a complete, validated product/service catalog with all required
data fields (titles, descriptions, images, pricing, variants,
categories, tags, and metadata) imported into the target platform and
verified for accuracy.

**Scope Includes**

> \- Product/service data collection from client
>
> \- Data formatting and standardization
>
> \- Product photography coordination (if applicable)
>
> \- Category and tag taxonomy creation
>
> \- CSV/data import into platform (Shopify, WooCommerce, etc.)
>
> \- Product data validation and QA
>
> \- Variant and option configuration
>
> \- SEO metadata for products (titles, descriptions, alt text)

**Scope Excludes**

> \- Product photography or image creation (client responsibility unless
> contracted)
>
> \- Copywriting for marketing pages (covered in P3)
>
> \- Platform theme development (covered in P6)
>
> \- Pricing strategy or business consulting
>
> \- Fulfillment or shipping configuration (covered in P6 - Development)

**WHO - RACI MATRIX**

|  |  |  |
|:---|:---|:---|
| **Role** | **Person(s)** | **Responsibility** |
| **Responsible** | Asya | *Performs the work for this phase* |
| **Accountable** | Asya | *Ultimately answerable for completion* |
| **Consulted** | Rinaldo + Carlos | *Provides input and approves deliverables* |
| **Informed** | Harry + Aida | *Kept up to date on progress* |

**WHAT - DELIVERABLES**

|  |  |  |
|:---|:---|:---|
| **Deliverable** | **Format / Location** | **Owner** |
| **Product Data Template (blank)** | Google Sheets / CSV | Asya |
| **Completed Product Data Sheet** | Google Sheets / CSV | Asya + Client |
| **Category & Tag Taxonomy** | Google Sheets | Asya |
| **Product Image Inventory** | Google Drive | Client + Asya |
| **Import Validation Report** | Google Docs / Sheets | Asya |
| **Platform Product Catalog (imported)** | Shopify / CMS | Asya |

**WHERE - TOOLS & PLATFORMS**

|  |  |
|:---|:---|
| **Tool** | **Purpose in This Phase** |
| **Google Sheets** | Product data template, data formatting, taxonomy planning |
| **Google Drive** | Product image storage, data file sharing |
| **Shopify / WooCommerce / CMS** | Product import, catalog management |
| **ClickUp** | Inventory task tracking, import status |
| **Slack** | Internal updates, data collection follow-ups |
| **Email** | Client communication for data collection |
| **CSV Import Tools** | Matrixify (Shopify), WP All Import, or platform-native importers |

**HOW - PROCESS STEPS**

> **1. Send Product Data Template**
>
> Provide the client with a structured product data template (Google
> Sheet or CSV) that includes all required fields: product title,
> description, price, compare-at price, SKU, barcode, weight, variants
> (size, color, etc.), images, category, tags, SEO title, SEO
> description, and any custom metafields. Include instructions and
> examples.
>
> **2. Collect Product Data from Client**
>
> Work with the client to populate the template. Schedule a call if
> needed to walk through the format. Set a clear deadline for data
> submission. Track progress and send reminders for incomplete data.
> Validate data as it comes in.
>
> **3. Build Category and Tag Taxonomy**
>
> Create a logical category hierarchy and tag system based on the
> product catalog. Consider: how users will browse and filter products,
> SEO keyword alignment, platform-specific collection/category
> limitations, and cross-selling/upselling groupings.
>
> **4. Collect and Organize Product Images**
>
> Coordinate product image collection from the client. Ensure:
> consistent image dimensions and quality, proper file naming convention
> (SKU-based), required views per product (front, back, detail,
> lifestyle), image optimization for web (file size and format).
> Organize in Google Drive by product/category.
>
> **5. Format and Validate Data**
>
> Review all submitted product data for: completeness (no empty required
> fields), consistency (standardized formatting, units, naming),
> accuracy (prices, descriptions, variants match), SEO optimization
> (titles and descriptions include target keywords), and platform
> compatibility (correct CSV format for import tool).
>
> **6. Import Products to Platform**
>
> Using the appropriate import tool (Matrixify for Shopify, WP All
> Import for WordPress, or native importer), import all product data.
> Run a test import with a small batch first. Verify: all fields mapped
> correctly, images linked properly, variants created accurately,
> categories/tags assigned correctly.
>
> **7. Validate Imported Data**
>
> Systematically review imported products on the platform: spot-check at
> least 20% of products for accuracy, verify all variants display
> correctly, confirm images are properly assigned, check pricing and
> inventory counts, validate SEO metadata, test category/collection
> pages. Document any issues in a validation report.
>
> **8. Fix Issues and Finalize**
>
> Address any issues found during validation. Re-import or manually fix
> incorrect data. Get PM sign-off on the final product catalog. Update
> ClickUp tasks and notify the team via Slack that inventory is complete
> and ready for development integration.

**COMMUNICATION - STAKEHOLDER UPDATES**

|  |  |  |  |
|:---|:---|:---|:---|
| **Type** | **Frequency** | **Audience** | **Channel** |
| Data Template Delivery | Once | Client | Email + Google Sheets |
| Data Collection Follow-up | As needed (max 3 reminders) | Client | Email |
| Import Status Update | Once (after import) | PM + Dev Team | Slack |
| Validation Report | Once (after QA) | PM | Google Docs + Slack |
| Phase Completion | Once (at phase close) | Full Team | Slack |

**ESCALATION - BLOCKED PHASE PROTOCOL**

|  |  |  |  |
|:---|:---|:---|:---|
| **Trigger** | **Timeframe** | **Escalation Action** | **Escalated To** |
| Client not submitting product data | 7 business days | Send reminder with impact on project timeline | Asya |
| Product data still incomplete | 14 business days | Escalate to PM; schedule call with client | Rinaldo |
| Product images not provided | 7 business days | Send specific missing image list; offer placeholder strategy | Asya + Rinaldo |
| Data quality issues (\>20% error rate) | Immediately | Return data to client with specific issues; schedule working session | Asya |
| Import tool errors or platform issues | 2 business days | Escalate to dev team for technical resolution | Asya + Dev Lead |
| Product count significantly exceeds scope | Immediately | Notify PM; discuss scope adjustment or additional fees | Rinaldo |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **Approved Design (for product page layout)** | P4 - Branding & Design | Need to know what product fields are displayed and how |
| **Content Strategy (for product SEO)** | P3 - Content Strategy & Copywriting | Keyword research informs product titles and descriptions |
| **Platform Setup** | P2 - Project Kickoff | Need dev store configured before product import |
| **Client Product Data** | Client | Cannot proceed without client-provided product information |

**REVISION LIMITS & SCOPE CONTROL**

Product Data Template: Standard template used; custom fields require PM
approval

Category Taxonomy: 1 round of restructuring included; further changes
after import require additional effort

Data Re-imports: 1 full re-import included if client submits
significantly updated data; additional re-imports billed hourly

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

**PHASE GATE - COMPLETION CHECKLIST**

*ALL items below must be completed before the project can advance to
P6 - Development. The development team must have a complete, validated
product catalog to integrate into the site build.*

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **1** | Product data template sent to client |  |  |
| **2** | All product data received and validated |  |  |
| **3** | Category and tag taxonomy created and applied |  |  |
| **4** | Product images collected, optimized, and organized |  |  |
| **5** | Products successfully imported to platform |  |  |
| **6** | Import validation completed (min 20% spot-check) |  |  |
| **7** | All data issues identified and resolved |  |  |
| **8** | SEO metadata verified for all products |  |  |
| **9** | Variant and option configurations validated |  |  |
| **10** | PM sign-off on final product catalog |  |  |
| **11** | ClickUp inventory tasks marked as complete |  |  |
| **12** | Slack notification posted confirming inventory phase completion |  |  |

**Phase Gate Sign-Off**

|                        |                  |          |
|:-----------------------|:-----------------|:---------|
| **Field**              | **Details**      | **Date** |
| **Project Name**       |                  |          |
| **Approved By**        |                  |          |
| **Client Rep**         |                  |          |
| **Next Phase**         | P6 - Development |          |
| **Notes / Conditions** |                  |          |

**APPENDIX A: PRODUCT DATA SPECIFICATION & IMPORT TEMPLATE**

*This specification defines the complete product data structure, import
requirements, taxonomy, and quality standards for the e-commerce
catalog. It ensures consistent product data across all collections,
variants, and metafields before development begins.*

*Prerequisites: P0 brief (product scope), P1 intake (inventory
management details), and P3 content strategy (collection hierarchy, SEO
keywords) must be complete.*

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 65%" />
</colgroup>
<tbody>
<tr>
<td colspan="2"><strong>1. CATALOG OVERVIEW &amp; SCOPE</strong></td>
</tr>
<tr>
<td><strong>Total SKUs at Launch</strong></td>
<td><em>Number: ___ / Source: P0 brief / Verified: [ ]</em></td>
</tr>
<tr>
<td><strong>Product Types</strong></td>
<td><em>List all product types: ___ (e.g., Rings, Necklaces, Earrings,
Bracelets — or Apparel, Accessories, Home)</em></td>
</tr>
<tr>
<td><strong>Collections Planned</strong></td>
<td><em>Total: ___ / Top-level: ___ / Sub-collections: ___ / Automated
vs Manual: ___</em></td>
</tr>
<tr>
<td><strong>Variant Types</strong></td>
<td><em>What product options exist? [ ] Size [ ] Color [ ] Material [ ]
Length [ ] Custom: ___</em></td>
</tr>
<tr>
<td><strong>Max Variants per Product</strong></td>
<td><em>Shopify limit: 100 variant combinations per product / Estimated
max: ___</em></td>
</tr>
<tr>
<td><strong>Product Data Source</strong></td>
<td><em>[ ] CSV from client [ ] Existing Shopify export [ ] ERP feed [ ]
Manual entry [ ] API import — Source: ___</em></td>
</tr>
<tr>
<td><strong>Multi-Location Inventory?</strong></td>
<td><em>Yes / No — Locations: ___ / Primary warehouse: ___</em></td>
</tr>
<tr>
<td><strong>Vendor / Supplier List</strong></td>
<td><em>List all vendors/brands: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>2. PRODUCT DATA TEMPLATE FIELDS</strong></td>
</tr>
<tr>
<td><strong>Handle (URL slug)</strong></td>
<td><em>Format: lowercase-hyphenated / Auto-generate or manual? ___ /
Max length: 255 chars</em></td>
</tr>
<tr>
<td><strong>Title</strong></td>
<td><em>Convention: [Brand] [Product Name] [Variant Key] / Max
recommended: 70 chars / Include target keyword: [ ]</em></td>
</tr>
<tr>
<td><strong>Body HTML (Description)</strong></td>
<td><em>From P3 content: [ ] / Rich text / Min length: ___ words /
Include SEO keyword: [ ] / Template: ___</em></td>
</tr>
<tr>
<td><strong>Vendor</strong></td>
<td><em>Brand/vendor name for each product / Consistent naming: [
]</em></td>
</tr>
<tr>
<td><strong>Product Type</strong></td>
<td><em>Standardized type from taxonomy above / Mapping to Shopify
product type: ___</em></td>
</tr>
<tr>
<td><strong>Tags</strong></td>
<td><em>Tag conventions: ___ / Max per product: ___ / Automated
collection tags: ___</em></td>
</tr>
<tr>
<td><strong>Published Scope</strong></td>
<td><em>Web / Point of Sale / Both — Default: ___</em></td>
</tr>
<tr>
<td><strong>Option1 Name / Values</strong></td>
<td><em>Option: ___ / Values: ___ (e.g., Size: S, M, L, XL)</em></td>
</tr>
<tr>
<td><strong>Option2 Name / Values</strong></td>
<td><em>Option: ___ / Values: ___ (e.g., Color: Black, White,
Navy)</em></td>
</tr>
<tr>
<td><strong>Option3 Name / Values</strong></td>
<td><em>Option: ___ / Values: ___ (if applicable)</em></td>
</tr>
<tr>
<td><strong>Variant SKU Convention</strong></td>
<td><em>Format: [Brand]-[Type]-[Color]-[Size] / Example: ___</em></td>
</tr>
<tr>
<td><strong>Variant Price</strong></td>
<td><em>Currency: ___ / Tax-inclusive? [ ] / Compare-at price
(original/sale)? [ ]</em></td>
</tr>
<tr>
<td><strong>Variant Weight</strong></td>
<td><em>Unit: g / kg / lb / oz / Required for shipping calculations: [
]</em></td>
</tr>
<tr>
<td><strong>Variant Barcode</strong></td>
<td><em>UPC / EAN / ISBN — Available? [ ] / Required for POS? [
]</em></td>
</tr>
<tr>
<td><strong>Inventory Tracking</strong></td>
<td><em>Track quantity: [ ] / Allow overselling: [ ] / Inventory policy:
deny / continue</em></td>
</tr>
<tr>
<td colspan="2"><strong>3. PRODUCT METAFIELDS &amp; CUSTOM
DATA</strong></td>
</tr>
<tr>
<td><strong>Metafield Definitions Needed</strong></td>
<td><em>List each custom data field: ___</em></td>
</tr>
<tr>
<td><strong>Specifications / Attributes</strong></td>
<td><em>e.g., Metal type, Carat weight, Stone type, Dimensions, Material
composition: ___</em></td>
</tr>
<tr>
<td><strong>Care Instructions</strong></td>
<td><em>Standard per product type or custom per product? ___ / Format:
Text / Icon-based / Both</em></td>
</tr>
<tr>
<td><strong>Certifications / Compliance</strong></td>
<td><em>e.g., Conflict-free, GIA certified, Fair Trade, Organic — Field
type: ___</em></td>
</tr>
<tr>
<td><strong>Shipping Attributes</strong></td>
<td><em>Fragile? [ ] / Oversized? [ ] / Hazmat? [ ] / Special handling
notes: ___</em></td>
</tr>
<tr>
<td><strong>Cross-Sell / Upsell References</strong></td>
<td><em>How are related products linked? Metafield / Tag-based / Manual
/ AI: ___</em></td>
</tr>
<tr>
<td><strong>Custom Badge / Label</strong></td>
<td><em>Sale / New / Bestseller / Limited Edition — Controlled by
metafield? [ ] / Tag? [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>4. PRODUCT IMAGE SPECIFICATIONS</strong></td>
</tr>
<tr>
<td><strong>Image Naming Convention</strong></td>
<td><em>Format: [handle]-[angle]-[number].webp / Example:
gold-ring-front-01.webp</em></td>
</tr>
<tr>
<td><strong>Minimum Resolution</strong></td>
<td><em>Width: ___px / Height: ___px / Recommended: 2048x2048px
square</em></td>
</tr>
<tr>
<td><strong>Aspect Ratio</strong></td>
<td><em>Square 1:1 / Portrait 3:4 / Landscape 4:3 / Mixed (not
recommended): ___</em></td>
</tr>
<tr>
<td><strong>Required Angles per Product</strong></td>
<td><em>[ ] Front [ ] Back [ ] Side [ ] Detail [ ] Lifestyle [ ] Scale —
Min images: ___</em></td>
</tr>
<tr>
<td><strong>Background Standard</strong></td>
<td><em>Pure white (#FFFFFF) / Transparent / Lifestyle / Mixed:
___</em></td>
</tr>
<tr>
<td><strong>Alt Text Convention</strong></td>
<td><em>Format: [Brand] [Product Name] [Angle/Detail] —
Keyword-optimized from P3: [ ]</em></td>
</tr>
<tr>
<td><strong>Variant Image Mapping</strong></td>
<td><em>Do color variants have unique images? [ ] / How are they
matched? Filename / Position / Manual</em></td>
</tr>
<tr>
<td><strong>Image Optimization</strong></td>
<td><em>Format: WebP preferred / Max file size: ___KB / Compression: ___
/ Lazy loading: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>5. COLLECTION CONFIGURATION</strong></td>
</tr>
<tr>
<td><strong>Manual Collections</strong></td>
<td><em>List: ___ / Criteria for inclusion: ___</em></td>
</tr>
<tr>
<td><strong>Automated Collections</strong></td>
<td><em>List with conditions: ___ (e.g., Tag = 'new-arrival' AND Type =
'Ring')</em></td>
</tr>
<tr>
<td><strong>Collection Sort Order</strong></td>
<td><em>Default: Best selling / Manual / Price / Newest / Alphabetical —
Per collection or global? ___</em></td>
</tr>
<tr>
<td><strong>Collection Page SEO</strong></td>
<td><em>Per collection: Title tag / Meta description / H1 / Intro text —
From P3 keyword map: [ ]</em></td>
</tr>
<tr>
<td><strong>Collection Image</strong></td>
<td><em>Per collection: Featured image required? [ ] / Banner image? [ ]
/ Size: ___</em></td>
</tr>
<tr>
<td><strong>Filters / Faceted Navigation</strong></td>
<td><em>Filter by: [ ] Price [ ] Color [ ] Size [ ] Vendor [ ]
Availability [ ] Custom: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>6. IMPORT PROCESS &amp; DATA
VALIDATION</strong></td>
</tr>
<tr>
<td><strong>Import Method</strong></td>
<td><em>[ ] Shopify CSV import [ ] Matrixify (bulk) [ ] API script [ ]
Manual entry — Method: ___</em></td>
</tr>
<tr>
<td><strong>Data Validation Rules</strong></td>
<td><em>Required fields: ___ / Format checks: ___ / Price validation
(&gt; $0): [ ] / SKU uniqueness: [ ]</em></td>
</tr>
<tr>
<td><strong>Test Import Count</strong></td>
<td><em>Import first ___ products as test batch / Validate before full
import: [ ]</em></td>
</tr>
<tr>
<td><strong>Spot Check Coverage</strong></td>
<td><em>Minimum: 20% of imported products manually verified / Method:
___</em></td>
</tr>
<tr>
<td><strong>Image Upload Verification</strong></td>
<td><em>All images uploaded? [ ] / Alt text populated? [ ] / Variant
mapping correct? [ ]</em></td>
</tr>
<tr>
<td><strong>Collection Assignment Verified</strong></td>
<td><em>All products in correct collections? [ ] / Automated rules
firing correctly? [ ]</em></td>
</tr>
<tr>
<td><strong>Metafield Data Verified</strong></td>
<td><em>All metafields populated? [ ] / Rendering correctly on PDP? [
]</em></td>
</tr>
<tr>
<td><strong>Import Error Log</strong></td>
<td><em>Errors encountered: ___ / Resolution: ___ / Re-import needed? [
]</em></td>
</tr>
<tr>
<td><strong>Final Product Count Verified</strong></td>
<td><em>Expected: ___ / Actual imported: ___ / Discrepancy: ___ /
Resolved: [ ]</em></td>
</tr>
</tbody>
</table>

Inventory Setup Completed By:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Data Validation By:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

PM Sign-Off:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

*Once all product data is imported, validated, and organized into
collections, this phase gate can be evaluated for advancement to P6 —
Development.*
