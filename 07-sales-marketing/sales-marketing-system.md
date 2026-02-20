# Part F — Sales, Marketing & Customer Operations

## Awdeer Investments Limited — Business Operating System

| Field | Detail |
|-------|--------|
| Document Title | Sales, Marketing & Customer Operations System |
| Section | Part F |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Sales Manager / Managing Director |
| Classification | Internal — Confidential |

---

## Table of Contents

1. [Overview & Objectives](#1-overview--objectives)
2. [Sales Pipeline & CRM Setup](#2-sales-pipeline--crm-setup)
3. [Customer Segmentation & Pricing Policy](#3-customer-segmentation--pricing-policy)
4. [Quotation-to-Contract Workflow](#4-quotation-to-contract-workflow)
5. [Order Management Workflow](#5-order-management-workflow)
6. [Service Level Standards & Complaint Handling](#6-service-level-standards--complaint-handling)
7. [Marketing System](#7-marketing-system)
8. [Customer Success & Contract Renewals](#8-customer-success--contract-renewals)
9. [KPIs & Performance Dashboard](#9-kpis--performance-dashboard)
10. [Related SOPs & Templates](#10-related-sops--templates)
11. [Appendix — Assumptions & Configuration Notes](#11-appendix--assumptions--configuration-notes)

---

## 1. Overview & Objectives

### 1.1 Purpose

This document defines the end-to-end sales, marketing, and customer operations framework for Awdeer Investments Limited. It covers every stage from lead generation through customer retention, providing standardised processes, controls, and measurement across all business lines (Energy/Fuel, Real Estate, Logistics, Retail, Professional Services).

### 1.2 Design Principles

| Principle | Application in Sales & Marketing |
|-----------|----------------------------------|
| Dual-version | Every process has a Lean (small team) and Controlled (mid-size) version |
| Audit-ready | Every quotation, discount, and contract has an approval trail |
| Segregation of Duties | Sales person does not approve own discounts; pricing approvals are separated |
| Uganda-Ready | Pricing in UGX, VAT-inclusive where applicable, URA e-invoicing compatible |
| ERP-Mapped | Pipeline, quotations, orders, and invoicing map to CRM/ERP modules |
| Scale-Ready | Processes work for single sales lead or multi-branch sales team |

### 1.3 Scope

| In Scope | Out of Scope |
|----------|-------------|
| Lead management & qualification | Product development / R&D |
| Sales pipeline management | Financial accounting (see Part C — Finance) |
| Quotation & contract workflows | Legal contract drafting (see Part I — Legal) |
| Order processing & fulfilment coordination | Warehouse operations (see Part E — Inventory) |
| Customer complaints & service levels | IT systems administration (see Part J — IT) |
| Marketing campaigns & brand management | Board-level strategy (see Part B — Strategy) |
| Customer success & renewals | Internal audit (see Part K — Internal Audit) |

### 1.4 Lean vs Controlled Versions — Summary

| Element | Lean Version (1–10 staff) | Controlled Version (10+ staff) |
|---------|--------------------------|-------------------------------|
| Team | Sales Lead + MD oversight | Sales Manager + Sales Executives + Marketing Officer |
| CRM | Spreadsheet or free CRM (HubSpot Free / Odoo CRM) | Full CRM module in ERP with automation |
| Pipeline reviews | Weekly informal check-in | Weekly structured pipeline review meeting |
| Quotation approval | MD approves all quotes > UGX 5,000,000 | Tiered: Sales Manager up to UGX 20M, MD above |
| Discount authority | MD only | Tiered per Delegation of Authority |
| Marketing | Social media + referrals | Multi-channel with campaign calendar |
| Reporting | Monthly summary to MD | Weekly pipeline report + monthly dashboard |
| Complaint handling | Logged in spreadsheet, MD resolves | Formal ticket system with SLA tracking |

---

## 2. Sales Pipeline & CRM Setup

### 2.1 Pipeline Stages

Every sales opportunity moves through a defined pipeline. Each stage has clear entry criteria and required actions.

| Stage | Entry Criteria | Required Actions | Exit Criteria | Probability % |
|-------|---------------|------------------|---------------|---------------|
| **1. Lead** | New enquiry received (any channel) | Log in CRM, assign owner, capture source | Initial contact made, basic needs identified | 10% |
| **2. Qualified** | Budget confirmed, decision-maker identified, need validated (BANT) | Complete qualification checklist, identify stakeholders | Customer confirms interest in proposal | 25% |
| **3. Proposal** | Customer requests or agrees to receive a formal quotation | Prepare and send quotation, present solution | Customer acknowledges proposal, enters review | 50% |
| **4. Negotiation** | Customer provides feedback on proposal; pricing/terms discussion | Address objections, revise quotation if needed, seek discount approval | Verbal agreement or final rejection | 75% |
| **5. Won** | Customer signs contract or issues purchase order | Issue order confirmation, hand off to operations/fulfilment | Order entered in ERP, fulfilment triggered | 100% |
| **5b. Lost** | Customer declines or goes silent beyond follow-up window | Record loss reason, update CRM, schedule future follow-up | Deal archived with loss analysis | 0% |

### 2.2 CRM Data Model

#### Minimum Fields per Lead/Opportunity

| Field | Description | Required? |
|-------|------------|-----------|
| Lead ID | Auto-generated unique identifier | Yes |
| Company Name | Customer or prospect company name | Yes |
| Contact Name | Primary contact person | Yes |
| Phone / Email | Contact details | Yes |
| Lead Source | Referral, Walk-in, Website, Social Media, Event, Cold Call | Yes |
| Business Line | Energy, Real Estate, Logistics, Retail, Services | Yes |
| Estimated Value (UGX) | Expected deal value | Yes |
| Pipeline Stage | Current stage (Lead through Won/Lost) | Yes |
| Assigned To | Sales person responsible | Yes |
| Next Action | Next step to advance the deal | Yes |
| Next Action Date | When the next action is due | Yes |
| Loss Reason | (If Lost) Price, Competitor, Timing, No Budget, Other | Conditional |
| Notes | Free-text activity log | No |

### 2.3 Lead Source Tracking

| Source Category | Examples | Tracking Method |
|----------------|---------|-----------------|
| Referrals | Existing client referral, partner referral | Referral code / name in CRM |
| Inbound | Website enquiry, phone call, walk-in | Source field in CRM |
| Outbound | Cold call, email outreach, door-to-door | Campaign tag in CRM |
| Events | Trade show, networking event, conference | Event name tag |
| Digital | Social media, Google search, online ad | UTM parameters / channel tag |

### 2.4 Pipeline Management — RACI

| Activity | Sales Executive | Sales Manager | MD | Finance |
|----------|:-:|:-:|:-:|:-:|
| Log new lead | R/A | I | — | — |
| Qualify lead (BANT) | R | A | — | — |
| Weekly pipeline review | R | A | I | — |
| Escalate stalled deals | R | A | C | — |
| Pipeline reporting | I | R/A | I | — |
| Pipeline data integrity audit | C | R | A | — |

> **R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed

### 2.5 Pipeline — Lean Version

- Sales Lead manages all opportunities personally in a spreadsheet or free CRM.
- MD reviews pipeline informally each week (15-minute standup or brief call).
- Sales Lead sends MD a simple weekly email: new leads, deals progressing, deals at risk.
- Pipeline stages remain the same; formality of documentation is lighter.
- Qualification is conversational rather than checklist-driven.

### 2.6 Pipeline — Controlled Version

- Sales Executives own individual pipelines; Sales Manager owns the consolidated view.
- Formal weekly pipeline review meeting (30 minutes) with structured agenda:
  - New leads this week
  - Stage changes
  - Deals at risk (stalled > 14 days without activity)
  - Forecast for current month/quarter
- CRM automation: auto-reminders for overdue next actions, stage aging alerts.
- Monthly pipeline health report to MD with win rate, velocity, and forecast accuracy.

---

## 3. Customer Segmentation & Pricing Policy

### 3.1 Customer Segmentation Framework

| Segment | Criteria | Service Level | Payment Terms | Discount Authority |
|---------|----------|--------------|---------------|-------------------|
| **A — Strategic** | Annual revenue > UGX 200M or long-term contract | Dedicated account manager, priority fulfilment, quarterly business reviews | Net 30 days | Up to 15% (MD approval) |
| **B — Core** | Annual revenue UGX 50M–200M, recurring business | Named contact, standard SLA, semi-annual review | Net 15–30 days | Up to 10% (Sales Manager approval) |
| **C — Standard** | Annual revenue < UGX 50M, transactional | Standard service, general support | Net 15 days or advance payment | Up to 5% (Sales Manager approval) |
| **D — New/Prospect** | No purchase history yet | Standard service during onboarding | Advance payment or proforma | None (list price only) |

### 3.2 Pricing Policy Framework

#### 3.2.1 Pricing Principles

1. **Cost-Plus Baseline**: All prices start from a cost-plus calculation ensuring minimum gross margin targets are met.
2. **Market Reference**: Prices are benchmarked against market rates for competitiveness.
3. **Tiered Volume Discounts**: Standard discount tiers for volume commitments, pre-approved and published.
4. **VAT Compliance**: All external-facing prices must state whether they are inclusive or exclusive of 18% VAT per URA requirements.
5. **Currency**: All domestic pricing in UGX. Foreign currency pricing (USD) only for export or international clients, with exchange rate locked at quotation date.

#### 3.2.2 Standard Pricing Tiers (Template — Customize per Business Line)

| Tier | Volume / Commitment | Discount from List Price | Approval Required |
|------|---------------------|-------------------------|-------------------|
| List Price | Any single order | 0% | None |
| Tier 1 | Quarterly commitment > UGX 20M | 3% | Sales Manager |
| Tier 2 | Quarterly commitment > UGX 50M | 5% | Sales Manager |
| Tier 3 | Annual contract > UGX 200M | 8% | Sales Manager + MD |
| Special / Negotiated | Strategic account, tender, or exceptional case | Up to 15% | MD approval required |

#### 3.2.3 Discount Authorization Rules

| Discount Range | Approver (Lean) | Approver (Controlled) | Documentation Required |
|---------------|----------------|----------------------|----------------------|
| 0% (list price) | None | None | Standard quotation |
| 1–5% | MD | Sales Manager | Quotation + justification note |
| 6–10% | MD | Sales Manager + MD acknowledgement | Pricing Approval Form (SAL-TPL-003) |
| 11–15% | MD | MD formal approval | Pricing Approval Form + business case |
| > 15% | Not permitted | Board/MD special resolution | Full business case + margin analysis |

#### 3.2.4 Pricing Review Cycle

| Activity | Frequency | Owner | Deliverable |
|----------|-----------|-------|------------|
| Cost-base review | Quarterly | Finance Manager | Updated cost sheets |
| Market price benchmarking | Semi-annually | Sales Manager | Competitive pricing report |
| Discount utilization review | Monthly | Sales Manager | Discount analysis report |
| Price list update | Annually (or as needed) | Sales Manager + MD | Published price list |

---

## 4. Quotation-to-Contract Workflow

### 4.1 Process Overview

```
Customer Enquiry → Qualify Need → Prepare Quotation → Internal Review/Approval
    → Send to Customer → Customer Negotiation → Final Quotation
    → Contract/PO → Order Entry → Handoff to Fulfilment
```

### 4.2 Detailed Workflow Steps

| Step | Action | Responsible | Approval | SLA |
|------|--------|-------------|----------|-----|
| 1 | Receive and log customer enquiry in CRM | Sales Executive | — | Same day |
| 2 | Qualify customer need and confirm specifications | Sales Executive | — | 1 business day |
| 3 | Check pricing: standard list or custom pricing needed? | Sales Executive | — | — |
| 4a | Standard pricing: prepare quotation using template (SAL-TPL-002) | Sales Executive | — | 1 business day |
| 4b | Custom/discounted pricing: complete Pricing Approval Form (SAL-TPL-003) | Sales Executive | Sales Manager / MD | 2 business days |
| 5 | Internal review of quotation for accuracy (pricing, VAT, terms) | Sales Manager | — | 1 business day |
| 6 | Send quotation to customer with cover letter/email | Sales Executive | — | Same day after approval |
| 7 | Follow up with customer per agreed timeline | Sales Executive | — | Per quotation validity |
| 8 | Negotiate terms if customer requests changes | Sales Executive | Sales Manager for revised terms | 2 business days |
| 9 | Prepare final quotation and send for customer acceptance | Sales Executive | Sales Manager | 1 business day |
| 10 | Receive signed contract/PO from customer | Sales Executive | — | — |
| 11 | Enter order in ERP/order system | Sales Executive | Sales Manager confirms | Same day |
| 12 | Handoff to operations/fulfilment with order pack | Sales Executive | — | Same day |

### 4.3 Quotation-to-Contract — RACI

| Activity | Sales Executive | Sales Manager | MD | Finance | Operations |
|----------|:-:|:-:|:-:|:-:|:-:|
| Prepare quotation | R | A | — | C (for costing) | C (for availability) |
| Approve standard pricing quotation | — | R/A | I | — | — |
| Approve discounted quotation | — | R | A (if > threshold) | C | — |
| Send quotation to customer | R | A | — | — | — |
| Negotiate terms | R | A | C (for major deals) | — | — |
| Review and sign contract | — | R | A | C | I |
| Enter order | R | A | — | I | I |

### 4.4 Quotation-to-Contract — Lean Version

- Sales Lead prepares quotations using the standard template.
- MD reviews and approves all quotations above UGX 5,000,000.
- Quotations below UGX 5,000,000 can be sent by Sales Lead with standard pricing.
- Contracts above UGX 20,000,000 require MD signature.
- Simple email trail serves as approval record.
- Quotation validity: 14 days standard.

### 4.5 Quotation-to-Contract — Controlled Version

- Sales Executives prepare quotations; Sales Manager reviews all before sending.
- Tiered approval per Delegation of Authority.
- All quotations numbered sequentially: `AWD-QTN-YYYY-NNNN`.
- Quotations above UGX 50,000,000 require Finance review for margin validation.
- Contract execution follows Legal review for contracts above UGX 100,000,000.
- All quotation documents stored in CRM/document management system.
- Quotation validity: 30 days standard, extendable with Sales Manager approval.
- Automated CRM reminders for quotation follow-up and expiry.

### 4.6 Controls & Safeguards

| Control | Purpose | How |
|---------|---------|-----|
| Sequential quotation numbering | Prevent gaps, ensure traceability | Auto-generated by CRM/ERP |
| Pricing approval form | Prevent unauthorized discounts | Form required for any discount > 0% |
| Quotation expiry | Prevent stale pricing exposure | 14/30-day validity enforced |
| Margin floor check | Ensure profitability | Finance validates gross margin before approval |
| Segregation: prepare vs approve | Prevent self-approval | Different person prepares and approves |
| Contract review | Ensure legal soundness | Legal reviews high-value contracts |

---

## 5. Order Management Workflow

### 5.1 Process Overview

```
Signed Contract/PO Received → Order Entry → Credit Check → Order Confirmation
    → Fulfilment Coordination → Delivery/Service Execution
    → Delivery Confirmation → Invoicing → Payment Collection → Order Closure
```

### 5.2 Detailed Workflow Steps

| Step | Action | Responsible | Approval | SLA |
|------|--------|-------------|----------|-----|
| 1 | Receive signed contract, PO, or confirmed order | Sales Executive | — | — |
| 2 | Verify order details match approved quotation | Sales Executive | Sales Manager | Same day |
| 3 | Perform credit check (new customers or large orders) | Finance / AR Officer | Finance Manager | 1 business day |
| 4 | Enter order in ERP/order system | Sales Executive | — | Same day |
| 5 | Generate and send Order Confirmation to customer | Sales Executive | — | Same day |
| 6 | Coordinate fulfilment with Operations/Warehouse | Sales Executive | Operations Manager | Per delivery SLA |
| 7 | Track fulfilment progress and update customer | Sales Executive | — | Ongoing |
| 8 | Confirm delivery / service completion with customer sign-off | Operations / Sales | — | At delivery |
| 9 | Trigger invoice generation (handoff to Finance) | Sales Executive | Finance Manager | Within 2 business days of delivery |
| 10 | Monitor payment collection, follow up on overdue | AR Officer / Sales | Finance Manager | Per payment terms |
| 11 | Close order in system once fully paid and delivered | Sales Executive | Sales Manager | Within 5 business days of payment |

### 5.3 Order Management — RACI

| Activity | Sales Executive | Sales Manager | Operations | Finance | MD |
|----------|:-:|:-:|:-:|:-:|:-:|
| Order entry | R | A | I | I | — |
| Credit check | I | I | — | R/A | C (large orders) |
| Order confirmation to customer | R | A | I | — | — |
| Fulfilment coordination | R | I | R/A | — | — |
| Delivery confirmation | I | I | R/A | — | — |
| Invoice generation | I | — | — | R/A | — |
| Payment follow-up | C | I | — | R/A | I (overdue) |
| Order closure | R | A | C | C | — |

### 5.4 Order Management — Lean Version

- Sales Lead enters orders, coordinates with Operations Manager directly.
- Credit checks are informal: MD decides on credit terms for new customers.
- Delivery confirmation via WhatsApp photo/message or email, then filed.
- Invoice request sent to Finance Manager by email.
- Simple order tracker spreadsheet.

### 5.5 Order Management — Controlled Version

- Full ERP order workflow: order entry triggers automatic stock reservation and fulfilment workflow.
- Formal credit check process with credit limit per customer maintained in ERP.
- Automated order confirmation emails from ERP.
- Delivery note generated from ERP, signed by customer, scanned and attached.
- Invoice auto-generated from confirmed delivery in ERP.
- Aging report automatically flags overdue payments for follow-up.
- Monthly order fulfilment report: fill rate, on-time delivery, order-to-cash cycle time.

### 5.6 Controls & Safeguards

| Control | Purpose | How |
|---------|---------|-----|
| Order vs quotation match | Ensure order reflects agreed terms | Sales Manager verifies before entry |
| Credit check | Prevent bad debt | Finance approves credit for new/large customers |
| Delivery confirmation sign-off | Proof of fulfilment | Customer signs delivery note or acknowledges receipt |
| Invoice-to-order match | Billing accuracy | Finance matches invoice to order and delivery note |
| Payment monitoring | Cash collection | AR aging report reviewed weekly |
| Segregation: sell vs collect | Prevent fraud | Sales does not handle cash; Finance collects |

---

## 6. Service Level Standards & Complaint Handling

### 6.1 Service Level Standards

| Service Metric | Target (Standard) | Target (Strategic Accounts) | Measurement Method |
|---------------|-------------------|---------------------------|-------------------|
| Quotation response time | Within 2 business days of enquiry | Within 1 business day | CRM timestamp: enquiry vs quotation sent |
| Order confirmation | Same day as order entry | Same day as order entry | ERP timestamp |
| Delivery / fulfilment | Per agreed delivery schedule (±1 day) | Per agreed schedule (no tolerance) | Delivery note date vs committed date |
| Invoice accuracy | 99% first-time accuracy | 99% first-time accuracy | Credit note ratio |
| Complaint acknowledgement | Within 1 business day | Within 4 hours | Complaint log timestamp |
| Complaint resolution | Within 5 business days | Within 3 business days | Complaint log resolution date |
| Customer query response | Within 1 business day | Within 4 hours | Email/CRM response time |
| Account review meeting | Annually | Quarterly | Calendar schedule |

### 6.2 Complaint Handling Process

#### 6.2.1 Complaint Categories

| Category | Examples | Severity | Target Resolution |
|----------|---------|----------|-------------------|
| **Critical** | Product/service failure causing financial loss, safety issue, contract breach | High | 24 hours initial response, 3 business days resolution |
| **Major** | Significant quality issue, repeated delivery delays, billing errors > UGX 1M | Medium-High | 1 business day acknowledgement, 5 business days resolution |
| **Minor** | Small billing discrepancy, minor delay, communication gap | Medium | 1 business day acknowledgement, 7 business days resolution |
| **Feedback** | Suggestion for improvement, general comment | Low | Acknowledge within 2 business days, log for review |

#### 6.2.2 Complaint Handling Workflow

| Step | Action | Responsible | SLA |
|------|--------|-------------|-----|
| 1 | Receive complaint (phone, email, in-person, form) | Any staff member | Immediate logging |
| 2 | Log complaint in complaint register using form (SAL-TPL-005) | Receiving staff / Sales Executive | Same day |
| 3 | Assign severity and route to complaint owner | Sales Manager | Within 4 hours |
| 4 | Acknowledge receipt to customer | Complaint Owner | Per severity SLA |
| 5 | Investigate root cause | Complaint Owner + relevant department | 1–3 business days |
| 6 | Propose resolution to customer | Complaint Owner | Per severity SLA |
| 7 | Implement resolution and confirm with customer | Complaint Owner | Per severity SLA |
| 8 | Record resolution in complaint register | Complaint Owner | Same day as resolution |
| 9 | Follow up with customer to confirm satisfaction | Sales Manager / Complaint Owner | 3 business days after resolution |
| 10 | Review complaint for systemic issues / corrective action | Sales Manager + MD (monthly review) | Monthly |

#### 6.2.3 Complaint Handling — RACI

| Activity | Receiving Staff | Sales Executive | Sales Manager | MD | Operations/Finance |
|----------|:-:|:-:|:-:|:-:|:-:|
| Log complaint | R | R | A | I (critical) | — |
| Assign severity | — | C | R/A | I (critical) | — |
| Investigate | — | R | A | C (critical) | R (if their area) |
| Resolve | — | R | A | A (critical) | R (if their area) |
| Follow-up | — | R | A | I | — |
| Monthly review | — | I | R | A | C |

#### 6.2.4 Escalation Matrix

| Condition | Escalation Level | Action |
|-----------|-----------------|--------|
| Complaint not acknowledged within SLA | Sales Manager | Sales Manager contacts customer directly |
| Complaint not resolved within SLA | MD | MD intervenes, resources assigned |
| Customer threatens legal action | MD + Legal | Immediate legal consultation |
| Complaint reveals systemic issue | MD + affected department heads | Root cause analysis and corrective action plan |
| Customer requests compensation > UGX 5M | MD | MD approval for any financial remedy |

### 6.3 Lean Version — Service Levels & Complaints

- Sales Lead handles all complaints directly, escalating to MD for critical issues.
- Complaint log maintained in spreadsheet with columns: Date, Customer, Issue, Severity, Owner, Status, Resolution, Date Closed.
- MD reviews complaint log monthly.
- Service level targets remain the same; tracking is manual.

### 6.4 Controlled Version — Service Levels & Complaints

- Formal complaint ticketing system (CRM module or dedicated tool).
- Auto-generated acknowledgement emails.
- SLA countdown timers with escalation triggers.
- Monthly complaint analysis report: volume, categories, resolution time, repeat issues.
- Quarterly customer satisfaction survey for Segment A and B customers.
- Complaint data feeds into continuous improvement / internal audit programs.

---

## 7. Marketing System

### 7.1 Brand Kit Essentials

| Element | Specification | Owner | Status |
|---------|--------------|-------|--------|
| Logo | Primary logo (colour, B&W, reverse), minimum size rules | MD / Marketing | REQUIRED — establish if not existing |
| Colour palette | Primary colours (2–3), secondary colours (2–3), with hex/RGB codes | MD / Marketing | REQUIRED |
| Typography | Primary font (headings), secondary font (body), approved alternatives | MD / Marketing | REQUIRED |
| Tagline / Slogan | 1-line company positioning statement | MD | REQUIRED |
| Business card template | Standard layout for all staff | Marketing / Admin | REQUIRED |
| Letterhead template | Official company letterhead with registration details | Marketing / Admin | REQUIRED |
| Email signature template | Standard email signature block for all staff | Marketing / IT | REQUIRED |
| Presentation template | PowerPoint/Google Slides template with branding | Marketing | RECOMMENDED |
| Social media profile assets | Profile picture, cover images, sized per platform | Marketing | REQUIRED |

### 7.2 Messaging Framework

| Component | Content | Use |
|-----------|---------|-----|
| **Vision Statement** | [To be defined by MD/Board] | Annual reports, website, corporate communications |
| **Mission Statement** | [To be defined by MD/Board] | Internal documents, proposals, marketing materials |
| **Value Proposition** | What Awdeer uniquely offers to customers across business lines | Sales pitches, website homepage, proposals |
| **Elevator Pitch (30 sec)** | 2–3 sentence company introduction for networking | Events, cold outreach, social media bios |
| **Key Messages per Business Line** | 3–5 bullet points per line: Energy, Real Estate, Logistics, Retail, Services | Targeted marketing, proposals, segment-specific campaigns |
| **Proof Points** | Client testimonials, case studies, certifications, years in business | Proposals, website, social media |

### 7.3 Marketing Channels

| Channel | Purpose | Cost Level | Owner | Frequency |
|---------|---------|-----------|-------|-----------|
| **Website** | Digital storefront, credibility, lead generation | Medium (one-time + hosting) | Marketing / IT | Ongoing updates |
| **Google Business Profile** | Local search visibility, reviews | Free | Marketing | Weekly updates |
| **LinkedIn** | B2B networking, thought leadership, recruitment | Free / Low (ads optional) | Marketing / MD | 2–3 posts/week |
| **Facebook** | Brand awareness, community engagement (B2C lines) | Free / Low (ads optional) | Marketing | 3–5 posts/week |
| **WhatsApp Business** | Direct customer communication, order updates | Free | Sales | As needed |
| **Email Marketing** | Newsletters, promotions, customer nurture | Low (Mailchimp free tier or similar) | Marketing | Monthly newsletter |
| **Referral Program** | Customer and partner referrals | Low (incentive cost) | Sales | Ongoing |
| **Events & Trade Shows** | Network, generate leads, build brand | Medium–High | Sales / MD | Per opportunity |
| **Print (cards, flyers, signage)** | Physical presence, local marketing | Low–Medium | Marketing | As needed |

### 7.4 Campaign Management Process

| Step | Action | Responsible | Approval | SLA |
|------|--------|-------------|----------|-----|
| 1 | Identify campaign objective and target audience | Sales Manager / Marketing | MD | — |
| 2 | Define campaign: message, channels, budget, timeline | Marketing | Sales Manager | 5 business days |
| 3 | Budget approval | Sales Manager | MD (if > UGX 2,000,000) | 2 business days |
| 4 | Create campaign content (copy, visuals, landing pages) | Marketing | Sales Manager | Per timeline |
| 5 | Review and approve content for brand consistency | Sales Manager | MD (for public-facing) | 2 business days |
| 6 | Launch campaign | Marketing | — | Per timeline |
| 7 | Monitor campaign performance (leads generated, engagement) | Marketing | — | Daily during campaign |
| 8 | Capture and route leads generated to sales pipeline | Marketing → Sales | — | Same day |
| 9 | Campaign close: compile results report | Marketing | — | 5 business days after close |
| 10 | Post-campaign review: ROI analysis, lessons learned | Marketing + Sales | MD | 10 business days after close |

### 7.5 Campaign Management — RACI

| Activity | Marketing Officer | Sales Manager | Sales Executive | MD | Finance |
|----------|:-:|:-:|:-:|:-:|:-:|
| Campaign planning | R | A | C | I | — |
| Budget approval | — | R | — | A | C |
| Content creation | R | A | C | — | — |
| Content approval | — | R | — | A (public-facing) | — |
| Campaign execution | R | I | I | — | — |
| Lead handoff to sales | R | A | R (receives leads) | — | — |
| Results reporting | R | A | I | I | — |
| ROI analysis | R | A | — | I | C |

### 7.6 Marketing — Lean Version

- Sales Lead handles marketing with MD guidance.
- Focus on free/low-cost channels: Google Business, social media, referrals, WhatsApp.
- Simple campaign tracker: Google Sheet with campaign name, channel, spend, leads generated.
- MD approves all marketing spend.
- Content: simple posts, customer testimonials, project photos.
- Monthly marketing review as part of MD check-in with Sales Lead.

### 7.7 Marketing — Controlled Version

- Dedicated Marketing Officer or outsourced marketing support.
- Annual marketing calendar with planned campaigns per quarter.
- Campaign briefs for each campaign with objectives, budget, KPIs.
- Content calendar for social media (weekly posts planned in advance).
- Lead scoring: Marketing Qualified Lead (MQL) criteria defined before handoff to sales.
- Monthly marketing performance dashboard: impressions, engagement, leads, cost per lead.
- Brand guideline enforcement: all materials reviewed before publication.
- A/B testing on digital campaigns where possible.

### 7.8 Annual Marketing Budget Framework

| Category | Lean Budget (Annual, UGX) | Controlled Budget (Annual, UGX) |
|----------|--------------------------|-------------------------------|
| Website hosting & maintenance | 500,000–1,500,000 | 2,000,000–5,000,000 |
| Social media advertising | 1,000,000–3,000,000 | 5,000,000–15,000,000 |
| Print materials (cards, flyers, signage) | 500,000–2,000,000 | 2,000,000–5,000,000 |
| Events & trade shows | 1,000,000–5,000,000 | 5,000,000–20,000,000 |
| Email marketing tools | Free–500,000 | 1,000,000–3,000,000 |
| Content creation (photos, videos) | 500,000–2,000,000 | 3,000,000–10,000,000 |
| Referral program incentives | 1,000,000–3,000,000 | 3,000,000–10,000,000 |
| **Total Estimated Range** | **4,500,000–17,000,000** | **21,000,000–68,000,000** |

> Note: Budgets are indicative and must be approved annually by MD as part of the budgeting cycle.

---

## 8. Customer Success & Contract Renewals

### 8.1 Customer Success Framework

The goal of customer success is to maximise customer lifetime value through retention, upselling, and advocacy.

| Activity | Frequency | Owner | Deliverable |
|----------|-----------|-------|------------|
| Onboarding new customer | At contract start | Sales Executive | Welcome pack, key contacts, SLA summary |
| Relationship check-in | Monthly (Segment A), Quarterly (Segment B), Annually (Segment C) | Account Owner | Meeting notes, action items |
| Service delivery review | Per delivery/milestone | Operations + Sales | Delivery report, customer feedback |
| Customer satisfaction survey | Annually (all), Quarterly (Segment A) | Sales Manager | NPS/CSAT score, feedback summary |
| Contract renewal outreach | 90 days before expiry | Sales Executive | Renewal proposal |
| Upsell/cross-sell identification | Ongoing, reviewed quarterly | Sales Executive | Opportunity logged in CRM |
| Win-back outreach (lost customers) | 6 months after loss | Sales Executive | Re-engagement contact |

### 8.2 Contract Renewal Process

| Step | Action | Responsible | SLA |
|------|--------|-------------|-----|
| 1 | CRM alert: contract expiry in 90 days | System (auto) | Automatic |
| 2 | Review account performance: revenue, profitability, complaints | Sales Executive + Finance | Within 5 business days of alert |
| 3 | Prepare renewal proposal (updated pricing if applicable) | Sales Executive | 15 business days before expiry |
| 4 | Present renewal proposal to customer | Sales Executive | 10 business days before expiry |
| 5 | Negotiate terms if needed | Sales Executive | Before expiry |
| 6 | Obtain signed renewal / new contract | Sales Executive | Before or at expiry |
| 7 | Update CRM with new contract dates and terms | Sales Executive | Same day as signing |
| 8 | If customer does not renew: log reason, initiate win-back plan | Sales Executive | Within 5 business days |

### 8.3 Customer Success — RACI

| Activity | Sales Executive | Sales Manager | MD | Finance | Operations |
|----------|:-:|:-:|:-:|:-:|:-:|
| Customer onboarding | R | A | — | I | C |
| Relationship check-ins | R | A | C (Segment A) | — | — |
| Satisfaction surveys | C | R/A | I | — | — |
| Contract renewal proposal | R | A | A (Segment A) | C (pricing) | — |
| Upsell identification | R | A | I | — | C |
| Win-back outreach | R | A | C | — | — |

### 8.4 Customer Success — Lean Version

- Sales Lead manages all customer relationships.
- Renewal tracking via spreadsheet with contract end dates and 90-day reminder.
- Annual informal check-in with top 10 customers.
- Simple feedback collected via phone call or WhatsApp after key deliveries.

### 8.5 Customer Success — Controlled Version

- CRM-driven renewal alerts and customer health scoring.
- Formal customer onboarding checklist and welcome pack.
- Quarterly business reviews for Segment A customers (formal presentation).
- Annual NPS survey deployed via email/online form.
- Customer success dashboard: retention rate, NPS, revenue per customer trend.
- Formal win-back campaign for churned customers (email + call sequence).
- Customer advisory board (Segment A customers) meeting annually.

---

## 9. KPIs & Performance Dashboard

### 9.1 Sales & Marketing KPIs

| KPI | Definition | Target | Frequency | Owner |
|-----|-----------|--------|-----------|-------|
| **Lead Conversion Rate** | Leads converted to Won / Total Leads | > 20% | Monthly | Sales Manager |
| **Average Deal Size** | Total revenue from Won deals / Number of Won deals | Track trend (increase YoY) | Monthly | Sales Manager |
| **Sales Cycle Length** | Average days from Lead to Won | < 45 days (varies by business line) | Monthly | Sales Manager |
| **Customer Acquisition Cost (CAC)** | Total sales & marketing spend / Number of new customers acquired | Decreasing trend | Quarterly | Sales Manager + Finance |
| **Net Promoter Score (NPS)** | % Promoters (9–10) minus % Detractors (0–6) on 0–10 scale | > 40 | Quarterly / Annually | Sales Manager |
| **Customer Churn Rate** | Customers lost in period / Total customers at start of period | < 10% annually | Quarterly | Sales Manager |
| **Revenue Retention Rate** | Revenue from existing customers this period / Revenue from same customers prior period | > 90% | Quarterly | Sales Manager + Finance |
| **Quotation Win Rate** | Quotations converted to orders / Total quotations sent | > 40% | Monthly | Sales Manager |
| **Average Quotation Response Time** | Average days from enquiry to quotation sent | < 2 days | Monthly | Sales Manager |
| **Complaint Resolution Rate** | Complaints resolved within SLA / Total complaints | > 90% | Monthly | Sales Manager |
| **Marketing Cost per Lead** | Total marketing spend / Total leads generated from marketing | Decreasing trend | Monthly | Marketing |
| **Customer Satisfaction (CSAT)** | Average satisfaction score from feedback surveys (1–5 scale) | > 4.0 | Quarterly | Sales Manager |
| **Pipeline Value** | Total value of all active opportunities in pipeline | Track trend (increasing) | Weekly | Sales Manager |
| **Pipeline Coverage Ratio** | Total pipeline value / Revenue target | > 3x current quarter target | Monthly | Sales Manager |
| **On-Time Delivery Rate** | Orders delivered on time / Total orders | > 95% | Monthly | Operations + Sales |

### 9.2 Dashboard — Lean Version

Monthly summary report (1 page) prepared by Sales Lead for MD:

| Section | Content |
|---------|---------|
| Pipeline Summary | Number of leads, qualified, proposals, won, lost this month |
| Revenue | Sales revenue this month vs target |
| Key Wins | Top 3 deals closed this month |
| Key Risks | Deals at risk, customer complaints, overdue payments |
| Marketing | Activities this month, leads generated |
| Next Month Focus | Top priorities and targets |

### 9.3 Dashboard — Controlled Version

Weekly and monthly reports generated from CRM/ERP:

**Weekly Pipeline Report (Sales Manager to MD):**
- New leads and source breakdown
- Stage movement and pipeline velocity
- Deals closing this month (forecast)
- Stalled deals requiring action

**Monthly Sales & Marketing Dashboard:**
- All KPIs from table above with trend arrows (improving/stable/declining)
- Revenue vs target by business line
- Pipeline funnel chart
- Win/loss analysis
- Customer churn/retention metrics
- Marketing campaign performance
- Complaint summary
- Top 10 customers by revenue

**Quarterly Business Review Input:**
- Full KPI review with 3-month trends
- Customer segmentation revenue analysis
- Marketing ROI analysis
- Customer satisfaction / NPS results
- Sales team performance (individual, if applicable)
- Forecast accuracy review
- Recommendations for next quarter

---

## 10. Related SOPs & Templates

### 10.1 Standard Operating Procedures

| SOP ID | Title | Location |
|--------|-------|----------|
| SAL-PIP-001 | Sales Pipeline Management | `07-sales-marketing/sops/SAL-PIP-001-sales-pipeline.md` |
| SAL-QTC-001 | Quotation to Contract | `07-sales-marketing/sops/SAL-QTC-001-quotation-to-contract.md` |
| SAL-ORD-001 | Order Management | `07-sales-marketing/sops/SAL-ORD-001-order-management.md` |
| SAL-CMP-001 | Customer Complaint Handling | `07-sales-marketing/sops/SAL-CMP-001-complaint-handling.md` |
| SAL-MKT-001 | Marketing Campaign Management | `07-sales-marketing/sops/SAL-MKT-001-marketing-campaigns.md` |

### 10.2 Templates & Forms

| Template ID | Title | Location |
|-------------|-------|----------|
| SAL-TPL-001 | Lead Tracking Sheet | `07-sales-marketing/templates/SAL-TPL-001-lead-sheet.md` |
| SAL-TPL-002 | Quotation Template | `07-sales-marketing/templates/SAL-TPL-002-quotation-template.md` |
| SAL-TPL-003 | Pricing Approval / Discount Authorization Form | `07-sales-marketing/templates/SAL-TPL-003-pricing-approval-form.md` |
| SAL-TPL-004 | Sales Contract Outline | `07-sales-marketing/templates/SAL-TPL-004-sales-contract-outline.md` |
| SAL-TPL-005 | Customer Complaint Form | `07-sales-marketing/templates/SAL-TPL-005-customer-complaint-form.md` |
| SAL-TPL-006 | Customer Feedback Survey | `07-sales-marketing/templates/SAL-TPL-006-customer-feedback-survey.md` |

---

## 11. Appendix — Assumptions & Configuration Notes

### 11.1 Assumptions

| # | Assumption | Default Used | Action Required |
|---|-----------|-------------|-----------------|
| 1 | Business lines | Energy, Real Estate, Logistics, Retail, Services | Confirm active lines |
| 2 | Primary currency | UGX with 18% VAT standard rate | Confirm VAT registration status |
| 3 | CRM platform | Odoo CRM (ERP module) for Controlled; Spreadsheet/Free CRM for Lean | Confirm platform choice |
| 4 | Sales team size | 1 Sales Lead (Lean); 1 Sales Manager + 2–4 Sales Executives (Controlled) | Confirm current headcount |
| 5 | Customer base size | <100 active customers (Lean); 100–500 (Controlled) | Confirm actual count |
| 6 | Quotation validity period | 14 days (Lean), 30 days (Controlled) | Confirm preferred terms |
| 7 | Standard payment terms | Net 15–30 days depending on segment | Confirm terms policy |
| 8 | Marketing budget | Per framework in Section 7.8 | Confirm annual budget |
| 9 | Discount authority thresholds | Per Section 3.2.3 | Confirm with MD |
| 10 | Customer segmentation thresholds | Per Section 3.1 (UGX values) | Confirm revenue tiers |

### 11.2 ERP Module Mapping

| Process | ERP Module | Key Transactions |
|---------|-----------|-----------------|
| Lead management | CRM — Leads | Lead creation, qualification, assignment |
| Pipeline management | CRM — Opportunities | Stage tracking, probability, expected revenue |
| Quotation | CRM / Sales — Quotations | Quotation creation, approval, sending |
| Order management | Sales — Sales Orders | Order entry, confirmation, fulfilment tracking |
| Invoicing | Accounting — Customer Invoices | Invoice generation, payment application |
| Customer master | CRM — Contacts | Customer data, segmentation, credit terms |
| Complaint tracking | Helpdesk / CRM — Tickets | Ticket creation, assignment, resolution |
| Marketing campaigns | CRM — Campaigns | Campaign tracking, lead source attribution |
| Reporting | CRM / Sales — Dashboards | Pipeline, revenue, KPIs |

### 11.3 Integration Points with Other Sections

| This Section | Integrates With | Integration Point |
|-------------|----------------|-------------------|
| Sales Pipeline | Strategy (Part B) | Revenue targets from OKRs drive pipeline targets |
| Quotation/Pricing | Finance (Part C) | Cost data from finance feeds pricing; quotations trigger invoicing |
| Order Management | Inventory (Part E) | Orders trigger stock allocation and dispatch |
| Order Management | Procurement (Part D) | Make-to-order items trigger purchase requisitions |
| Complaint Handling | Internal Audit (Part K) | Complaint trends feed audit risk assessment |
| Contracts | Legal (Part I) | High-value contracts require legal review |
| Customer Data | IT (Part J) | CRM data protection, access controls, backups |
| Marketing | Finance (Part C) | Marketing budget managed per finance controls |
| Customer Success | Strategy (Part B) | NPS and retention metrics feed QBR |

---

*Version 1.0 — February 2026*
*Awdeer Investments Limited — Business Operating System*
