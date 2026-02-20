# INV-ISS-001 — Stock Issuing SOP

## Document Control

| Field | Detail |
|-------|--------|
| Document ID | INV-ISS-001 |
| Title | Stock Issuing Standard Operating Procedure |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Stores/Inventory Officer |
| Approved By | Operations Manager |
| Review Cycle | Annually or after significant process change |

---

## 1. Purpose

To establish a standardized procedure for issuing stock from Awdeer Investments Limited stores to authorized internal requesters, ensuring proper authorization, accurate record-keeping, correct cost allocation, and prevention of unauthorized withdrawals.

---

## 2. Scope

This SOP applies to:

- All issues of stock from any Awdeer Investments Limited store or warehouse
- All categories: raw materials, consumables, spare parts, finished goods, fuel, PPE
- All internal departments and projects requesting stock
- Both routine and emergency/urgent issues

This SOP does **not** cover:

- Dispatch of goods to external customers (covered under INV-DSP-001)
- Transfer of stock between locations (covered under INV-TRF-001)
- Return of goods to suppliers (covered under INV-RCV-001)

---

## 3. RACI Matrix

### 3.1 Lean Version

| Activity | Requester | Stores Assistant | Operations Manager | Finance |
|----------|:---:|:---:|:---:|:---:|
| Raise Stores Request Form | R | I | I | — |
| Approve request | — | A (C items ≤500K) | R/A (all others) | — |
| Check stock availability | — | R/A | I | — |
| Pick items from storage | — | R/A | — | — |
| Verify items and sign | R | R | — | — |
| Update stock card / system | — | R/A | I | I |
| File documentation | — | R | I | I |
| Weekly summary to Finance | — | R | I | R/A |

### 3.2 Controlled Version

| Activity | Requester | Dept Head | Stores Asst | Stores/Inv. Officer | Ops Manager | Finance |
|----------|:---:|:---:|:---:|:---:|:---:|:---:|
| Raise Stores Request (ERP/form) | R | I | I | I | — | — |
| Departmental approval | I | R/A | — | — | — | — |
| Budget check | — | C | — | C | — | R |
| Validate stock availability | — | — | C | R/A | — | — |
| Approve issue (Class B/C) | — | — | — | R/A | I | — |
| Approve issue (Class A) | — | — | — | C | R/A | I |
| Pick items from bin | — | — | R | A | — | — |
| Verify items received | R | — | C | I | — | — |
| Record issue in system | — | — | C | R/A | I | I |
| Cost allocation to dept/project | — | — | — | R | A | R/A |
| Daily issue summary | — | — | — | R | I | I |
| Monthly issue report | — | — | — | R | A | R/A |

**Legend:** R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## 4. Inputs & Outputs

### 4.1 Inputs

| Input | Source | Purpose |
|-------|--------|---------|
| Stores Request / Issue Form (INV-TPL-002) | Requester | Formal request for stock |
| Approved budget / project allocation | Finance / Department Head | Confirms funds available |
| Stock card / bin card (current balance) | Stores | Confirms stock availability |
| Item master data (ERP) | System | Item details, bin location, cost |
| Approval per Delegation of Authority | Approver | Authorization to issue |

### 4.2 Outputs

| Output | Destination | Purpose |
|--------|-------------|---------|
| Completed Stores Request / Issue Form | Stores file, Finance | Record of issue |
| Updated stock card / bin card | Stores | Adjusted balance |
| Updated ERP inventory record | System | Real-time stock visibility |
| Cost allocation entry | Finance / ERP | Charge to correct department/project |
| Daily / weekly issue summary | Operations Manager, Finance | Management visibility |

---

## 5. Step-by-Step Workflow

### 5.1 Lean Version (Small Team < 15 People)

#### Step 1: Raise Request

- Requester completes Stores Request / Issue Form (INV-TPL-002) — paper or digital
- Form must include: date, requester name, department, item description, quantity requested, purpose/project reference

#### Step 2: Approval

- **Class C items up to UGX 500,000:** Stores Assistant may approve and issue directly
- **All other items:** Operations Manager reviews and approves the request
- Unapproved requests are not processed; returned to requester with reason

#### Step 3: Stock Availability Check

- Stores Assistant checks stock card / bin card for available quantity
- If stock is insufficient: notify requester; issue partial quantity if agreed; raise reorder alert to Operations Manager

#### Step 4: Picking

- Stores Assistant locates items in storage area
- Picks exact quantity from designated bin location
- Follows FIFO/FEFO: oldest stock issued first

#### Step 5: Handover and Verification

- Requester physically verifies items: correct item, correct quantity, acceptable condition
- Both Stores Assistant and Requester sign the Stores Request / Issue Form
- Date and time of issue recorded

#### Step 6: Record Update

- Stores Assistant updates stock card / bin card: date, issue reference, quantity out, new balance
- Form filed in stores issue file (chronological)

#### Step 7: Weekly Reporting

- Stores Assistant prepares weekly issue summary: items issued, quantities, requesting departments
- Summary forwarded to Operations Manager and Finance by Monday for preceding week
- Finance uses summary for cost allocation entries

### 5.2 Controlled Version (Mid-Size Team 15–100+ People)

#### Step 1: Raise Request in System

- Requester submits Stores Request / Issue Form via ERP system or approved manual form
- Required fields: date, requester name and employee ID, department, cost centre/project code, item code and description, quantity requested, unit of measure, purpose/justification
- System auto-checks: is the item in the catalogue? Is there a cost centre?

#### Step 2: Departmental Approval

- Request routed to Department Head for approval
- Department Head confirms: legitimate business need, correct cost centre, within departmental budget
- Department Head approves or rejects with reason

#### Step 3: Budget Verification (For Material Requests)

- For requests above UGX 2,000,000: Finance confirms budget availability before stores processes
- System-enforced budget check preferred; manual check acceptable as interim

#### Step 4: Stores Validation

- Stores/Inventory Officer receives approved request
- Verifies stock availability in system
- If insufficient stock: notifies requester of options (partial issue, alternative item, reorder timeline)
- If alternative item proposed: requester and Department Head must re-approve

#### Step 5: Approval by Stores Authority

- **Class B and C items:** Stores/Inventory Officer approves issue
- **Class A items (high value):** Operations Manager co-approval required
- **Items above UGX 10,000,000:** Managing Director approval required
- Critical spares: Operations Manager approval always required regardless of value

#### Step 6: Picking

- Stores Assistant receives approved pick instruction
- Picks items from designated bin location
- Follows FIFO/FEFO (First In First Out / First Expiry First Out)
- Records bin location picked from on the issue form
- For large or complex picks: uses pick list generated by system

#### Step 7: Verification and Handover

- Requester inspects items at issuing counter: correct item, quantity, condition
- Requester signs issue form / confirms receipt in system
- Stores Assistant signs as issuer
- For high-value items: Stores/Inventory Officer witnesses handover

#### Step 8: System Update

- Stores/Inventory Officer records issue in ERP system:
  - Item code, description, quantity issued
  - Issuing store and bin location
  - Requester and department
  - Cost centre / project code
  - Date and time
- System automatically: decrements stock balance, calculates cost at Weighted Average Cost, posts cost allocation to department/project
- Bin card at shelf level updated by Stores Assistant

#### Step 9: Daily Summary

- Stores/Inventory Officer generates daily issue summary from system
- Reviewed by Operations Manager next morning
- Exceptions (high-value, unusual quantity, out-of-stock) highlighted

#### Step 10: Monthly Reporting

- Monthly issue report prepared: total issues by department, by item category, by value
- Compared to budget allocations
- Overruns flagged to Operations Manager and Finance Manager
- Report supports cost of goods / departmental expense analysis

---

## 6. Controls & Approvals

| Control | Description | Version |
|---------|-------------|---------|
| No form, no issue | Stock cannot be issued without an approved Stores Request Form | Both |
| Approval thresholds enforced | Issues approved per Delegation of Authority thresholds | Both |
| FIFO/FEFO compliance | Oldest stock issued first; expiry-date items by earliest expiry | Both |
| Segregation of duties | Requester cannot self-approve; issuer cannot be the requester | Both |
| Dual signature | Both issuer and receiver sign the issue form | Both |
| Same-day recording | Issues recorded in system/stock card on the day of physical issue | Both |
| Class A co-approval | High-value items require Operations Manager co-approval | Controlled |
| Budget check | Material requests above threshold verified against budget | Controlled |
| No verbal issues | All issues require written/system request; no verbal-only requests | Both |
| Witness for high-value | Stores/Inventory Officer witnesses handover of Class A items | Controlled |
| Daily reconciliation | Stores/Inventory Officer reconciles physical issues to system entries daily | Controlled |

### Approval Thresholds (ASSUMPTION — Align with Delegation of Authority)

| Value Band (UGX) | Lean Approver | Controlled Approver |
|-------------------|--------------|---------------------|
| Up to 500,000 | Stores Assistant (C items only) | Stores/Inventory Officer |
| 500,001 – 2,000,000 | Operations Manager | Department Head |
| 2,000,001 – 10,000,000 | Operations Manager | Operations Manager |
| Above 10,000,000 | Managing Director | Managing Director |

---

## 7. Documents & Forms

| Document | Template Reference | Purpose |
|----------|--------------------|---------|
| Stores Request / Issue Form | INV-TPL-002 | Primary request and issue record |
| Stock Card / Bin Card | INV-TPL-001 | Item-level balance tracker |
| Pick List | ERP-generated | Guides Stores Assistant for complex picks |
| Daily Issue Summary | ERP report or manual summary | Management review |
| Monthly Issue Report | ERP report or manual summary | Cost analysis and budget comparison |

---

## 8. KPIs

| KPI | Formula | Target | Measurement Frequency |
|-----|---------|--------|-----------------------|
| Order Fill Rate | (Requisitions fully filled / Total requisitions) x 100 | > 95% | Monthly |
| Issue Accuracy | (Issues without errors / Total issues) x 100 | > 99% | Monthly |
| Request-to-Issue Time | Average time from approved request to physical handover | < 2 hours (routine) | Weekly |
| Unauthorized Issue Rate | Unauthorized issues discovered / Total issues | 0% | Monthly (audit) |
| FIFO Compliance | (Issues following FIFO / Total issues) x 100 | 100% | Monthly (spot check) |
| Stockout Rate | (Stockout incidents / Total requests) x 100 | < 2% | Monthly |
| Cost Allocation Accuracy | (Issues with correct cost centre / Total issues) x 100 | 100% | Monthly |
| Same-Day Recording | (Issues recorded same day / Total issues) x 100 | 100% | Weekly |

---

## 9. Special Scenarios

### 9.1 Emergency / Urgent Issues

- Requester verbally requests from Operations Manager (Lean) or Stores/Inventory Officer (Controlled)
- Verbal approval granted by Operations Manager
- Stock issued immediately
- **Stores Request Form must be completed and signed within 24 hours**
- Emergency issues tracked separately; monthly report on frequency and causes

### 9.2 Partial Issues

- If requested quantity not fully available, Stores may issue partial quantity with requester agreement
- Stores Request Form marked "PARTIAL ISSUE" with quantity issued and backorder quantity
- Backorder tracked and fulfilled when stock arrives
- Requester notified when backorder stock is available

### 9.3 Returns to Store

- If requester returns unused stock to stores:
  - Items must be in original condition, unopened/unused
  - Stores/Inventory Officer inspects and accepts or rejects
  - Return entry made on Stores Request Form (negative issue) or separate return form
  - Stock card credited; system updated
  - Cost centre credited for returned value

---

## 10. Process Flowchart (Text)

```
START
  │
  ├─► Requester completes Stores Request Form
  │
  ├─► Approval obtained? ──► NO ──► Return to requester ──► END
  │         │
  │        YES
  │         │
  ├─► Stock available? ──► NO ──► Notify requester; partial issue or reorder
  │         │
  │        YES
  │         │
  ├─► Class A item? ──► YES ──► Operations Manager co-approval
  │         │
  │        NO (or approved)
  │         │
  ├─► Stores Assistant picks items (FIFO/FEFO)
  │
  ├─► Requester verifies items
  │
  ├─► Both parties sign issue form
  │
  ├─► System / stock card updated (same day)
  │
  ├─► Cost allocated to department / project
  │
  └─► END
```

---

## 11. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | February 2026 | Operations Manager | Initial release |

---

*Awdeer Investments Limited — INV-ISS-001 Stock Issuing SOP*
*Version 1.0 — February 2026*
