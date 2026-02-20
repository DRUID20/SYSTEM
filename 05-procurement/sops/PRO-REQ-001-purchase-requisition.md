# SOP: PRO-REQ-001 — Purchase Requisition to Purchase Order Workflow

## Awdeer Investments Limited — Uganda

| Field | Detail |
|-------|--------|
| SOP Code | PRO-REQ-001 |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Operations Manager (Lean) / Procurement Manager (Controlled) |
| Approved By | Managing Director |
| Review Cycle | Annually or upon material change |

---

## 1. Purpose

This SOP defines the standard workflow for initiating a purchase requisition (PR), converting it to a purchase order (PO), and managing the procurement process through to supplier engagement. It ensures that all purchases are properly authorized, budgeted, competitively sourced, and documented with a complete audit trail.

---

## 2. Scope

**In Scope:**
- All purchases of goods, services, and works across all business lines
- All procurement tiers (Tier 1 through Tier 5)
- Both CAPEX and OPEX purchases
- Local and international procurement

**Out of Scope:**
- Petty cash purchases below UGX 100,000 (governed by FIN-PC-001)
- Employee expense reimbursements (governed by FIN-EXP-001)
- Payroll and statutory payments (governed by HR-PAY-001)
- Emergency procurement (separate emergency protocol in procurement-system.md)

---

## 3. RACI Matrix

### Lean Version

| Activity | Requester | Dept Head / OM | Finance Manager | MD |
|----------|-----------|---------------|-----------------|-----|
| Initiate PR | **R, A** | I | I | — |
| Review & approve PR | I | **R, A** | C | — |
| Verify budget availability | — | R | **R, A** | — |
| Source quotations | — | **R, A** | — | — |
| Evaluate bids | — | **R, A** | C | C (Tier 3+) |
| Approve supplier selection | — | R (Tier 1–2) | C | **A** (Tier 3+) |
| Issue Purchase Order | — | **R, A** | I | — |
| Dispatch PO to supplier | — | **R** | — | — |
| File procurement records | — | **R** | **R** | — |

> R = Responsible, A = Accountable, C = Consulted, I = Informed

### Controlled Version

| Activity | Requester | Dept Head | Proc. Officer | Proc. Manager | Finance Manager | MD | Board |
|----------|-----------|-----------|---------------|---------------|-----------------|-----|-------|
| Initiate PR | **R, A** | I | I | I | — | — | — |
| Approve PR | I | **R, A** | — | — | — | — | — |
| Verify budget | — | — | R | — | **R, A** | — | — |
| Source quotations | — | — | **R** | **A** | — | — | — |
| Technical evaluation | — | C | — | R | — | — | — |
| Evaluate bids | — | C | R | **R, A** (Tier 2–3) | C | — | — |
| Tender Committee evaluation | — | C | I | **R** | R | **A** | — |
| Approve supplier selection | — | — | — | A (Tier 1–2) | C | **A** (Tier 3–4) | **A** (Tier 5) |
| Issue Purchase Order | — | I | **R** | **A** | I | — | — |
| Legal review (Tier 3+) | — | — | — | C | — | — | — |
| Dispatch PO to supplier | — | — | **R** | I | — | — | — |
| File procurement records | — | — | **R** | A | — | — | — |

---

## 4. Inputs and Outputs

### Inputs

| Input | Source | Format |
|-------|--------|--------|
| Business need / requirement | Requesting department | Verbal / email / project plan |
| Approved budget | Finance | Budget allocation spreadsheet / ERP |
| Approved Supplier List (ASL) | Procurement | Spreadsheet / ERP master |
| Procurement thresholds & approval matrix | Procurement Policy | procurement-system.md |
| Previous purchase history | Procurement records / ERP | Historical data |

### Outputs

| Output | Destination | Format |
|--------|-------------|--------|
| Approved Purchase Requisition | Procurement function | PRO-TPL-001 / ERP record |
| Request for Quotation (if applicable) | Suppliers | PRO-TPL-002 |
| Bid Comparison Sheet | Procurement file | PRO-TPL-003 |
| Approved Purchase Order | Supplier + Finance + Stores | PRO-TPL-004 / ERP record |
| Procurement file (complete) | Procurement records | Physical file / ERP |

---

## 5. Step-by-Step Workflow

### 5.1 Lean Version

#### Step 1: Identify Need and Prepare Purchase Requisition

| Detail | Description |
|--------|-------------|
| Actor | Requester (any staff member) |
| Action | Complete Purchase Requisition Form (PRO-TPL-001) with: item description, quantity, estimated cost, budget code, justification, preferred supplier (if any), required delivery date |
| Timeframe | As needed |
| Output | Completed PR form |
| Key rule | Estimated cost determines the procurement tier and therefore the required process |

#### Step 2: Department Head / Operations Manager Approval

| Detail | Description |
|--------|-------------|
| Actor | Department Head or Operations Manager |
| Action | Review PR for: business need validity, correct specifications, reasonable cost estimate, correct budget code. Approve or reject with comments |
| Timeframe | Within 1 business day of receipt |
| Output | Approved or rejected PR |
| Key rule | DH approves Tier 1 directly; OM approves Tier 1–2; MD required for Tier 3+ |

#### Step 3: Budget Verification

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager + Finance Manager |
| Action | Finance Manager confirms budget availability against the specified budget code. Stamps or signs budget confirmation on PR |
| Timeframe | Within 1 business day |
| Output | Budget-confirmed PR |
| Key rule | If budget insufficient: PR returned to requester. Requester may request budget reallocation through Finance Manager and MD |

#### Step 4: Sourcing Quotations

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Source quotations per procurement tier: Tier 1 — 1 quote acceptable. Tier 2 — Minimum 3 written quotations. Tier 3 — Formal RFQ (PRO-TPL-002) to minimum 3 suppliers |
| Timeframe | 2–5 business days depending on tier |
| Output | Collected quotations |
| Key rules | Quotations must be from different, independent suppliers. All quotations must include supplier TIN. Quotations must be in UGX (or converted at prevailing BoU rate) |

#### Step 5: Evaluate Quotations

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager (Tier 1–2); OM + MD + FM (Tier 3) |
| Action | Compare quotations using Bid Comparison Sheet (PRO-TPL-003) for Tier 2+. Evaluate on: price, quality, delivery time, payment terms, supplier track record |
| Timeframe | 1–2 business days |
| Output | Completed Bid Comparison Sheet with recommendation |
| Key rule | Lowest price is not automatically selected — best value for money is the criterion |

#### Step 6: Approve Supplier Selection

| Detail | Description |
|--------|-------------|
| Actor | OM (Tier 1–2) / MD (Tier 3+) |
| Action | Review bid comparison and recommendation. Approve selected supplier. Sign approval on Bid Comparison Sheet |
| Timeframe | 1 business day |
| Output | Approved supplier selection |
| Key rule | Approver must not be the same person who sourced quotations (segregation of duties) |

#### Step 7: Issue Purchase Order

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Prepare Purchase Order (PRO-TPL-004) with: PO number, supplier details, item descriptions, quantities, unit prices, total amount, delivery date, delivery location, payment terms, standard T&Cs. Obtain required signature(s) per approval matrix |
| Timeframe | 1 business day |
| Output | Signed Purchase Order |
| Key rule | PO number must be sequential and unique. PO must reference the PR number |

#### Step 8: Dispatch PO to Supplier

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Send PO to supplier via email (preferred) or hand delivery. Obtain supplier acknowledgment and confirmed delivery date |
| Timeframe | Same day as PO issuance |
| Output | Acknowledged PO; confirmed delivery date |
| Key rule | Retain proof of PO dispatch (email sent record or signed receipt) |

#### Step 9: File and Track

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Create procurement file containing: PR, budget confirmation, quotations, bid comparison sheet, approval records, PO, supplier acknowledgment. Track expected delivery date |
| Timeframe | Ongoing |
| Output | Complete procurement file; delivery tracking |
| Key rule | File must be accessible for audit at any time |

### 5.2 Controlled Version

#### Step 1: Initiate Purchase Requisition in ERP

| Detail | Description |
|--------|-------------|
| Actor | Requester |
| Action | Create PR in ERP system with: item codes (from product master), quantity, unit of measure, estimated unit cost, budget code (auto-populated), cost centre, detailed justification, delivery requirements, attachments (specs, drawings if applicable) |
| Timeframe | As needed |
| Output | System-generated PR number |
| Key rule | ERP automatically classifies procurement tier based on estimated total value |

#### Step 2: Department Head Approval

| Detail | Description |
|--------|-------------|
| Actor | Department Head |
| Action | Review PR in ERP. Verify business need, specifications, and priority. Approve or reject with comments in system |
| Timeframe | Within 1 business day |
| Output | DH-approved PR (system status updated) |
| Key rule | System notification sent to DH on PR submission. Escalation if not actioned within 2 business days |

#### Step 3: Procurement Officer Validation and Budget Check

| Detail | Description |
|--------|-------------|
| Actor | Procurement Officer + Finance Manager |
| Action | Procurement Officer validates: completeness, correct item codes, reasonable estimates, no duplicate PRs. Finance Manager (or system) confirms budget availability. ERP performs automatic budget commitment (encumbrance) |
| Timeframe | Within 1 business day |
| Output | Validated, budget-confirmed PR |
| Key rule | ERP blocks PR if budget insufficient. Budget reallocation requires FM + MD approval |

#### Step 4: Sourcing Strategy

| Detail | Description |
|--------|-------------|
| Actor | Procurement Officer / Procurement Manager |
| Action | Determine sourcing approach: Tier 1 — Direct purchase from ASL. Tier 2 — Request 3 quotations from ASL suppliers. Tier 3 — Issue formal RFQ to minimum 3 ASL suppliers + 1 new supplier. Tier 4–5 — Issue formal tender invitation to minimum 5 suppliers |
| Timeframe | 1 business day (strategy); 3–7 business days (sourcing) |
| Output | RFQ/Tender documents issued |
| Key rule | RFQs for Tier 3+ require Procurement Manager approval before issue |

#### Step 5: Receive and Record Quotations/Bids

| Detail | Description |
|--------|-------------|
| Actor | Procurement Officer |
| Action | Receive quotations/bids. For Tier 4–5: sealed bids stored unopened until bid opening date. Record all received bids in ERP. Late bids rejected and recorded |
| Timeframe | Per RFQ/tender closing date |
| Output | Complete set of received quotations/bids |
| Key rule | Tier 4–5 bids opened in formal session with minimum 3 Tender Committee members present |

#### Step 6: Bid Evaluation

| Detail | Description |
|--------|-------------|
| Actor | Procurement Manager (Tier 2–3) / Evaluation Committee (Tier 4–5) |
| Action | Evaluate bids using Bid Comparison Sheet (PRO-TPL-003). Score each bid against weighted criteria: price (40%), quality (25%), delivery (15%), terms (10%), supplier rating (10%). Prepare evaluation report with ranked recommendations |
| Timeframe | 2–5 business days |
| Output | Completed evaluation matrix; recommendation report |
| Key rule | Each evaluator scores independently before group discussion. All scores documented |

#### Step 7: Technical Evaluation (Tier 3+)

| Detail | Description |
|--------|-------------|
| Actor | Technical evaluator (relevant Department Head / specialist) |
| Action | Evaluate technical compliance of top-ranked bids. Verify specifications, samples (if required), references. Issue Technical Evaluation Report |
| Timeframe | 2–3 business days |
| Output | Technical Evaluation Report |
| Key rule | Technical evaluation is pass/fail — only technically compliant bids proceed to final selection |

#### Step 8: Supplier Selection Approval

| Detail | Description |
|--------|-------------|
| Actor | Procurement Manager (Tier 1–2) / MD (Tier 3–4) / Board (Tier 5) |
| Action | Review evaluation report and recommendation. Approve selected supplier. Record approval in ERP |
| Timeframe | 1–5 business days depending on tier |
| Output | Approved supplier selection |
| Key rule | Board approval for Tier 5 requires formal board resolution |

#### Step 9: Issue Purchase Order in ERP

| Detail | Description |
|--------|-------------|
| Actor | Procurement Officer |
| Action | Convert approved PR to PO in ERP. System generates PO with: unique PO number, full supplier details, line items with prices from approved bid, delivery schedule, standard terms and conditions, WHT applicability flag, required approval signatures |
| Timeframe | 1 business day |
| Output | System-generated PO pending approval |
| Key rule | PO total must not exceed approved PR amount by more than 5% (system control) |

#### Step 10: PO Approval

| Detail | Description |
|--------|-------------|
| Actor | Per approval matrix — Procurement Manager / MD / Board |
| Action | Review and approve PO in ERP |
| Timeframe | 1–2 business days |
| Output | Approved PO (system status: approved) |
| Key rule | System enforces approval hierarchy — cannot be bypassed |

#### Step 11: Legal Review (Tier 3+)

| Detail | Description |
|--------|-------------|
| Actor | Legal / Compliance Officer |
| Action | Review contract terms, T&Cs, SLA provisions. Flag any risk areas. Approve or request amendments |
| Timeframe | 2–3 business days |
| Output | Legal-cleared PO/contract |
| Key rule | Mandatory for all procurements above UGX 5,000,000 and all service agreements |

#### Step 12: Dispatch PO/Contract to Supplier

| Detail | Description |
|--------|-------------|
| Actor | Procurement Officer |
| Action | Send approved PO to supplier via email from ERP. For Tier 3+, send contract for counter-signature. Record supplier acknowledgment in ERP |
| Timeframe | Same day as approval |
| Output | Dispatched PO; supplier acknowledgment |
| Key rule | ERP generates automatic follow-up if acknowledgment not received within 2 business days |

#### Step 13: Track and Monitor

| Detail | Description |
|--------|-------------|
| Actor | Procurement Officer |
| Action | Monitor delivery schedule. Follow up with suppliers on overdue deliveries. Update ERP with delivery status. Escalate delays to Procurement Manager |
| Timeframe | Ongoing until PO fully delivered |
| Output | Delivery tracking records; escalation reports |
| Key rule | System alerts for deliveries overdue by more than 3 business days |

---

## 6. Controls and Approvals

| Control | Description | Version |
|---------|-------------|---------|
| Segregation of duties | Requester cannot approve own PR; approver cannot issue PO to self | Both |
| Budget encumbrance | System commits budget at PR approval stage | Controlled |
| Threshold enforcement | System/manual check ensures correct sourcing method per tier | Both |
| Duplicate PR detection | ERP flags PRs for same item/supplier within 30 days | Controlled |
| Approval hierarchy | System enforces correct approver per Delegation of Authority | Controlled |
| PO–PR linkage | Every PO must reference an approved PR | Both |
| Quote authenticity | All quotations verified (letterhead, TIN, contact details) | Both |
| Independent evaluation | Bid evaluators must not have conflict of interest | Both |
| Audit trail | All actions timestamped with user ID in ERP; paper trail for Lean | Both |
| PO amendment control | Amendments require re-approval at original approval level | Both |

---

## 7. Documents and Forms

| Document | Template Code | Purpose |
|----------|--------------|---------|
| Purchase Requisition Form | PRO-TPL-001 | Initiate procurement request |
| Request for Quotation | PRO-TPL-002 | Solicit supplier quotations |
| Bid Comparison Sheet | PRO-TPL-003 | Compare and evaluate quotations/bids |
| Purchase Order | PRO-TPL-004 | Formal order to supplier |
| Goods Received Note | PRO-TPL-005 | Record receipt of goods |
| Supplier Evaluation Scorecard | PRO-TPL-006 | Evaluate supplier performance |

---

## 8. Key Performance Indicators

| KPI | Target | Measurement Method | Frequency |
|-----|--------|-------------------|-----------|
| PR to PO cycle time | ≤ 5 BD (Lean) / ≤ 7 BD (Controlled) | Average days from PR submission to PO issuance | Monthly |
| PR rejection rate | ≤ 10% | Number of rejected PRs / total PRs submitted | Monthly |
| Budget compliance | 100% of POs within approved budget | POs issued without budget confirmation / total POs | Monthly |
| Quotation compliance | 100% at Tier 2+ | POs with required number of quotations / total POs at Tier 2+ | Monthly |
| PO accuracy | ≥ 95% | POs with no amendments required / total POs | Monthly |
| Unauthorized purchases | 0 | Purchases without valid PO | Monthly |
| Approval turnaround | ≤ 2 BD per approval step | Average days per approval step | Monthly |
| Supplier acknowledgment rate | 100% within 2 BD | POs acknowledged within 2 BD / total POs dispatched | Monthly |

---

## 9. Process Flow Diagram

```
LEAN VERSION:

Requester              Operations Manager       Finance Manager         MD
    |                        |                       |                   |
    |-- Submit PR (TPL-001) -->                      |                   |
    |                        |                       |                   |
    |                  Review & Approve PR            |                   |
    |                        |                       |                   |
    |                        |-- Budget Check ------->                   |
    |                        |                       |                   |
    |                        |<-- Budget Confirmed ---|                   |
    |                        |                       |                   |
    |                  Source Quotations               |                   |
    |                        |                       |                   |
    |                  Evaluate Bids (TPL-003)        |                   |
    |                        |                       |                   |
    |                        |---- Tier 3+ Approval ----------------->  |
    |                        |                       |                   |
    |                        |<--- Approved ----------------------------|
    |                        |                       |                   |
    |                  Issue PO (TPL-004)              |                   |
    |                        |                       |                   |
    |                  Send PO to Supplier             |                   |
    |                        |                       |                   |
    |<-- Delivery Notification                        |                   |


CONTROLLED VERSION:

Requester → DH Approve → Proc. Officer Validate → FM Budget Check
    → Proc. Officer Source (RFQ) → Receive Bids → Proc. Manager Evaluate
    → Technical Eval (Tier 3+) → Approval Authority Approves
    → Proc. Officer Issues PO in ERP → Legal Review (Tier 3+)
    → PO Approved → Dispatch to Supplier → Track Delivery
```

---

## 10. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | February 2026 | System Design | Initial version |

---

*Awdeer Investments Limited*
*SOP: PRO-REQ-001 — Purchase Requisition to Purchase Order Workflow*
*Version 1.0 — February 2026*
