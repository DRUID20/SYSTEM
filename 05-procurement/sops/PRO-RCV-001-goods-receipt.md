# SOP: PRO-RCV-001 — Goods Receipt and Service Acceptance

## Awdeer Investments Limited — Uganda

| Field | Detail |
|-------|--------|
| SOP Code | PRO-RCV-001 |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Operations Manager (Lean) / Stores/Inventory Officer (Controlled) |
| Approved By | Managing Director |
| Review Cycle | Annually or upon material change |

---

## 1. Purpose

This SOP establishes the standard process for receiving goods and accepting services delivered by suppliers against approved Purchase Orders. It ensures that all deliveries are properly inspected, documented, matched against PO terms, and recorded to enable accurate three-way matching for payment processing.

---

## 2. Scope

**In Scope:**
- Receipt of all physical goods delivered to any Awdeer location
- Acceptance of all services rendered by external suppliers
- Partial deliveries and back-orders
- Rejection and return of non-conforming goods
- Goods received on behalf of other departments or branches

**Out of Scope:**
- Internal stock transfers between departments (governed by INV-TRF-001)
- Receipt of employee personal items
- Returns of Awdeer products by customers (governed by SAL-RET-001)

---

## 3. RACI Matrix

### Lean Version

| Activity | Requester | Operations Manager | Finance Manager | MD |
|----------|-----------|-------------------|-----------------|-----|
| Notify expected delivery | I | **R, A** | — | — |
| Receive goods at location | — | **R, A** | — | — |
| Physical inspection & count | — | **R, A** | — | — |
| Complete GRN | — | **R, A** | I | — |
| Record discrepancies | — | **R, A** | I | I (if material) |
| Service acceptance verification | **R** | **A** | — | — |
| Sign Service Acceptance Certificate | **R, A** | I | I | — |
| Forward documents to Finance | — | **R** | **A** | — |
| Handle returns/rejections | — | **R, A** | I | I (if material) |

### Controlled Version

| Activity | Requester | Dept Head | Stores Officer | Proc. Manager | Finance / AP | MD |
|----------|-----------|-----------|---------------|---------------|-------------|-----|
| Notify expected delivery | — | — | I | **R, A** | — | — |
| Receive goods at loading bay | — | — | **R, A** | I | — | — |
| Physical inspection & count | — | — | **R, A** | — | — | — |
| Quality inspection | — | C | **R** | **A** | — | — |
| Complete GRN in ERP | — | — | **R, A** | I | I | — |
| Record discrepancies in ERP | — | I | **R** | **A** | I | I (if >5% value) |
| Service acceptance verification | **R** | **A** | — | I | — | — |
| Sign Service Acceptance Certificate | — | **R, A** | — | I | I | — |
| Forward documents to AP | — | — | **R** | — | **A** | — |
| Handle returns/rejections | — | I | **R** | **A** | I | — |
| Update stock records | — | — | **R, A** | — | — | — |

---

## 4. Inputs and Outputs

### Inputs

| Input | Source | Format |
|-------|--------|--------|
| Approved Purchase Order | Procurement | PRO-TPL-004 / ERP PO |
| Supplier delivery note / packing list | Supplier | Supplier document |
| Product specifications | PO / Technical specs | As per PO |
| Expected delivery schedule | PO / Supplier confirmation | Calendar / ERP schedule |
| Quality standards / acceptance criteria | PO / Contract / SLA | As specified |

### Outputs

| Output | Destination | Format |
|--------|-------------|--------|
| Goods Received Note (GRN) | Finance, Procurement, Inventory | PRO-TPL-005 / ERP record |
| Service Acceptance Certificate | Finance, Procurement | Signed certificate |
| Discrepancy Report | Procurement Manager, Supplier | Written report / ERP record |
| Return to Supplier Note | Supplier, Procurement, Finance | Written note |
| Updated stock records | Inventory system | ERP / Stock ledger |

---

## 5. Step-by-Step Workflow

### 5.1 Goods Receipt — Lean Version

#### Step 1: Prepare for Delivery

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Review PO to confirm expected items, quantities, and delivery date. Ensure receiving area is prepared. Notify relevant staff of expected delivery |
| Timeframe | Before expected delivery date |
| Output | Prepared receiving area; staff notified |

#### Step 2: Receive Supplier at Delivery Point

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Meet supplier delivery team. Collect supplier's delivery note and any other documentation (certificates, test reports). Verify supplier identity against PO |
| Timeframe | At delivery |
| Output | Delivery note collected |

#### Step 3: Physical Inspection and Count

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Count all items against delivery note AND Purchase Order. Check packaging integrity — note any visible damage. Verify item descriptions match PO specifications. Check quantities match PO quantities. Inspect quality/condition of goods (visual inspection at minimum) |
| Timeframe | At delivery (within 1 hour for standard deliveries) |
| Output | Inspection completed |
| Key rules | Do NOT sign delivery note until inspection is complete. If items require technical testing, note "Received pending quality check" |

#### Step 4: Record Discrepancies (if any)

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Document any discrepancies on both the delivery note and GRN: short delivery (fewer items than PO), over-delivery, wrong items, damaged items, quality issues. Photograph damage if applicable. Notify supplier representative immediately |
| Timeframe | At delivery |
| Output | Noted discrepancies on delivery note and GRN |
| Key rules | Supplier representative must countersign acknowledgment of discrepancies. Do NOT accept clearly wrong or damaged goods — reject on the spot |

#### Step 5: Complete Goods Received Note (GRN)

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Complete GRN form (PRO-TPL-005) with: GRN number (sequential), date and time received, PO number reference, supplier name and delivery note number, item descriptions, quantities ordered vs received, condition of goods (good/damaged/rejected), receiving officer signature, supplier representative signature |
| Timeframe | At delivery — immediately after inspection |
| Output | Completed, signed GRN |
| Key rule | GRN number must be unique and sequential. One GRN per delivery (even if against same PO) |

#### Step 6: Sign Supplier Delivery Note

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Sign supplier's delivery note ONLY for items actually received in good condition. Note any rejected items on the delivery note. Retain copy of signed delivery note |
| Timeframe | At delivery |
| Output | Signed delivery note (supplier retains original; Awdeer retains copy) |

#### Step 7: Store Goods and Update Records

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Move received goods to appropriate storage location. Update stock records/inventory ledger. Label items if required (date received, PO number) |
| Timeframe | Same day as receipt |
| Output | Goods stored; stock records updated |

#### Step 8: Notify Requester and Forward Documents

| Detail | Description |
|--------|-------------|
| Actor | Operations Manager |
| Action | Notify requester that goods have arrived (email or verbal). Forward GRN + copy of delivery note + PO copy to Finance Manager for three-way match |
| Timeframe | Within 1 business day of receipt |
| Output | Requester notified; Finance has GRN document pack |

### 5.2 Goods Receipt — Controlled Version

#### Step 1: Pre-Delivery Preparation

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer |
| Action | Review open PO schedule in ERP for expected deliveries. Prepare receiving bay/area. Print PO summary for reference during inspection. Coordinate with security for supplier access (if applicable) |
| Timeframe | Daily review of expected deliveries |
| Output | Daily receiving schedule; prepared area |

#### Step 2: Receive Supplier and Verify Documentation

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer |
| Action | Verify supplier identification. Collect delivery note, packing list, and any certificates. Cross-reference delivery note with open PO in ERP. Log arrival in Delivery Log Book (date, time, supplier, PO reference) |
| Timeframe | At delivery |
| Output | Delivery logged; documentation collected |
| Key rule | No goods to be unloaded until PO verified in system |

#### Step 3: Unload and Physical Count

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer |
| Action | Supervise unloading to designated inspection area (NOT directly to storage). Perform detailed count of all items. Compare quantities against PO and delivery note. Record count on Receiving Inspection Checklist |
| Timeframe | At delivery |
| Output | Physical count completed |
| Key rule | Goods remain in inspection area until GRN is completed and quality check is passed |

#### Step 4: Quality Inspection

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer + Technical reviewer (if required) |
| Action | Inspect goods against PO specifications: dimensions, weight, colour, grade, model numbers, expiry dates (if applicable), certificates of conformity. For technical items: request Department Head or technical specialist to verify. Record all findings on Quality Inspection section of GRN |
| Timeframe | Within 4 hours for standard items; within 2 business days for technical items |
| Output | Quality inspection completed and recorded |
| Key rule | Items failing quality inspection are quarantined — not moved to storage |

#### Step 5: Record GRN in ERP

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer |
| Action | Create GRN in ERP against the PO: system auto-populates PO details. Enter actual quantities received per line item. Record condition (accepted/rejected/pending) per line item. Attach scanned delivery note and any inspection reports. System automatically updates stock levels for accepted items |
| Timeframe | Same day as receipt |
| Output | System-generated GRN number; stock updated |
| Key rule | GRN triggers automatic notification to Finance/AP for invoice matching |

#### Step 6: Handle Discrepancies

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer (reports) / Procurement Manager (acts) |
| Action | For discrepancies: Stores Officer records in ERP Discrepancy Report. Procurement Manager contacts supplier within 1 business day. Options: accept short delivery (amend PO), arrange re-delivery, reject and return, negotiate credit note |
| Timeframe | Immediate recording; resolution within 5 business days |
| Output | Discrepancy resolved; ERP updated |
| Key rule | Discrepancies exceeding 5% of PO value require MD notification |

#### Step 7: Process Returns (if applicable)

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer + Procurement Manager |
| Action | Issue Return to Supplier Note (debit note). Pack rejected goods securely. Arrange collection or delivery back to supplier. Record return in ERP. Follow up on replacement or credit note |
| Timeframe | Within 3 business days of rejection |
| Output | Return to Supplier Note; goods returned; credit note received |

#### Step 8: Move to Storage and Update Records

| Detail | Description |
|--------|-------------|
| Actor | Stores Officer |
| Action | Move accepted goods from inspection area to designated storage location. Update bin/location records in ERP. Apply inventory labels (item code, date received, PO number, batch/lot if applicable) |
| Timeframe | Same day as GRN completion |
| Output | Goods in correct storage; ERP location updated |

#### Step 9: Notify Stakeholders

| Detail | Description |
|--------|-------------|
| Actor | ERP System / Stores Officer |
| Action | ERP auto-notifies: Requesting department (goods available for use), AP Officer (GRN ready for invoice matching), Procurement Officer (delivery recorded against PO). Stores Officer follows up verbally for urgent items |
| Timeframe | Automatic on GRN entry |
| Output | All stakeholders notified |

### 5.3 Service Acceptance — Both Versions

#### Step 1: Supplier Notifies Completion

| Detail | Description |
|--------|-------------|
| Actor | Supplier |
| Action | Supplier formally notifies that service is complete (or milestone achieved). Submits completion report/deliverables as per contract |
| Timeframe | Per contract/PO schedule |
| Output | Completion notification and deliverables |

#### Step 2: Verify Deliverables

| Detail | Description |
|--------|-------------|
| Actor | Requesting Department Head (both versions); Technical reviewer (Controlled — for Tier 3+) |
| Action | Review all deliverables against PO/Contract scope. Verify quality and completeness. Test/inspect output (as applicable). Document findings |
| Timeframe | Within 3 business days of notification (Lean); within 5 business days (Controlled) |
| Output | Deliverables verified |

#### Step 3: Issue Service Acceptance Certificate or Deficiency Notice

| Detail | Description |
|--------|-------------|
| Actor | Department Head |
| Action | If satisfactory: Complete and sign Service Acceptance Certificate. If deficient: Issue Deficiency Notice to supplier specifying corrections required and timeline |
| Timeframe | Within 1 business day of verification |
| Output | Signed Service Acceptance Certificate OR Deficiency Notice |
| Key rule | Partial acceptance is permitted — certificate notes what is accepted and what remains outstanding |

#### Step 4: Forward to Finance

| Detail | Description |
|--------|-------------|
| Actor | Department Head (Lean) / System (Controlled) |
| Action | Forward Service Acceptance Certificate + PO copy to Finance for invoice matching. In Controlled version, certificate is recorded in ERP and auto-routed |
| Timeframe | Within 1 business day |
| Output | Finance has acceptance documentation |

---

## 6. Controls and Approvals

| Control | Description | Version |
|---------|-------------|---------|
| PO-based receiving | No goods accepted without a valid, approved PO | Both |
| Segregation of duties | Person ordering (Procurement) is different from person receiving (Stores/OM) | Both |
| Inspection before acceptance | All goods inspected before signing delivery note | Both |
| GRN sequencing | GRN numbers are sequential and unique — no gaps | Both |
| Discrepancy threshold | Discrepancies above 5% of PO value escalated to MD | Both |
| Quarantine controls | Non-conforming goods quarantined, not mixed with accepted stock | Controlled |
| System controls | GRN must reference valid open PO in ERP | Controlled |
| Blind receiving option | Stores Officer can receive without seeing PO quantities (forces independent count) | Controlled |
| Service acceptance authority | Only requesting Department Head can accept services | Both |
| Return documentation | All returns documented with supplier acknowledgment | Both |
| Photograph evidence | Damaged/deficient goods photographed for evidence | Both |

---

## 7. Documents and Forms

| Document | Template Code | Purpose |
|----------|--------------|---------|
| Goods Received Note | PRO-TPL-005 | Record receipt of physical goods |
| Purchase Order (reference) | PRO-TPL-004 | Verify delivery against order |
| Service Acceptance Certificate | Embedded in SOP | Confirm satisfactory service completion |
| Discrepancy Report | ERP-generated / manual note | Record delivery discrepancies |
| Return to Supplier Note | Debit note format | Document returned goods |
| Delivery Log Book | Physical register | Log all deliveries received |

### Service Acceptance Certificate Format

| Field | Detail |
|-------|--------|
| Certificate number | SAC-[YYYY]-[NNN] |
| Date | Date of acceptance |
| PO / Contract reference | PO number or contract number |
| Supplier name | Legal name of supplier |
| Description of services | Brief description of services rendered |
| Deliverables received | List of all deliverables |
| Acceptance status | Full acceptance / Partial acceptance / Rejected |
| Deficiencies noted | List any outstanding items |
| Accepted by | Department Head name and signature |
| Date accepted | Date of sign-off |
| Witnessed by | Operations Manager / Procurement Manager |

---

## 8. Key Performance Indicators

| KPI | Target | Measurement Method | Frequency |
|-----|--------|-------------------|-----------|
| GRN completion within same day | ≥ 95% | GRNs completed same day as delivery / total deliveries | Monthly |
| Inspection accuracy | ≥ 98% | Post-receipt issues discovered / total GRNs | Monthly |
| Discrepancy rate | ≤ 5% of deliveries | Deliveries with discrepancies / total deliveries | Monthly |
| Return-to-supplier rate | ≤ 2% of deliveries | Returns / total deliveries | Monthly |
| Service acceptance turnaround | ≤ 5 BD from completion notice | Average days from completion notice to certificate | Monthly |
| GRN-to-Finance forwarding time | ≤ 1 BD | Average days from GRN to Finance receipt | Monthly |
| Document completeness | 100% | GRNs with all required fields completed / total GRNs | Monthly |
| Stock record accuracy | ≥ 98% | Matching physical count vs system records post-GRN | Quarterly |

---

## 9. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | February 2026 | System Design | Initial version |

---

*Awdeer Investments Limited*
*SOP: PRO-RCV-001 — Goods Receipt and Service Acceptance*
*Version 1.0 — February 2026*
