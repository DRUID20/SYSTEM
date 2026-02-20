# Part D — Procurement & Vendor Management System

## Awdeer Investments Limited — Uganda

---

## Table of Contents

1. [Overview](#1-overview)
2. [Procurement Policy](#2-procurement-policy)
3. [Procurement Thresholds & Approval Matrix](#3-procurement-thresholds--approval-matrix)
4. [Purchase Requisition to PO to Payment Workflow](#4-purchase-requisition-to-po-to-payment-workflow)
5. [Goods Receipt & Service Acceptance](#5-goods-receipt--service-acceptance)
6. [Supplier Lifecycle Management](#6-supplier-lifecycle-management)
7. [Contracting & SLA Management](#7-contracting--sla-management)
8. [Procurement Fraud Controls](#8-procurement-fraud-controls)
9. [SOPs Index](#9-sops-index)
10. [Templates Index](#10-templates-index)
11. [Key Performance Indicators](#11-key-performance-indicators)
12. [ERP Module Mapping](#12-erp-module-mapping)

---

## 1. Overview

### 1.1 Purpose

This section establishes the end-to-end procurement and vendor management system for Awdeer Investments Limited. It covers every stage from identifying a need through to payment, supplier management, and performance review. The system is designed to ensure value for money, transparency, segregation of duties, and fraud prevention while remaining practical for the company's current scale.

### 1.2 Scope

This procurement system applies to:

- All purchases of goods, services, and works across all business lines
- All departments and branches of Awdeer Investments Limited
- Capital expenditure (CAPEX) and operating expenditure (OPEX) purchases
- Both local and international procurement
- Consultant and professional service engagements
- All supplier and vendor relationships

### 1.3 Excluded from Scope

| Item | Governed By |
|------|-------------|
| Petty cash purchases below UGX 100,000 | Finance — Petty Cash Policy (FIN-PC-001) |
| Employee expense reimbursements | Finance — Expense Policy (FIN-EXP-001) |
| Payroll and statutory payments | HR — Payroll (HR-PAY-001) |
| Tax remittances | Finance — Tax Compliance (FIN-TAX-001) |
| Inter-company transfers | Finance — Treasury (FIN-TRS-001) |

### 1.4 Design Principles

| Principle | Application in Procurement |
|-----------|---------------------------|
| Segregation of Duties | Requester ≠ Approver ≠ Buyer ≠ Receiver ≠ Payer |
| Value for Money | Competitive sourcing at every threshold level |
| Transparency | Documented evaluations, audit trail on every decision |
| Accountability | Named approvers at every stage with delegation limits |
| Compliance | Aligned with URA tax requirements (WHT, VAT) and Uganda PPDA principles |
| Fraud Prevention | Split-purchase detection, conflict of interest declarations, bid-rigging controls |

### 1.5 Key Roles

| Role | Abbreviation | Lean Version | Controlled Version |
|------|-------------|-------------|-------------------|
| Managing Director | MD | Final approver (above UGX 5M) | Final approver (above UGX 50M) |
| Operations Manager | OM | Procurement lead, buyer | Oversees procurement function |
| Procurement Manager | PM | N/A (OM handles) | Manages day-to-day procurement |
| Procurement Officer | PO-role | N/A | Processes PRs, issues RFQs/POs |
| Finance Manager | FM | Budget check, payment processing | Budget check, payment approval |
| Accounts Payable Officer | APO | N/A (FM handles) | Processes supplier invoices/payments |
| Department Heads | DH | Initiators and first-level approvers | Initiators and first-level approvers |
| Stores/Inventory Officer | SIO | Goods receipt (OM handles) | Receives goods, issues GRNs |
| Board of Directors | Board | N/A | Approves above UGX 200M |

---

## 2. Procurement Policy

### 2.1 Policy Statement

Awdeer Investments Limited is committed to procuring goods, services, and works in a manner that achieves best value for money, maintains the highest ethical standards, ensures fair competition among suppliers, and complies with all applicable laws and regulations of Uganda.

### 2.2 Core Rules

| # | Rule | Detail |
|---|------|--------|
| 1 | Budget availability | No purchase may be initiated without confirmed budget availability |
| 2 | Approved supplier list | Preference to pre-qualified suppliers on the Approved Supplier List (ASL) |
| 3 | Competitive sourcing | Quotations/tenders required per threshold matrix |
| 4 | Written authorization | Every purchase requires written approval per Delegation of Authority |
| 5 | Purchase orders | No supplier may deliver goods/services without a valid PO (except emergencies) |
| 6 | Three-way match | Payment requires matching PO + GRN/Service Acceptance + Supplier Invoice |
| 7 | Conflict of interest | All procurement staff must declare conflicts annually and per-transaction |
| 8 | No split purchases | Deliberately splitting purchases to avoid thresholds is a disciplinary offence |
| 9 | Tax compliance | All POs must include supplier TIN; WHT deducted per URA rates |
| 10 | Record retention | All procurement records retained for minimum 7 years |

### 2.3 Emergency Procurement

| Parameter | Rule |
|-----------|------|
| Definition | Unforeseeable event threatening safety, operations, or significant financial loss |
| Authorization | MD verbal approval (written confirmation within 24 hours) |
| Threshold limit | Up to UGX 20,000,000 without competitive process |
| Documentation | Emergency Procurement Justification Form within 48 hours |
| Post-event | Retrospective review at next management meeting |
| Frequency cap | Maximum 3 emergency procurements per quarter before formal review |

---

## 3. Procurement Thresholds & Approval Matrix

### 3.1 Threshold Table

| Tier | Value Range (UGX) | Sourcing Method | Minimum Quotes | Approval Authority |
|------|-------------------|----------------|----------------|-------------------|
| **Tier 1** | Below 500,000 | Direct purchase | 1 quote | Department Head |
| **Tier 2** | 500,000 – 5,000,000 | Comparative shopping | 3 quotations | Operations Manager / Procurement Manager |
| **Tier 3** | 5,000,000 – 50,000,000 | Formal RFQ with bid comparison | 3+ formal quotes | Managing Director |
| **Tier 4** | 50,000,000 – 200,000,000 | Competitive tender | 5+ bidders invited | Managing Director + Finance Manager |
| **Tier 5** | Above 200,000,000 | Competitive tender | 5+ bidders invited | Board of Directors |

### 3.2 Approval Matrix — Lean Version

| Step | Tier 1 (<500K) | Tier 2 (500K–5M) | Tier 3 (5M–50M) |
|------|----------------|-------------------|-------------------|
| Requisition initiation | Any staff | Any staff | Department Head |
| Budget check | Operations Manager | Operations Manager | Finance Manager |
| Quotation sourcing | Requester | Operations Manager | Operations Manager |
| Bid evaluation | N/A | Operations Manager | MD + FM |
| PO approval | Operations Manager | MD | MD |
| Goods receipt | Operations Manager | Operations Manager | Operations Manager |
| Invoice verification | Finance Manager | Finance Manager | Finance Manager |
| Payment approval | Finance Manager | MD | MD |

> **Note — Lean Version:** In the Lean version, Tier 4 and Tier 5 purchases are unlikely to be frequent. When they occur, the MD acts as final approver with external board consultation for amounts above UGX 200,000,000.

### 3.3 Approval Matrix — Controlled Version

| Step | Tier 1 (<500K) | Tier 2 (500K–5M) | Tier 3 (5M–50M) | Tier 4 (50M–200M) | Tier 5 (>200M) |
|------|----------------|-------------------|-------------------|--------------------|----------------|
| Requisition initiation | Any staff | Any staff | Department Head | Department Head | Department Head |
| Budget check | Procurement Officer | Procurement Officer | Finance Manager | CFO | CFO |
| Quotation sourcing | Procurement Officer | Procurement Officer | Procurement Manager | Procurement Manager | Procurement Manager |
| Bid evaluation | N/A | Procurement Manager | Evaluation Committee | Tender Committee | Tender Committee |
| Technical evaluation | N/A | N/A | Technical evaluator | Technical evaluator | Technical evaluator |
| PO approval | Procurement Manager | Procurement Manager | MD | MD | MD + Board |
| Goods receipt | Stores Officer | Stores Officer | Stores Officer | Stores Officer + PM | Stores Officer + PM |
| Invoice verification | AP Officer | AP Officer | AP Officer | Finance Manager | CFO |
| Payment approval | Finance Manager | Finance Manager | MD | MD | MD + Board |

### 3.4 Tender Committee (Controlled Version)

| Member | Role |
|--------|------|
| Managing Director | Chairperson |
| Finance Manager / CFO | Financial evaluation |
| Procurement Manager | Process coordination |
| Relevant Department Head | Technical evaluation |
| Legal/Compliance Officer | Contract and compliance review |

The Tender Committee is convened for all Tier 4 and Tier 5 procurements. Quorum requires a minimum of 3 members including the MD or designated alternate.

---

## 4. Purchase Requisition to PO to Payment Workflow

### 4.1 End-to-End Process Flow

```
[Need Identified] → [Purchase Requisition] → [Budget Check] → [Sourcing/Quotations]
       → [Bid Evaluation] → [PO Issuance] → [Supplier Delivers] → [Goods Receipt/GRN]
       → [Invoice Received] → [Three-Way Match] → [Payment Processing] → [Record & Close]
```

### 4.2 Lean Version — Step by Step

| Step | Action | Responsible | Output | Timeline |
|------|--------|-------------|--------|----------|
| 1 | Identify need and complete Purchase Requisition Form (PRO-TPL-001) | Requester | Completed PR form | As needed |
| 2 | Department Head reviews and approves PR | Department Head / OM | Approved PR | Within 1 business day |
| 3 | Operations Manager checks budget availability with Finance Manager | OM + FM | Budget confirmation | Within 1 business day |
| 4 | Source quotations per threshold tier | OM | Quotations collected | 2–5 business days |
| 5 | Evaluate quotes (use Bid Comparison Sheet PRO-TPL-003 for Tier 2+) | OM (+ MD for Tier 3) | Evaluation record | 1–2 business days |
| 6 | Select supplier and obtain approval | OM / MD | Approved selection | 1 business day |
| 7 | Issue Purchase Order (PRO-TPL-004) | OM | Signed PO | 1 business day |
| 8 | Send PO to supplier and confirm delivery date | OM | Confirmed delivery | Same day |
| 9 | Receive goods/services and complete GRN (PRO-TPL-005) | OM | Signed GRN | At delivery |
| 10 | Forward supplier invoice + GRN + PO to Finance Manager | OM | Document pack | Within 1 business day |
| 11 | Finance Manager performs three-way match (PO vs GRN vs Invoice) | FM | Verified invoice | Within 2 business days |
| 12 | Process payment per approved payment cycle | FM | Payment voucher | Per payment cycle |
| 13 | File all documents (PR, quotes, PO, GRN, invoice, payment voucher) | FM / OM | Complete procurement file | Ongoing |

### 4.3 Controlled Version — Step by Step

| Step | Action | Responsible | Output | Timeline |
|------|--------|-------------|--------|----------|
| 1 | Identify need and complete Purchase Requisition in ERP | Requester | PR number generated | As needed |
| 2 | Department Head reviews and approves PR in ERP | Department Head | DH-approved PR | Within 1 business day |
| 3 | Procurement Officer validates PR and checks budget in ERP | PO-role + FM | Budget-confirmed PR | Within 1 business day |
| 4 | Procurement Officer/Manager sources quotations per tier | PO-role / PM | RFQ issued, quotes received | 3–7 business days |
| 5 | Evaluate bids using Bid Comparison Sheet (PRO-TPL-003) | PM / Evaluation Committee | Scored evaluation matrix | 2–5 business days |
| 6 | Technical evaluation (for Tier 3+) | Technical evaluator | Technical report | 2–3 business days |
| 7 | Procurement Manager recommends supplier | PM | Recommendation memo | 1 business day |
| 8 | Approval authority approves supplier selection per DoA | MD / Board | Approved recommendation | 1–5 business days |
| 9 | Issue Purchase Order in ERP with full terms | PM / PO-role | System-generated PO | 1 business day |
| 10 | Legal reviews contract terms (Tier 3+) | Legal Officer | Reviewed terms | 2–3 business days |
| 11 | Send PO/Contract to supplier | PO-role | Acknowledged PO | Same day |
| 12 | Track delivery against PO schedule | PO-role | Delivery tracking log | Ongoing |
| 13 | Receive goods, inspect quality, and record GRN in ERP | Stores Officer | System GRN | At delivery |
| 14 | Service acceptance sign-off (for services) | Requesting DH | Service Acceptance Certificate | At completion |
| 15 | Supplier submits tax-compliant invoice | Supplier | Original tax invoice | Per PO terms |
| 16 | AP Officer performs three-way match in ERP | APO | Matched invoice | Within 2 business days |
| 17 | Finance Manager approves for payment | FM / CFO | Approved payment batch | Within 2 business days |
| 18 | Process payment (EFT preferred) with WHT deduction | APO | Payment + WHT certificate | Per payment cycle |
| 19 | Update supplier ledger and procurement file | APO | Updated records | Same day |
| 20 | Close PO in ERP (or manage partial receipts) | PO-role | Closed/updated PO | On completion |

### 4.4 Three-Way Match Rules

| Match Element | Source Document | Verified Against |
|--------------|-----------------|-----------------|
| Quantities | Goods Received Note (GRN) | Purchase Order |
| Unit prices | Supplier Invoice | Purchase Order |
| Total amount | Supplier Invoice | PO x GRN quantities |
| Specifications | GRN quality notes | PO specifications |
| Tax details | Supplier Invoice | URA requirements (TIN, VAT, WHT) |

**Tolerance:** Invoiced amount may vary from PO by up to 5% or UGX 250,000 (whichever is less) without requiring a PO amendment. Variances exceeding this require a PO amendment approved at the original approval level.

---

## 5. Goods Receipt & Service Acceptance

### 5.1 Goods Receipt Process

| Step | Action | Lean | Controlled |
|------|--------|------|-----------|
| 1 | Supplier arrives with goods and delivery note | OM receives | Stores Officer receives |
| 2 | Check delivery note against PO (items, quantities) | OM | Stores Officer |
| 3 | Physical inspection — count, quality, packaging | OM | Stores Officer + Quality check |
| 4 | Record any discrepancies (short delivery, damage, wrong items) | Note on delivery note | Discrepancy Report in ERP |
| 5 | Complete GRN (PRO-TPL-005) | OM signs | Stores Officer records in ERP |
| 6 | Supplier signs GRN copy acknowledging receipt record | Supplier | Supplier |
| 7 | Notify requester that goods have arrived | OM (verbal/email) | System notification |
| 8 | Forward GRN + delivery note to Finance | OM | Auto-routed in ERP |

### 5.2 Service Acceptance Process

| Step | Action | Lean | Controlled |
|------|--------|------|-----------|
| 1 | Supplier notifies completion of service | Email/verbal | Formal completion notice |
| 2 | Requesting department inspects/verifies work | DH reviews | DH + Technical reviewer |
| 3 | Compare deliverables against PO/Contract/SLA | DH checks | DH checks against SLA metrics |
| 4 | Complete Service Acceptance Certificate | DH signs paper form | DH signs in ERP |
| 5 | Record any deficiencies or partial completion | Written note | Deficiency log in ERP |
| 6 | If deficient, issue Corrective Action Notice to supplier | OM sends | PM issues formal notice |
| 7 | Forward acceptance certificate to Finance | DH to FM | Auto-routed in ERP |

### 5.3 Partial Deliveries and Back-Orders

| Scenario | Action |
|----------|--------|
| Partial delivery — balance expected | Record partial GRN; PO remains open; track balance |
| Partial delivery — balance cancelled | Record partial GRN; amend PO; close balance |
| Over-delivery (within 5%) | Accept and amend PO if within budget |
| Over-delivery (above 5%) | Reject excess; return to supplier; no PO amendment |
| Wrong goods delivered | Reject; record discrepancy; notify supplier immediately |
| Damaged goods | Reject damaged items; record on GRN; supplier replaces |

---

## 6. Supplier Lifecycle Management

### 6.1 Supplier Lifecycle Stages

```
[Identification] → [Pre-qualification] → [Registration] → [Approved Supplier List]
     → [Engagement (POs/Contracts)] → [Performance Monitoring]
     → [Annual Review] → [Re-approval / Suspension / Removal]
```

### 6.2 Supplier Pre-Qualification Requirements

| Requirement | Detail |
|-------------|--------|
| Legal registration | Certificate of incorporation / Business registration |
| Tax compliance | Valid TIN, URA tax clearance certificate |
| Financial capacity | Bank reference letter, recent financial statements (for Tier 3+) |
| Technical capacity | Proof of capability, past performance references |
| Insurance | Relevant insurance certificates (where applicable) |
| Conflict of interest | Signed declaration of no conflict with Awdeer staff |
| Code of conduct | Signed Supplier Code of Conduct |

### 6.3 Approved Supplier List (ASL)

| Parameter | Lean | Controlled |
|-----------|------|-----------|
| Maintained by | Operations Manager | Procurement Manager |
| Format | Spreadsheet / ERP list | ERP Supplier Master |
| Review frequency | Annually | Semi-annually |
| Categories | By product/service type | By product/service type + tier |
| Minimum per category | 3 suppliers | 5 suppliers |
| Approval to add | MD | Procurement Manager + MD |
| Approval to remove | MD | Procurement Manager + MD |

### 6.4 Supplier Performance Evaluation

| Criteria | Weight | Measurement |
|----------|--------|-------------|
| Delivery timeliness | 25% | % of on-time deliveries |
| Quality compliance | 25% | % of deliveries meeting specifications |
| Price competitiveness | 20% | Comparison with market rates |
| Responsiveness | 15% | Average response time to queries/issues |
| Documentation accuracy | 10% | % of error-free invoices and delivery notes |
| Compliance (tax, safety) | 5% | Valid certifications maintained |

**Scoring:**

| Rating | Score | Action |
|--------|-------|--------|
| Excellent | 90–100 | Preferred supplier; consider strategic partnership |
| Good | 75–89 | Maintain on ASL; no action required |
| Satisfactory | 60–74 | Improvement plan required; monitor closely |
| Poor | Below 60 | Issue warning; if no improvement in 90 days, suspend |
| Critical failure | Any score + critical incident | Immediate suspension pending review |

### 6.5 Supplier Suspension and Removal

| Trigger | Action | Authority |
|---------|--------|-----------|
| Two consecutive evaluations below 60 | Suspend from ASL | Procurement Manager + MD |
| Fraud, bribery, or corruption | Immediate removal and blacklist | MD (Lean) / Board (Controlled) |
| Persistent tax non-compliance | Suspend until compliant | Finance Manager + PM |
| Breach of contract terms | Suspension pending investigation | PM + Legal |
| Conflict of interest discovered | Immediate suspension | MD |
| Supplier requests removal | Remove from ASL | PM updates records |

---

## 7. Contracting & SLA Management

### 7.1 When Contracts Are Required

| Scenario | Contract Required? | Type |
|----------|-------------------|------|
| One-time purchase below UGX 5,000,000 | No — PO terms sufficient | Purchase Order |
| Recurring purchases (any value) | Yes | Framework/Supply Agreement |
| Any purchase above UGX 5,000,000 | Recommended | Supply Contract |
| Any purchase above UGX 50,000,000 | Yes — mandatory | Formal Contract |
| Services engagement | Yes | Service Agreement / SLA |
| Consulting/professional services | Yes | Consultancy Agreement |
| Construction/works | Yes | Works Contract |

### 7.2 Standard Contract Elements

| Element | Detail |
|---------|--------|
| Parties | Full legal names, TINs, registered addresses |
| Scope of work/supply | Detailed specifications, quantities, deliverables |
| Price and payment terms | Unit prices, total value, payment schedule, currency (UGX) |
| Delivery terms | Delivery location, schedule, Incoterms (if international) |
| Quality standards | Specifications, acceptance criteria, testing requirements |
| Warranty/guarantee | Period, coverage, remedy process |
| Performance bonds | Required for Tier 4+ (5–10% of contract value) |
| Penalties/liquidated damages | Late delivery penalties, defect remedies |
| Termination clauses | Termination for convenience, termination for cause |
| Dispute resolution | Negotiation → Mediation → Arbitration (Uganda) |
| Governing law | Laws of the Republic of Uganda |
| Confidentiality | Non-disclosure obligations |
| Anti-corruption | Anti-bribery and corruption warranty |
| Insurance requirements | As applicable to contract type |
| Tax obligations | WHT, VAT responsibilities clearly assigned |

### 7.3 SLA Management

| SLA Element | Examples |
|-------------|----------|
| Delivery lead time | X business days from PO date |
| Quality acceptance rate | Minimum 95% first-pass acceptance |
| Response time | Acknowledge queries within X hours |
| Issue resolution | Resolve complaints within X business days |
| Reporting | Monthly/quarterly performance reports |
| Review meetings | Quarterly review meetings for strategic suppliers |

### 7.4 Contract Lifecycle

| Phase | Lean | Controlled |
|-------|------|-----------|
| Drafting | OM drafts using templates | PM drafts; Legal reviews |
| Review | FM reviews financial terms | FM + Legal + Technical review |
| Negotiation | OM + MD | PM + Legal + relevant DH |
| Approval | MD | MD (Tier 3), MD + Board (Tier 4–5) |
| Execution | MD signs | MD signs; Legal witnesses |
| Storage | Physical file + digital scan | ERP contract module + Legal repository |
| Monitoring | OM tracks milestones | PM tracks in ERP; automated alerts |
| Renewal/Expiry | OM flags 60 days before | System alert 90 days before expiry |
| Amendment | MD approves changes | Change order process; Legal reviews |
| Close-out | OM confirms completion | PM issues close-out certificate |

---

## 8. Procurement Fraud Controls

### 8.1 Fraud Risk Register — Procurement

| # | Fraud Risk | Likelihood | Impact | Inherent Risk | Key Controls |
|---|-----------|------------|--------|---------------|-------------|
| 1 | Split purchases to avoid thresholds | High | Medium | High | System-flagged sequential POs; management reporting |
| 2 | Vendor conflict of interest | High | High | Critical | Annual declarations; surprise audits |
| 3 | Bid rigging / collusion | Medium | High | High | Sealed bids; independent evaluation; rotation |
| 4 | Fictitious suppliers | Medium | High | High | Physical verification; bank account validation |
| 5 | Invoice fraud (inflated/duplicate) | Medium | High | High | Three-way match; duplicate detection in ERP |
| 6 | Kickbacks from suppliers | Medium | High | High | Declaration policy; whistleblower line; rotation |
| 7 | Accepting sub-standard goods | Medium | Medium | Medium | Independent quality inspection; GRN controls |
| 8 | Unauthorized purchases | Low | Medium | Medium | PO-required policy; system access controls |
| 9 | Favoring specific suppliers without justification | Medium | Medium | Medium | Supplier rotation monitoring; evaluation records |
| 10 | Post-award contract manipulation | Low | High | Medium | Change order controls; Legal review of amendments |

### 8.2 Split Purchase Prevention

| Control | Detail |
|---------|--------|
| System monitoring | ERP flags multiple POs to same supplier within 30 days that cumulatively exceed threshold |
| Monthly report | Procurement Manager reviews all purchases by supplier, by category, by requester |
| Annual analysis | Internal Audit analyses procurement patterns for split-purchase indicators |
| Red flags | Same supplier, same category, sequential dates, just-below-threshold amounts |
| Consequence | Split purchasing is a disciplinary offence — written warning to dismissal |
| Reporting | Quarterly report to MD on flagged transactions |

### 8.3 Vendor Conflict of Interest Controls

| Control | Lean | Controlled |
|---------|------|-----------|
| Annual declaration | All staff involved in procurement | All staff company-wide |
| Per-transaction declaration | For Tier 3+ | For Tier 2+ |
| Supplier declaration | At registration | At registration + annually |
| Register maintenance | FM maintains spreadsheet | Compliance Officer maintains in ERP |
| Consequences | Removal from procurement role + disciplinary | Removal + disciplinary + potential termination |
| Review | MD reviews annually | Compliance Officer reviews quarterly; Internal Audit tests |

**Relationships requiring declaration:**
- Family members (spouse, children, parents, siblings, in-laws)
- Business partnerships or shareholding
- Previous employment with supplier
- Personal friendships with supplier principals
- Any financial interest in supplier entity

### 8.4 Bid Rigging Prevention

| Control | Detail |
|---------|--------|
| Supplier rotation | No single supplier to win more than 60% of category spend annually |
| Sealed bids | Physical sealed envelopes (manual) or system-locked submissions (ERP) |
| Opening ceremony | Tier 4–5 bids opened in presence of minimum 3 committee members |
| Independent evaluation | Evaluators score independently before discussion |
| Bid validity period | Minimum 60 days to prevent pressure tactics |
| Market price benchmarking | Procurement maintains price database; flags bids >15% above benchmark |
| Supplier communication | All communication through procurement function only during bidding |
| Bid withdrawal monitoring | Track patterns of suppliers withdrawing after bid opening |
| Same-source detection | System flags bids from companies with common directors, addresses, or bank accounts |

### 8.5 Fictitious Supplier Prevention

| Control | Detail |
|---------|--------|
| Physical verification | Site visit for all suppliers above UGX 10,000,000 annual spend |
| Bank account validation | Bank confirmation letter required before first payment |
| TIN verification | Cross-check with URA TIN database |
| Director check | Companies House (URSB) search to verify directors |
| Payment controls | No payments to personal accounts for company suppliers |
| New supplier setup | Requires independent approval (not by procurement requester) |
| Dormant supplier review | Flag suppliers with no transactions for 12 months; verify before reactivation |

### 8.6 Whistleblower and Reporting

| Channel | Detail |
|---------|--------|
| Whistleblower hotline | Dedicated phone/email for anonymous reporting |
| Protection | Whistleblower protection per company policy and Uganda Whistleblowers Protection Act |
| Investigation | Internal Audit investigates all reports within 5 business days |
| Escalation | Confirmed fraud escalated to MD and Board |
| Record keeping | All reports logged in confidential register |

---

## 9. SOPs Index

| SOP Code | Title | File |
|----------|-------|------|
| PRO-REQ-001 | Purchase Requisition to PO Workflow | `sops/PRO-REQ-001-purchase-requisition.md` |
| PRO-RCV-001 | Goods Receipt and Service Acceptance | `sops/PRO-RCV-001-goods-receipt.md` |
| PRO-VND-001 | Supplier Evaluation and Management | `sops/PRO-VND-001-supplier-management.md` |
| PRO-CTR-001 | Procurement Contracting and SLA Management | `sops/PRO-CTR-001-contract-management.md` |
| PRO-FRD-001 | Procurement Fraud Prevention Controls | `sops/PRO-FRD-001-fraud-controls.md` |

---

## 10. Templates Index

| Template Code | Title | File |
|---------------|-------|------|
| PRO-TPL-001 | Purchase Requisition Form | `templates/PRO-TPL-001-purchase-requisition.md` |
| PRO-TPL-002 | Request for Quotation (RFQ) | `templates/PRO-TPL-002-rfq-template.md` |
| PRO-TPL-003 | Bid Comparison / Evaluation Sheet | `templates/PRO-TPL-003-bid-comparison-sheet.md` |
| PRO-TPL-004 | Purchase Order | `templates/PRO-TPL-004-purchase-order.md` |
| PRO-TPL-005 | Goods Received Note (GRN) | `templates/PRO-TPL-005-goods-received-note.md` |
| PRO-TPL-006 | Supplier Evaluation Scorecard | `templates/PRO-TPL-006-supplier-evaluation-scorecard.md` |

---

## 11. Key Performance Indicators

| KPI | Target | Frequency | Owner |
|-----|--------|-----------|-------|
| PR to PO cycle time | ≤ 5 business days (Lean); ≤ 7 business days (Controlled) | Monthly | Procurement Manager / OM |
| PO to delivery cycle time | ≤ 10 business days (standard items) | Monthly | Procurement Manager / OM |
| Supplier on-time delivery rate | ≥ 90% | Monthly | Procurement Manager / OM |
| Three-way match rate (first pass) | ≥ 85% | Monthly | Finance Manager |
| Cost savings vs budget | ≥ 5% annual savings | Quarterly | Procurement Manager / OM |
| POs issued without prior PR | 0% | Monthly | Internal Audit |
| Supplier evaluation completion rate | 100% of active suppliers annually | Annually | Procurement Manager / OM |
| Procurement fraud incidents | 0 | Quarterly | Internal Audit |
| Emergency procurement ratio | ≤ 5% of total procurement value | Quarterly | Procurement Manager / OM |
| Average payment cycle to suppliers | ≤ 30 days from invoice | Monthly | Finance Manager |
| Approved Supplier List coverage | ≥ 80% of spend through ASL suppliers | Quarterly | Procurement Manager / OM |
| Split purchase flags resolved | 100% investigated within 10 days | Monthly | Internal Audit |

---

## 12. ERP Module Mapping

| Process | ERP Module | Key Functions |
|---------|-----------|---------------|
| Purchase Requisition | Purchase / Procurement | PR creation, approval workflow, budget check |
| Supplier Management | Contacts / Vendor Master | Supplier registration, categorization, evaluation |
| RFQ / Tendering | Purchase / Procurement | RFQ creation, bid receipt, comparison |
| Purchase Orders | Purchase / Procurement | PO creation, approval, dispatch, tracking |
| Goods Receipt | Inventory / Warehouse | GRN entry, quality check, stock update |
| Invoice Matching | Accounting / AP | Three-way match, invoice verification |
| Payments | Accounting / AP | Payment batch, WHT calculation, bank transfer |
| Contracts | Purchase / Legal | Contract creation, milestone tracking, renewal alerts |
| Reporting | BI / Reporting | Dashboards, spend analysis, supplier performance |

---

*Awdeer Investments Limited — Procurement & Vendor Management System*
*Part D of the Business Operating System*
*Version 1.0 — February 2026*
