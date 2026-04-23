**FANCY LAB**

WEB DEVELOPMENT DEPARTMENT

**PHASE P9**

**LAUNCH**

Standard Operating Procedure & Phase Gate Document

v1.0 \| February 2026 \| Confidential

**PURPOSE & SCOPE**

This SOP defines the standard process for deploying the approved website
to the live production environment. It covers pre-launch verification,
DNS configuration, SSL setup, platform migration (if applicable),
post-deployment verification, and the critical first 24-48 hours of
monitoring after go-live.

**Phase Objective**

Execute a smooth, zero-downtime (or minimal-downtime) website launch
that transitions the site from staging to production, with all technical
configurations verified and a monitoring plan in place for immediate
issue resolution.

**Scope Includes**

> \- Pre-launch checklist verification
>
> \- DNS configuration and propagation
>
> \- SSL certificate installation and verification
>
> \- Platform deployment (theme publish, store password removal, etc.)
>
> \- 301 redirect implementation and verification (if migration)
>
> \- Post-deployment functional verification
>
> \- Analytics and tracking verification
>
> \- Search engine indexing submission
>
> \- 24-48 hour post-launch monitoring
>
> \- Client launch notification

**Scope Excludes**

> \- New development work (route to Change Order)
>
> \- Content changes (must be approved before launch)
>
> \- Ongoing maintenance (covered in P10 - Post-Launch)
>
> \- Marketing campaign launch or social media announcements
>
> \- Email migration or non-website technical changes

**WHO - RACI MATRIX**

|  |  |  |
|:---|:---|:---|
| **Role** | **Person(s)** | **Responsibility** |
| **Responsible** | Narine + Ishkhan | *Performs the work for this phase* |
| **Accountable** | Asya | *Ultimately answerable for completion* |
| **Consulted** | Rinaldo | *Provides input and approves deliverables* |
| **Informed** | Harry + Carlos + Client | *Kept up to date on progress* |

**WHAT - DELIVERABLES**

|  |  |  |
|:---|:---|:---|
| **Deliverable** | **Format / Location** | **Owner** |
| **Pre-Launch Checklist (completed)** | Google Sheets / ClickUp | Asya |
| **DNS Configuration Record** | Google Docs | Narine |
| **SSL Verification Report** | Google Docs | Narine |
| **Post-Launch Verification Report** | Google Sheets | Asya |
| **Redirect Verification Report (if migration)** | Google Sheets | Narine |
| **Launch Notification Email** | Email | Carlos |
| **Post-Launch Monitoring Log** | Google Sheets / ClickUp | Asya |

**WHERE - TOOLS & PLATFORMS**

|  |  |
|:---|:---|
| **Tool** | **Purpose in This Phase** |
| **Shopify / WordPress / CMS Admin** | Platform deployment, store activation |
| **Domain Registrar (GoDaddy, Namecheap, Cloudflare, etc.)** | DNS configuration |
| **Google Search Console** | Sitemap submission, indexing request |
| **Google Analytics** | Verify tracking is live and collecting data |
| **Screaming Frog / Sitebulb** | Redirect verification, broken link check |
| **GTmetrix / PageSpeed Insights** | Post-launch performance verification |
| **ClickUp** | Launch task tracking, monitoring log |
| **Slack** | Real-time launch coordination and monitoring alerts |
| **Email** | Client launch notification |

**HOW - PROCESS STEPS**

> **1. Complete Pre-Launch Checklist**
>
> Before initiating deployment, verify every item on the pre-launch
> checklist: all client-approved content is in place, all forms have
> correct recipients, email notifications configured (order
> confirmations, contact form, etc.), payment gateway in live mode,
> shipping rates configured (if e-commerce), tax settings verified,
> legal pages published (Privacy Policy, Terms, Refund Policy), favicon
> uploaded, 404 page configured, analytics codes installed, social media
> meta tags present, XML sitemap accessible, robots.txt ready for
> production.
>
> **2. Schedule Launch Window**
>
> Coordinate the launch window with the team and client. Prefer
> low-traffic times (early morning or late evening of the client's
> market). Communicate the planned launch time to: development team, PM,
> client. Ensure at least one developer is available for 4 hours
> post-launch for emergency fixes.
>
> **3. Backup Current Site (if migration)**
>
> If replacing an existing website: create a full backup of the current
> site (files + database), document current DNS settings, export current
> analytics data for baseline comparison, save a copy of the current
> sitemap for redirect verification. Store all backups securely in
> Google Drive.
>
> **4. Configure DNS**
>
> Update DNS records to point to the new hosting/platform. Set A
> records, CNAME records, and any required TXT records per platform
> requirements. For Shopify: connect domain via Shopify admin. For
> WordPress: update nameservers or A records. Document all DNS changes
> made. Note that propagation can take up to 48 hours.
>
> **5. Verify SSL Certificate**
>
> Ensure SSL is active and properly configured: HTTPS is enforced on all
> pages, no mixed content warnings, SSL certificate is valid and not
> expiring soon, HTTP automatically redirects to HTTPS. Test across
> multiple browsers.
>
> **6. Deploy to Production**
>
> Execute the platform-specific deployment: Shopify — publish theme,
> remove store password, verify checkout; WordPress — deploy from
> staging to production, update site URL, clear caches; Custom — deploy
> code to production server, run migrations, clear caches. Verify the
> site loads correctly on the production domain.
>
> **7. Implement and Verify Redirects**
>
> If this is a migration: activate all 301 redirects, test every
> redirect using Screaming Frog or manual verification, verify no
> redirect chains or loops exist, spot-check high-traffic pages and key
> landing pages. Document redirect verification results.
>
> **8. Post-Deployment Verification**
>
> Immediately after deployment, verify: homepage loads correctly
> (desktop + mobile), all major pages accessible, navigation working,
> forms submitting correctly, e-commerce flow functional (test order if
> applicable), images loading properly, SSL active on all pages, no
> console errors, analytics tracking firing, third-party integrations
> working.
>
> **9. Submit to Search Engines**
>
> Submit the XML sitemap to Google Search Console. Request indexing of
> the homepage and key pages. If migration: monitor the Coverage report
> for crawl errors. Submit sitemap to Bing Webmaster Tools. Verify that
> robots.txt is not blocking important pages.
>
> **10. Send Client Launch Notification**
>
> Email the client confirming: the site is now live at their domain,
> launch was successful, any known post-launch items being monitored,
> who to contact for urgent issues in the next 48 hours, and the
> timeline for post-launch support. Include a link to the live site.
>
> **11. Monitor for 24-48 Hours**
>
> Active monitoring for the first 24-48 hours post-launch: check site
> uptime every 2-4 hours, monitor analytics for unusual patterns, check
> for error logs or server issues, verify email notifications are being
> received, monitor DNS propagation globally, check social media and
> client channels for reported issues. Log all monitoring checks in the
> monitoring report.

**COMMUNICATION - STAKEHOLDER UPDATES**

|  |  |  |  |
|:---|:---|:---|:---|
| **Type** | **Frequency** | **Audience** | **Channel** |
| Launch Schedule Confirmation | Once (before launch) | Team + Client | Email + Slack |
| Launch Execution Updates | Real-time (during launch) | Team | Slack |
| Post-Deploy Verification Status | Once (immediately after) | PM | Slack |
| Client Launch Notification | Once (after successful launch) | Client | Email |
| Monitoring Updates | Every 4-6 hours (first 48 hours) | PM | Slack |
| Launch Completion Summary | Once (at phase close) | Full Team + Client | Email + Slack |

**ESCALATION - BLOCKED PHASE PROTOCOL**

|  |  |  |  |
|:---|:---|:---|:---|
| **Trigger** | **Timeframe** | **Escalation Action** | **Escalated To** |
| Site down after deployment | Immediately | All hands on deck; assess rollback option | Asya + Narine + Ishkhan + Rinaldo |
| SSL or DNS not propagating | 4 hours post-change | Verify configuration; contact registrar/host support | Narine + Asya |
| Payment processing not working on live site | Immediately | Priority fix; disable checkout if needed until resolved | Asya + Narine + Rinaldo |
| Major redirect failures (migration) | Immediately | Implement emergency redirects; assess SEO impact | Narine + Asya + Rinaldo |
| Client reports critical issue post-launch | Within 2 hours | Triage and fix; keep client updated hourly | Asya + Rinaldo |
| Analytics not tracking | Within 4 hours | Debug and fix; verify via real-time reports | Narine |

**DEPENDENCIES - REQUIRED INPUTS**

|  |  |  |
|:---|:---|:---|
| **Dependency** | **Source Phase** | **Impact if Missing** |
| **Formal Client Sign-Off** | P8 - Client Approval | Cannot launch without written client approval |
| **QA Sign-Off (all Critical/High bugs resolved)** | P7 - Testing & QA | Cannot launch with known critical issues |
| **Domain Access / DNS Credentials** | P1 - Client Onboarding | Cannot configure DNS without registrar access |
| **Payment Gateway Credentials (live mode)** | Client | Cannot activate live payments without production API keys |
| **SSL Certificate** | Hosting Provider / Platform | Cannot go live without valid SSL |

**REVISION LIMITS & SCOPE CONTROL**

Launch Deployment: One launch included; rescheduled launches due to
client delays may incur additional coordination fees

Post-Launch Emergency Fixes: Critical fixes within 48 hours included;
non-critical changes follow post-launch support terms

Redirect Adjustments: Initial redirect implementation included; ongoing
redirect management covered in post-launch support

*Any additional revisions beyond the limits above require a Change Order
approved by the Project Lead and communicated to the client with
associated timeline and cost impact.*

**PHASE GATE - COMPLETION CHECKLIST**

*ALL items below must be completed before the project can advance to
P10 - Post-Launch. The site must be live, verified, and stable before
transitioning to ongoing support.*

|  |  |  |  |
|:---|:---|:---|:---|
| **\#** | **Gate Requirement** | **Status** | **Date** |
| **1** | Pre-launch checklist fully completed |  |  |
| **2** | Launch window communicated to team and client |  |  |
| **3** | Current site backed up (if migration) |  |  |
| **4** | DNS configured and propagating |  |  |
| **5** | SSL certificate active and verified |  |  |
| **6** | Site deployed to production and accessible |  |  |
| **7** | 301 redirects verified (if migration) |  |  |
| **8** | Post-deployment verification completed (all checks pass) |  |  |
| **9** | XML sitemap submitted to Google Search Console |  |  |
| **10** | Analytics and tracking verified on production |  |  |
| **11** | Client launch notification email sent |  |  |
| **12** | 24-48 hour monitoring completed with no critical issues |  |  |
| **13** | Post-Launch Monitoring Log documented |  |  |
| **14** | ClickUp launch tasks marked as complete |  |  |
| **15** | Slack notification posted confirming successful launch |  |  |

**Phase Gate Sign-Off**

|                        |                   |          |
|:-----------------------|:------------------|:---------|
| **Field**              | **Details**       | **Date** |
| **Project Name**       |                   |          |
| **Approved By**        |                   |          |
| **Client Rep**         |                   |          |
| **Next Phase**         | P10 - Post-Launch |          |
| **Notes / Conditions** |                   |          |

**APPENDIX A: PRE-LAUNCH CHECKLIST & GO-LIVE RUNBOOK**

*This runbook provides a step-by-step execution plan for launch day
operations. It includes the pre-launch verification checklist, the
deployment sequence, post-deployment verification, and the 48-hour
monitoring protocol. Each step must be completed in order with
sign-off.*

*Prerequisites: P8 Client Approval — formal sign-off document must be
completed and signed before any launch activities begin.*

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 65%" />
</colgroup>
<tbody>
<tr>
<td colspan="2"><strong>1. LAUNCH SCHEDULE &amp; TEAM</strong></td>
</tr>
<tr>
<td><strong>Planned Launch Date</strong></td>
<td><em>Date: ___ / Day of week: ___ (Recommended:
Tuesday-Thursday)</em></td>
</tr>
<tr>
<td><strong>Launch Window</strong></td>
<td><em>Start time: ___ / End time: ___ / Timezone: ___ / Avoid:
Fridays, weekends, holidays</em></td>
</tr>
<tr>
<td><strong>Launch Commander</strong></td>
<td><em>Name: ___ / Role: ___ / This person coordinates all launch
activities</em></td>
</tr>
<tr>
<td><strong>Dev Team On-Call</strong></td>
<td><em>Primary: ___ / Backup: ___ / Available: ___ to ___ (minimum 4
hours post-launch)</em></td>
</tr>
<tr>
<td><strong>Client Notified</strong></td>
<td><em>Launch time communicated: [ ] / Client available for
verification: [ ] / Emergency contact: ___</em></td>
</tr>
<tr>
<td><strong>Rollback Plan Owner</strong></td>
<td><em>Who decides to rollback if critical issues arise? ___ / Max
decision time: ___ minutes</em></td>
</tr>
<tr>
<td colspan="2"><strong>2. PRE-LAUNCH CHECKLIST (T-24
HOURS)</strong></td>
</tr>
<tr>
<td><strong>Client Sign-Off Confirmed</strong></td>
<td><em>P8 formal sign-off document completed: [ ] / Date: ___</em></td>
</tr>
<tr>
<td><strong>Final Content Freeze Verified</strong></td>
<td><em>No pending content changes: [ ] / All copy finalized: [
]</em></td>
</tr>
<tr>
<td><strong>Payment Gateway → Live Mode</strong></td>
<td><em>Switched from test to live: [ ] / Live test transaction
successful: [ ] / Refunded: [ ]</em></td>
</tr>
<tr>
<td><strong>Shipping Rates Verified</strong></td>
<td><em>All shipping zones correct: [ ] / Rates accurate: [ ] / Free
shipping threshold: [ ]</em></td>
</tr>
<tr>
<td><strong>Tax Settings Verified</strong></td>
<td><em>Tax auto-calculation: [ ] / Tax-exempt products: [ ] /
International tax: [ ]</em></td>
</tr>
<tr>
<td><strong>Email Notifications Configured</strong></td>
<td><em>Order confirmation: [ ] / Shipping confirmation: [ ] / Customer
account: [ ] / Custom emails: [ ]</em></td>
</tr>
<tr>
<td><strong>Legal Pages Published</strong></td>
<td><em>Privacy Policy: [ ] / Terms: [ ] / Return Policy: [ ] / Shipping
Policy: [ ] / Cookie consent: [ ]</em></td>
</tr>
<tr>
<td><strong>Favicon Uploaded</strong></td>
<td><em>Favicon: [ ] / Apple touch icon: [ ] / Correct in all browsers:
[ ]</em></td>
</tr>
<tr>
<td><strong>Social Sharing Preview</strong></td>
<td><em>OG tags correct: [ ] / Twitter cards: [ ] / Tested with:
Facebook Debugger [ ] / Twitter Validator [ ]</em></td>
</tr>
<tr>
<td><strong>Google Analytics Verified</strong></td>
<td><em>GA4 tracking: [ ] / E-commerce enhanced: [ ] / Conversion
tracking: [ ] / Goals configured: [ ]</em></td>
</tr>
<tr>
<td><strong>Backups Created</strong></td>
<td><em>Current site backed up: [ ] / Theme backup: [ ] / Product data
export: [ ] / Customer data: [ ]</em></td>
</tr>
<tr>
<td><strong>DNS TTL Reduced</strong></td>
<td><em>Current TTL: ___ / Reduced to 300s (5 min): [ ] / Change
propagated: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>3. DEPLOYMENT SEQUENCE (LAUNCH
DAY)</strong></td>
</tr>
<tr>
<td><strong>Step 1: Final Staging Check</strong></td>
<td><em>Time: ___ / All pages verified on staging one final time: [ ] /
Assigned: ___</em></td>
</tr>
<tr>
<td><strong>Step 2: Theme Publish</strong></td>
<td><em>Time: ___ / Publish approved theme to live: [ ] / Method:
Shopify Admin / CLI — Assigned: ___</em></td>
</tr>
<tr>
<td><strong>Step 3: DNS Configuration</strong></td>
<td><em>Time: ___ / Update DNS records: [ ] / A record: ___ / CNAME: ___
/ Assigned: ___</em></td>
</tr>
<tr>
<td><strong>Step 4: SSL Verification</strong></td>
<td><em>Time: ___ / HTTPS active: [ ] / Certificate valid: [ ] / No
mixed content warnings: [ ]</em></td>
</tr>
<tr>
<td><strong>Step 5: Domain Connection</strong></td>
<td><em>Time: ___ / Primary domain connected in Shopify: [ ] / Redirect
non-www: [ ] / Assigned: ___</em></td>
</tr>
<tr>
<td><strong>Step 6: 301 Redirects Active</strong></td>
<td><em>Time: ___ / All redirects imported: [ ] / Spot-check top 20
URLs: [ ] / Assigned: ___</em></td>
</tr>
<tr>
<td><strong>Step 7: Robots.txt Updated</strong></td>
<td><em>Time: ___ / Crawling allowed: [ ] / Sitemap reference: [ ] / No
accidental blocks: [ ]</em></td>
</tr>
<tr>
<td><strong>Step 8: Sitemap Submitted</strong></td>
<td><em>Time: ___ / XML sitemap submitted to Google Search Console: [ ]
/ Bing Webmaster: [ ]</em></td>
</tr>
<tr>
<td><strong>Step 9: Cache / CDN Clear</strong></td>
<td><em>Time: ___ / Shopify cache: [ ] / CDN purge: [ ] / Browser
tested: [ ]</em></td>
</tr>
<tr>
<td><strong>Step 10: Password Protection Removed</strong></td>
<td><em>Time: ___ / Store password page disabled: [ ] / Live to public:
[ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>4. POST-DEPLOYMENT VERIFICATION (FIRST 2
HOURS)</strong></td>
</tr>
<tr>
<td><strong>Homepage Loads Correctly</strong></td>
<td><em>Desktop: [ ] / Mobile: [ ] / Time: ___</em></td>
</tr>
<tr>
<td><strong>All Pages Accessible</strong></td>
<td><em>Spot-check 10+ pages: [ ] / No 404s: [ ] / No 500 errors: [
]</em></td>
</tr>
<tr>
<td><strong>Product Pages Work</strong></td>
<td><em>Variant selection: [ ] / Add to cart: [ ] / Images load: [ ] /
Prices correct: [ ]</em></td>
</tr>
<tr>
<td><strong>Full Purchase Flow</strong></td>
<td><em>Live test order placed: [ ] / Confirmation email received: [ ] /
Order appears in admin: [ ] / Refund processed: [ ]</em></td>
</tr>
<tr>
<td><strong>Contact Form Works</strong></td>
<td><em>Submit test: [ ] / Email received at correct address: [ ] /
Confirmation shown: [ ]</em></td>
</tr>
<tr>
<td><strong>Newsletter Signup Works</strong></td>
<td><em>Submit test: [ ] / Added to email list: [ ] / Welcome email
triggers: [ ]</em></td>
</tr>
<tr>
<td><strong>Analytics Receiving Data</strong></td>
<td><em>GA4 real-time showing visitors: [ ] / Events firing: [ ] /
E-commerce tracking: [ ]</em></td>
</tr>
<tr>
<td><strong>Third-Party Integrations</strong></td>
<td><em>All integrations verified live: [ ] / Chat widget: [ ] /
Reviews: [ ] / Social feeds: [ ]</em></td>
</tr>
<tr>
<td><strong>Search Engines</strong></td>
<td><em>Google can crawl: [ ] / No noindex tags: [ ] / Sitemap
accessible: [ ]</em></td>
</tr>
<tr>
<td><strong>Old URLs Redirect</strong></td>
<td><em>Test 10 old URLs: [ ] / All redirect to correct new pages: [ ] /
No chains: [ ]</em></td>
</tr>
<tr>
<td colspan="2"><strong>5. 48-HOUR POST-LAUNCH MONITORING
PROTOCOL</strong></td>
</tr>
<tr>
<td><strong>Hour 1-4: Active Monitoring</strong></td>
<td><em>Team member on site: ___ / Checking: Error logs, analytics,
orders, support inbox</em></td>
</tr>
<tr>
<td><strong>Hour 4-12: Regular Checks</strong></td>
<td><em>Check every 2 hours: [ ] / Error log: [ ] / Order flow: [ ] /
Site speed: [ ]</em></td>
</tr>
<tr>
<td><strong>Hour 12-24: Periodic Checks</strong></td>
<td><em>Check every 4 hours: [ ] / Overnight monitoring: ___ (automated
alerts configured? [ ])</em></td>
</tr>
<tr>
<td><strong>Hour 24-48: Daily Check</strong></td>
<td><em>Full site review: [ ] / Analytics review: [ ] / Error log
review: [ ] / Client feedback: [ ]</em></td>
</tr>
<tr>
<td><strong>Uptime Monitoring</strong></td>
<td><em>Tool: ___ / Alert threshold: ___% / Notification channel: ___ /
Configured: [ ]</em></td>
</tr>
<tr>
<td><strong>Error Rate Threshold</strong></td>
<td><em>Acceptable: &lt; ___% / Alert if exceeds: ___% / Who receives
alert: ___</em></td>
</tr>
<tr>
<td><strong>Issues Found Post-Launch</strong></td>
<td><em>List each issue: ID / Severity / Description / Resolution / Time
to fix: ___</em></td>
</tr>
<tr>
<td colspan="2"><strong>6. LAUNCH COMMUNICATIONS</strong></td>
</tr>
<tr>
<td><strong>Client Launch Notification</strong></td>
<td><em>Sent: [ ] / Time: ___ / Method: Email / Call / Both — Includes:
Live URL, support contact, next steps</em></td>
</tr>
<tr>
<td><strong>Internal Team Notification</strong></td>
<td><em>Slack announcement: [ ] / All team members aware: [ ]</em></td>
</tr>
<tr>
<td><strong>Social Media Announcement (if planned)</strong></td>
<td><em>Client responsible: [ ] / Fancy Lab assists: [ ] / Post
scheduled: [ ] / Platform: ___</em></td>
</tr>
<tr>
<td><strong>Email Marketing Launch (if planned)</strong></td>
<td><em>Launch campaign scheduled: [ ] / Platform: ___ / Send time: ___
/ List: ___</em></td>
</tr>
<tr>
<td><strong>Old Site Decommission Plan</strong></td>
<td><em>Keep old site accessible for ___ days / Redirect all traffic: [
] / Cancel old hosting by: ___</em></td>
</tr>
</tbody>
</table>

Launch Executed By:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Post-Launch Verification By:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

PM Confirmation:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

*Once the 48-hour monitoring period is complete with no critical issues,
this phase gate can be evaluated for advancement to P10 — Post-Launch
Support & Closure.*
