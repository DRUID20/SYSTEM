# Awdeer Investments Limited — Part E: Inventory, Stores & Logistics

## Document Control

| Field | Detail |
|-------|--------|
| Document ID | INV-SYS-001 |
| Title | Inventory, Stores & Logistics System |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Operations Manager / Stores & Inventory Officer |
| Approved By | Managing Director |
| Classification | Internal — All Staff (Stores, Logistics, Operations) |

---

## Table of Contents

1. [Purpose & Scope](#1-purpose--scope)
2. [Stores Structure & Roles](#2-stores-structure--roles)
3. [Inventory Classification](#3-inventory-classification)
4. [Stock Receiving](#4-stock-receiving)
5. [Stock Issuing](#5-stock-issuing)
6. [Stock Transfers Between Locations](#6-stock-transfers-between-locations)
7. [Stock Count Procedures](#7-stock-count-procedures)
8. [Inventory Valuation Method](#8-inventory-valuation-method)
9. [Shrinkage Investigation](#9-shrinkage-investigation)
10. [Warehousing & Dispatch](#10-warehousing--dispatch)
11. [Fleet & Logistics Controls](#11-fleet--logistics-controls)
12. [RACI Summary](#12-raci-summary)
13. [SOP Index](#13-sop-index)
14. [Templates Index](#14-templates-index)
15. [KPIs & Reporting](#15-kpis--reporting)
16. [Questions & Assumptions](#16-questions--assumptions)

---

## 1. Purpose & Scope

### 1.1 Purpose

This document establishes the complete Inventory, Stores & Logistics management framework for Awdeer Investments Limited. It governs how physical goods are received, stored, issued, counted, transferred, valued, and dispatched. It also covers fleet and logistics controls for vehicle-based operations.

### 1.2 Scope

This section applies to:

- All warehouses, stores, and storage locations operated by Awdeer Investments Limited
- All stock items: raw materials, finished goods, consumables, spare parts, fuel stocks
- All vehicles and fleet assets used for business logistics
- All staff involved in stores, warehousing, dispatch, and fleet operations

### 1.3 Governing Principles

| Principle | Application |
|-----------|-------------|
| Segregation of Duties | Requester, approver, issuer, and receiver are different persons |
| Audit Trail | Every stock movement is documented with date, quantity, authorizer, and reason |
| Physical-to-System Match | Physical stock must reconcile to system records at all times |
| Valuation Accuracy | Weighted Average Cost method applied consistently (ASSUMPTION) |
| Custodial Accountability | Named custodians for every store/warehouse location |
| Minimize Shrinkage | Proactive controls, regular counts, and investigation protocols |
| Fleet Discipline | Every trip authorized, every litre accounted for, every vehicle maintained |

---

## 2. Stores Structure & Roles

### 2.1 Store Types

| Store Type | Description | Examples |
|------------|-------------|----------|
| Main Store | Central warehouse holding bulk inventory | HQ warehouse |
| Sub-Store | Satellite storage at branch or site level | Branch stores, site containers |
| Bonded Store | Secured area for high-value or restricted items | Fuel depot, chemical stores |
| Transit Store | Temporary holding for goods in transfer | Loading bay, dispatch area |
| Quarantine Area | Holding for damaged, expired, or disputed goods | Returns area, QC hold zone |

### 2.2 Roles — Lean Version

| Role | Responsibilities |
|------|-----------------|
| Operations Manager | Overall stores oversight; approves requisitions above threshold; signs off on stock counts |
| Stores Assistant (1–2) | Receives goods, issues stock, updates stock cards, performs spot checks, manages dispatch |
| Managing Director | Approves high-value movements; reviews shrinkage reports |

### 2.3 Roles — Controlled Version

| Role | Responsibilities |
|------|-----------------|
| Operations Manager | Strategic oversight of all stores and logistics; exception approvals |
| Stores/Inventory Officer | Day-to-day stores management; stock accuracy; coordinates counts; vendor receipt verification |
| Stores Assistant(s) | Physical receiving, issuing, shelving, labelling; updates bin cards |
| Logistics Coordinator | Fleet management; dispatch scheduling; route planning; driver supervision |
| Driver(s) | Vehicle operation; delivery execution; vehicle daily checks; logbook maintenance |
| Procurement Manager | Coordinates with stores on PO deliveries; supplier returns |
| Finance Manager / Accountant | Inventory valuation; cost reconciliation; shrinkage write-off approval |
| Internal Auditor | Independent stock count verification; shrinkage investigation; controls testing |

### 2.4 Store Layout Standards

Every store location must have:

1. **Clearly labelled zones** — Receiving Bay, Storage Racks/Shelves, Issuing Counter, Dispatch Bay, Quarantine Area
2. **Bin/Location coding** — Format: `[Store]-[Aisle]-[Rack]-[Shelf]` (e.g., `MS-A-03-02` = Main Store, Aisle A, Rack 3, Shelf 2)
3. **Access control** — Only authorized stores personnel may enter storage areas
4. **Safety equipment** — Fire extinguishers, first aid kit, PPE as required by item type
5. **Signage** — No smoking, restricted access, hazardous material warnings where applicable

---

## 3. Inventory Classification

### 3.1 ABC Analysis

Inventory is classified by annual consumption value to prioritize management effort.

| Class | % of Items | % of Value | Control Level | Count Frequency |
|-------|-----------|------------|---------------|-----------------|
| A — High Value | ~10–20% | ~70–80% | Tight: daily monitoring, precise records, senior approval for issue | Monthly cycle count minimum |
| B — Medium Value | ~20–30% | ~15–20% | Moderate: weekly review, standard approval for issue | Quarterly cycle count minimum |
| C — Low Value | ~50–70% | ~5–10% | Basic: periodic review, simplified issue process | Semi-annual count minimum |

### 3.2 Movement Classification

| Category | Definition | Action |
|----------|-----------|--------|
| Fast Movers | Items consumed/sold within 30 days of receipt | Maintain buffer stock; reorder point set; prioritize storage access |
| Medium Movers | Items consumed/sold within 31–90 days | Standard reorder cycle; monitor for trend changes |
| Slow Movers | Items not consumed/sold within 90+ days | Review quarterly; consider disposal, return, or markdown |
| Dead Stock | No movement for 180+ days | Flag for write-off/disposal committee review |

### 3.3 Critical Spares

Items classified as critical spares receive special treatment regardless of ABC class:

| Attribute | Requirement |
|-----------|-------------|
| Identification | Tagged as "CRITICAL SPARE" in system and on bin card |
| Minimum Stock | Mandatory minimum stock level maintained at all times |
| Reorder Trigger | Automatic reorder when stock hits minimum; no waiting for periodic review |
| Issuing Authority | Operations Manager approval required (both Lean and Controlled) |
| Substitution | No substitution without engineering/technical sign-off |
| Storage | Dedicated, climate-appropriate storage where required |

### 3.4 Classification Review

- ABC classification recalculated **quarterly** based on trailing 12-month consumption data
- Movement classification reviewed **monthly**
- Critical spares list reviewed **quarterly** by Operations Manager with technical input

---

## 4. Stock Receiving

> **Full SOP:** [`INV-RCV-001-stock-receiving.md`](sops/INV-RCV-001-stock-receiving.md)

### 4.1 Process Overview

```
Supplier Delivery → Gate Check → Receiving Bay → Quantity/Quality Inspection
    → GRN Issued → System Update → Bin Allocation → Supplier Invoice Match
```

### 4.2 Lean Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Supplier arrives; Stores Assistant checks delivery against PO copy | Stores Assistant |
| 2 | Count items, check quality visually, note any damage | Stores Assistant |
| 3 | Complete Goods Received Note (GRN) — sign and date | Stores Assistant |
| 4 | Update stock card / bin card | Stores Assistant |
| 5 | Forward GRN + delivery note to Operations Manager for review | Stores Assistant |
| 6 | Operations Manager spot-checks and files with Finance | Operations Manager |

### 4.3 Controlled Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Supplier arrives at gate; security logs vehicle and delivery details | Security |
| 2 | Stores Assistant checks delivery note against approved PO | Stores Assistant |
| 3 | Stores/Inventory Officer inspects quantity and quality; specialist QC for technical items | Stores/Inventory Officer |
| 4 | Any variance or damage noted on GRN; photos taken for evidence | Stores/Inventory Officer |
| 5 | GRN issued in triplicate: Store copy, Finance copy, Supplier copy | Stores/Inventory Officer |
| 6 | System updated (ERP goods receipt); bin location assigned | Stores/Inventory Officer |
| 7 | Stock card / bin card updated at shelf level | Stores Assistant |
| 8 | GRN sent to Finance for three-way match (PO, GRN, Invoice) | Stores/Inventory Officer |
| 9 | Damaged/rejected goods moved to Quarantine Area; supplier notified | Stores/Inventory Officer |

### 4.4 RACI — Stock Receiving

| Activity | Stores Assistant | Stores/Inv. Officer | Ops Manager | Finance | Procurement |
|----------|:---:|:---:|:---:|:---:|:---:|
| Physical receipt & count | R | A | I | I | I |
| Quality inspection | R | R/A | I | — | C |
| GRN creation | R | A | I | I | I |
| System update | R | R/A | I | I | — |
| Three-way match | I | C | I | R/A | C |
| Quarantine handling | R | R/A | A | I | R |

### 4.5 Key Controls

- No receipt without a valid, approved Purchase Order
- GRN must be issued on the same day as physical receipt
- Variances exceeding 5% (quantity) or any quality defect require immediate escalation
- Supplier delivery note must be retained with GRN
- Backdated GRNs are prohibited

---

## 5. Stock Issuing

> **Full SOP:** [`INV-ISS-001-stock-issuing.md`](sops/INV-ISS-001-stock-issuing.md)

### 5.1 Process Overview

```
Stores Request Form → Approval → Stores Picks Items → Requester Verifies
    → Issue Recorded → Stock Card Updated → System Updated
```

### 5.2 Lean Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Requester completes Stores Request Form (paper or digital) | Requester |
| 2 | Operations Manager approves (or Stores Assistant for low-value C items) | Operations Manager |
| 3 | Stores Assistant picks items and hands to requester | Stores Assistant |
| 4 | Both sign the issue form; stock card updated | Stores Assistant / Requester |
| 5 | Weekly summary sent to Finance | Stores Assistant |

### 5.3 Controlled Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Requester submits Stores Request Form via ERP or approved form | Requester |
| 2 | Department Head approves request | Department Head |
| 3 | Stores/Inventory Officer validates against stock availability and budget allocation | Stores/Inventory Officer |
| 4 | Stores Assistant picks items from designated bin location | Stores Assistant |
| 5 | Requester verifies items received and signs | Requester |
| 6 | Stores/Inventory Officer records issue in system; stock card updated | Stores/Inventory Officer |
| 7 | For Class A items: Operations Manager co-signs | Operations Manager |
| 8 | Daily issue summary posted to ERP; cost allocation to department/project | Stores/Inventory Officer |

### 5.4 RACI — Stock Issuing

| Activity | Requester | Dept Head | Stores Asst | Stores/Inv. Officer | Ops Manager |
|----------|:---:|:---:|:---:|:---:|:---:|
| Raise request | R | I | I | I | I |
| Approve request | — | R/A | — | C | A (high value) |
| Pick items | — | — | R | A | — |
| Verify receipt | R | — | C | I | — |
| Record issue | — | — | R | R/A | I |
| Cost allocation | — | — | — | R | A |

### 5.5 Approval Thresholds (ASSUMPTION)

| Value Band (UGX) | Lean Approver | Controlled Approver |
|-------------------|--------------|---------------------|
| Up to 500,000 | Stores Assistant (self-approve for C items) | Stores/Inventory Officer |
| 500,001 – 2,000,000 | Operations Manager | Department Head |
| 2,000,001 – 10,000,000 | Operations Manager | Operations Manager |
| Above 10,000,000 | Managing Director | Managing Director |

---

## 6. Stock Transfers Between Locations

> **Full SOP:** [`INV-TRF-001-stock-transfers.md`](sops/INV-TRF-001-stock-transfers.md)

### 6.1 Process Overview

```
Transfer Request → Approval → Sending Store Prepares → Stock Transfer Note Issued
    → Physical Transfer → Receiving Store Inspects & Confirms → Both Systems Updated
```

### 6.2 Lean Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Requesting location submits transfer request to Operations Manager | Requester |
| 2 | Operations Manager approves and notifies sending store | Operations Manager |
| 3 | Sending store prepares items and completes Stock Transfer Note (STN) | Stores Assistant (Sending) |
| 4 | Items physically moved; receiving store checks and signs STN | Stores Assistant (Receiving) |
| 5 | Both stores update stock cards; copies to Finance | Both Stores Assistants |

### 6.3 Controlled Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Requesting location raises transfer request in ERP | Requesting Stores Officer |
| 2 | Sending location's Stores/Inventory Officer confirms availability | Stores/Inventory Officer (Sending) |
| 3 | Operations Manager approves transfer | Operations Manager |
| 4 | Sending store picks, packs, and issues STN in triplicate | Stores/Inventory Officer (Sending) |
| 5 | Logistics Coordinator arranges transport; Trip Authorization issued if using company vehicle | Logistics Coordinator |
| 6 | Goods dispatched with STN; sending store decrements stock | Stores/Inventory Officer (Sending) |
| 7 | Receiving store inspects goods against STN | Stores/Inventory Officer (Receiving) |
| 8 | Receiving store signs STN and increments stock in system | Stores/Inventory Officer (Receiving) |
| 9 | Any variance noted and escalated to Operations Manager | Stores/Inventory Officer (Receiving) |
| 10 | Finance receives confirmed STN copies for cost reallocation | Finance |

### 6.4 RACI — Stock Transfers

| Activity | Requesting Store | Sending Store | Ops Manager | Logistics | Finance |
|----------|:---:|:---:|:---:|:---:|:---:|
| Raise transfer request | R | I | A | I | I |
| Confirm stock availability | I | R | I | — | — |
| Approve transfer | I | I | R/A | I | I |
| Pick, pack, issue STN | — | R | I | I | — |
| Arrange transport | — | C | I | R | — |
| Receive and inspect | R | — | I | I | — |
| System update (both ends) | R | R | I | — | I |
| Cost reallocation | — | — | A | — | R |

---

## 7. Stock Count Procedures

> **Full SOP:** [`INV-CNT-001-stock-counting.md`](sops/INV-CNT-001-stock-counting.md)

### 7.1 Count Types

| Count Type | Frequency | Scope | Led By | Duration |
|-----------|-----------|-------|--------|----------|
| Daily Spot Check | Daily | 5–10 high-value/high-risk SKUs selected randomly | Stores Assistant / Stores Officer | 15–30 minutes |
| Monthly Cycle Count | Monthly | Subset of SKUs per ABC rotation: all A items monthly, B items quarterly, C items semi-annually | Stores/Inventory Officer | 2–4 hours |
| Quarterly Full Count | Quarterly | 100% of all SKUs across all locations | Operations Manager + Finance + Internal Auditor | Full day (operations paused) |

### 7.2 Lean Version

| Count Type | Process |
|-----------|---------|
| Daily Spot Check | Stores Assistant counts 5 random items at start of day; records on spot check log; flags variances to Operations Manager |
| Monthly Cycle Count | Operations Manager selects items for count; Stores Assistant counts; Operations Manager verifies sample of 20%; variances investigated |
| Quarterly Full Count | All stock counted over a weekend; Operations Manager leads; Finance observes; results reconciled within 3 business days |

### 7.3 Controlled Version

| Count Type | Process |
|-----------|---------|
| Daily Spot Check | Stores/Inventory Officer selects 5–10 items (system-generated random list preferred); Stores Assistant counts independently; Officer verifies; variances >2% investigated same day |
| Monthly Cycle Count | System generates count list by ABC class; two-person blind count (counter + checker); Stores/Inventory Officer reconciles to system; Operations Manager reviews variance report; all variances >1% investigated and documented |
| Quarterly Full Count | Pre-count: all movements frozen; count teams assigned (no one counts their own area); Independent counter + checker per zone; Internal Auditor observes and test-counts 10% of items; Finance verifies valuation; Variance Investigation Form completed for all differences; Operations Manager and Finance Manager sign off; adjustments posted after MD approval for write-offs above threshold |

### 7.4 RACI — Stock Counting

| Activity | Stores Asst | Stores/Inv. Officer | Ops Manager | Finance | Internal Auditor | MD |
|----------|:---:|:---:|:---:|:---:|:---:|:---:|
| Daily spot check | R | A | I | — | — | — |
| Monthly cycle count | R | R/A | A | I | I | — |
| Quarterly full count | R | R | A | R (observe) | R (observe) | A (write-off) |
| Variance investigation | C | R | A | C | R | A (>threshold) |
| System adjustment | — | R | A | R/A | I | A (>threshold) |

### 7.5 Variance Thresholds & Escalation

| Variance Level | Action | Authority |
|----------------|--------|-----------|
| Within 1% (by value) | Adjust after Stores/Inventory Officer approval | Stores/Inventory Officer |
| 1.01% – 3% | Investigate; Operations Manager approves adjustment | Operations Manager |
| 3.01% – 5% | Formal investigation; Finance Manager + Operations Manager approve | Finance Manager |
| Above 5% | Full investigation; MD approval for adjustment; Internal Audit notified | Managing Director |

---

## 8. Inventory Valuation Method

### 8.1 Method: Weighted Average Cost (ASSUMPTION)

Awdeer Investments Limited uses the **Weighted Average Cost** method for inventory valuation. This is consistent with IAS 2 (Inventories) and accepted by the Uganda Revenue Authority.

### 8.2 How It Works

```
New Weighted Average Cost = (Existing Stock Value + New Purchase Value) / (Existing Quantity + New Quantity)
```

**Example:**

| Event | Quantity | Unit Cost (UGX) | Total Value (UGX) | Weighted Avg Cost (UGX) |
|-------|---------|-----------------|-------------------|------------------------|
| Opening balance | 100 | 5,000 | 500,000 | 5,000 |
| Purchase received | 50 | 6,000 | 300,000 | — |
| **New balance** | **150** | — | **800,000** | **5,333** |
| Issue 30 units | -30 | 5,333 | -160,000 | 5,333 |
| **Closing balance** | **120** | — | **640,000** | **5,333** |

### 8.3 Valuation Rules

| Rule | Requirement |
|------|------------|
| Cost Basis | Purchase price + import duties + transport + handling costs (net of trade discounts) |
| Currency | UGX; foreign currency purchases converted at transaction date rate |
| Lower of Cost or NRV | Inventory carried at the lower of weighted average cost or net realisable value |
| NRV Review | Performed at each month-end close for Class A items; quarterly for all items |
| Write-down Authority | Finance Manager recommends; MD approves write-downs |
| Reversal | Prior write-downs reversed if NRV recovers, up to original cost |

### 8.4 Valuation Controls

- ERP system must automatically calculate weighted average cost on each goods receipt
- Manual cost overrides are prohibited without Finance Manager and Operations Manager dual approval
- Month-end inventory valuation report produced by Finance and reconciled to general ledger
- Physical count results valued at current weighted average cost for reconciliation

---

## 9. Shrinkage Investigation

> **Full SOP:** [`INV-SHR-001-shrinkage-investigation.md`](sops/INV-SHR-001-shrinkage-investigation.md)

### 9.1 Definition

**Shrinkage** = the difference between recorded (system/book) inventory and actual physical inventory, where physical is less than recorded. Causes include theft, damage, administrative errors, supplier short-delivery, and process failures.

### 9.2 Investigation Workflow

```
Variance Identified (Count or Spot Check) → Variance Exceeds Threshold
    → Freeze Item Movements → Investigation Initiated
    → Root Cause Determined → Corrective Action → Adjustment Posted → Report Filed
```

### 9.3 Lean Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Variance identified during count or spot check | Stores Assistant |
| 2 | Operations Manager notified; item movements frozen pending review | Operations Manager |
| 3 | Operations Manager reviews stock card, recent issues/receipts, and access log | Operations Manager |
| 4 | Root cause determined: error, damage, theft, or unknown | Operations Manager |
| 5 | Corrective action documented | Operations Manager |
| 6 | Adjustment posted (within approval threshold) or escalated to MD | Operations Manager / MD |
| 7 | Summary report filed with Finance | Operations Manager |

### 9.4 Controlled Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Variance identified and flagged during count | Stores/Inventory Officer |
| 2 | Item movements frozen in system; physical area secured | Stores/Inventory Officer |
| 3 | Variance Investigation Form completed (INV-TPL-005) | Stores/Inventory Officer |
| 4 | Recount performed by independent counter | Internal Auditor / Designated Counter |
| 5 | Transaction history reviewed: all GRNs, issues, transfers, returns for the item | Stores/Inventory Officer + Finance |
| 6 | Access logs, CCTV footage (if available), and personnel records reviewed | Operations Manager + HR (if theft suspected) |
| 7 | Root cause categorized: (a) Administrative error, (b) Damage/spoilage, (c) Supplier short-delivery, (d) Theft/pilferage, (e) Unresolved | Investigation Lead |
| 8 | Corrective and preventive action (CAPA) documented | Operations Manager |
| 9 | Adjustment approval obtained per threshold table | Per threshold authority |
| 10 | System adjustment posted; signed-off variance form filed | Finance + Stores/Inventory Officer |
| 11 | If theft: disciplinary process initiated (HR); police report if warranted | HR Manager + MD |
| 12 | Quarterly shrinkage report compiled and presented to MD | Operations Manager |

### 9.5 Shrinkage KPIs

| Metric | Target | Red Flag |
|--------|--------|----------|
| Overall shrinkage rate (value) | < 1% of inventory value per quarter | > 2% |
| Shrinkage incidents per month | < 3 incidents | > 5 incidents |
| Investigation closure time | Within 5 business days | > 10 business days |
| Repeat incidents (same item/area) | 0 | Any repeat within 90 days |

---

## 10. Warehousing & Dispatch

> **Full SOP:** [`INV-DSP-001-warehousing-dispatch.md`](sops/INV-DSP-001-warehousing-dispatch.md)

### 10.1 Warehousing Standards

| Area | Standard |
|------|----------|
| Storage Layout | FIFO/FEFO arrangement; fast movers near dispatch area; heavy items on lower shelves |
| Labelling | Every shelf/bin labelled with location code and item description |
| Housekeeping | 5S methodology: Sort, Set in order, Shine, Standardize, Sustain |
| Access | Restricted to authorized personnel only; visitor log maintained |
| Safety | Fire extinguishers serviced quarterly; spill kits for hazardous materials; PPE enforced |
| Pest Control | Monthly inspection; pest control contract in place (ASSUMPTION) |
| Temperature | Climate-sensitive items stored per manufacturer specifications |
| Security | Locks on all access points; CCTV recommended for main store (ASSUMPTION) |

### 10.2 Dispatch Process Overview

```
Sales Order / Delivery Instruction Approved → Pick List Generated
    → Items Picked & Packed → Quality Check → Dispatch Note Issued
    → Vehicle Loaded → Gate Check → Delivery → POD Returned
```

### 10.3 Lean Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Approved sales order or delivery instruction received | Operations Manager |
| 2 | Stores Assistant picks and packs items | Stores Assistant |
| 3 | Dispatch Note completed; quantities verified | Stores Assistant |
| 4 | Vehicle loaded; driver signs Dispatch Note | Driver |
| 5 | Delivery made; customer signs Proof of Delivery (POD) | Driver |
| 6 | POD returned to Stores Assistant; filed with Dispatch Note | Stores Assistant |
| 7 | Stock card updated; Finance notified for invoicing | Stores Assistant |

### 10.4 Controlled Version

| Step | Action | Responsible |
|------|--------|-------------|
| 1 | Approved sales order received and verified against credit terms | Sales / Finance |
| 2 | Stores/Inventory Officer generates pick list from system | Stores/Inventory Officer |
| 3 | Stores Assistant picks items per pick list; records bin locations | Stores Assistant |
| 4 | Second person (checker) verifies picked items against pick list | Checker (Stores) |
| 5 | Items packed; package count recorded | Stores Assistant |
| 6 | Dispatch Note issued in triplicate: Store copy, Customer copy, Driver copy | Stores/Inventory Officer |
| 7 | Logistics Coordinator assigns vehicle and driver; Trip Authorization issued | Logistics Coordinator |
| 8 | Vehicle loaded; gate security checks Dispatch Note against loaded items | Security |
| 9 | Driver delivers; customer signs POD on Dispatch Note | Driver / Customer |
| 10 | POD returned within 24 hours; Stores/Inventory Officer verifies | Stores/Inventory Officer |
| 11 | System updated; stock decremented; Finance notified for invoicing | Stores/Inventory Officer |
| 12 | Undelivered/returned items processed through returns procedure | Stores/Inventory Officer |

### 10.5 RACI — Warehousing & Dispatch

| Activity | Stores Asst | Stores/Inv. Officer | Logistics Coord | Ops Manager | Finance | Security |
|----------|:---:|:---:|:---:|:---:|:---:|:---:|
| Pick and pack | R | A | — | I | — | — |
| Quality/quantity check | R | R/A | — | I | — | — |
| Dispatch Note issuance | C | R/A | I | I | I | I |
| Vehicle assignment | — | C | R | A | — | — |
| Gate verification | — | — | I | I | — | R |
| Delivery execution | — | — | C | I | — | — |
| POD collection | — | R/A | C | I | I | — |
| System update | — | R/A | — | I | I | — |
| Returns processing | R | R/A | C | A | I | — |

---

## 11. Fleet & Logistics Controls

> **Full SOP:** [`INV-FLT-001-fleet-management.md`](sops/INV-FLT-001-fleet-management.md)

### 11.1 Fleet Register

Every company vehicle is recorded in the Fleet Register with:

| Field | Detail |
|-------|--------|
| Vehicle ID | Internal unique identifier |
| Registration Number | Uganda registration plate |
| Make/Model/Year | Vehicle description |
| Assigned Department | Department or business line |
| Primary Driver | Named responsible driver |
| Insurance Expiry | Current insurance validity |
| Inspection Due | Next Uganda vehicle inspection date |
| Service Schedule | Manufacturer-recommended service intervals |
| GPS Tracker | Installed Y/N; device ID |
| Current Mileage | Updated weekly from vehicle logbook |

### 11.2 Trip Authorization

**No company vehicle moves without an approved Trip Authorization Form.**

| Element | Requirement |
|---------|-------------|
| Form | INV-TPL-007 Trip Authorization Form |
| Required Fields | Date, driver, vehicle, destination, purpose, estimated distance, estimated fuel, departure/return time |
| Approval | Lean: Operations Manager; Controlled: Logistics Coordinator (routine), Operations Manager (non-routine/long distance) |
| Emergency Trips | Verbal approval from Operations Manager; form completed within 24 hours |
| Personal Use | Strictly prohibited unless MD provides written authorization |

### 11.3 Fuel Monitoring

| Control | Description |
|---------|-------------|
| Fuel Cards | Company fuel cards used where available; cash purchases require receipt and pre-approval |
| Fuel Log | Driver records fuel purchase in Vehicle Logbook: date, litres, cost, odometer reading, station |
| Consumption Benchmark | Expected km/litre set per vehicle; variance >15% investigated |
| Monthly Reconciliation | Logistics Coordinator reconciles fuel card statements to vehicle logbooks |
| Anomaly Investigation | Unexplained fuel consumption escalated to Operations Manager |
| Fuel Budget | Monthly fuel budget set per vehicle/department; overruns require Operations Manager approval |

### 11.4 Vehicle Maintenance

| Activity | Frequency | Responsible |
|----------|-----------|-------------|
| Daily pre-trip check | Every trip start | Driver |
| Weekly inspection | Weekly | Logistics Coordinator / Driver |
| Routine servicing | Per manufacturer schedule (km or time based) | Logistics Coordinator (arranges) |
| Tyre rotation/replacement | As per wear indicators | Logistics Coordinator |
| Annual inspection (Uganda) | Annually | Logistics Coordinator (arranges) |
| Accident/incident report | As needed | Driver → Logistics Coordinator → Ops Manager |

**Pre-trip Check Items:**

- [ ] Engine oil level
- [ ] Coolant level
- [ ] Tyre pressure and condition
- [ ] Brake function
- [ ] Lights (headlamps, indicators, brake lights)
- [ ] Windshield wipers and washers
- [ ] Horn
- [ ] Mirrors
- [ ] Seatbelts
- [ ] Vehicle documents (licence, insurance, inspection certificate)
- [ ] Fire extinguisher and first aid kit
- [ ] Fuel level

### 11.5 Driver Logs & GPS/Route Controls

| Control | Description |
|---------|-------------|
| Vehicle Logbook | Driver completes INV-TPL-008 for every trip: date, time out/in, origin/destination, purpose, km out/in, fuel added, passenger/cargo details |
| GPS Tracking | Where installed: real-time tracking; route replay; speed alerts; geofencing for authorized zones (ASSUMPTION) |
| Speed Limits | Company speed policy: 80 km/h highways, 40 km/h urban, 20 km/h within premises |
| Route Compliance | Drivers must follow authorized routes; deviations flagged by GPS and investigated |
| Working Hours | Maximum 8 hours continuous driving; 30-minute break after 4 hours (Uganda labor law compliance) |
| Accident Procedure | Stop safely → secure scene → report to Logistics Coordinator immediately → police report within 24 hours → do not admit fault → complete incident form |

### 11.6 RACI — Fleet & Logistics

| Activity | Driver | Logistics Coord | Ops Manager | Finance | MD |
|----------|:---:|:---:|:---:|:---:|:---:|
| Trip authorization request | R | A (routine) | A (non-routine) | — | — |
| Pre-trip vehicle check | R | A | I | — | — |
| Vehicle logbook maintenance | R | A | I | — | — |
| Fuel log and receipts | R | R/A | I | C | — |
| Monthly fuel reconciliation | C | R | A | R | I |
| Routine maintenance scheduling | I | R | A | I | — |
| Accident/incident reporting | R | R | A | I | I |
| GPS monitoring | — | R | A | — | I |
| Fleet register maintenance | — | R | A | — | — |
| Vehicle acquisition/disposal | — | C | R | C | A |

---

## 12. RACI Summary

### 12.1 Consolidated RACI — All Inventory & Logistics Processes

| Process | Stores Asst | Stores/Inv. Officer | Logistics Coord | Ops Manager | Finance | Procurement | Internal Auditor | MD |
|---------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Stock Receiving | R | R/A | — | A | I | C | I | — |
| Stock Issuing | R | R/A | — | A | I | — | I | A (high) |
| Stock Transfers | R | R/A | R | A | I | — | I | — |
| Daily Spot Check | R | A | — | I | — | — | — | — |
| Monthly Cycle Count | R | R/A | — | A | I | — | I | — |
| Quarterly Full Count | R | R | — | A | R | — | R | A (write-off) |
| Shrinkage Investigation | C | R | — | A | C | — | R | A (>threshold) |
| Warehousing | R | R/A | — | A | — | — | I | — |
| Dispatch | R | R/A | R | A | I | — | — | — |
| Fleet Management | — | — | R | A | I | — | I | A (acquisition) |
| Fuel Monitoring | — | — | R | A | R | — | I | I |

**Legend:** R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## 13. SOP Index

| SOP ID | Title | File |
|--------|-------|------|
| INV-RCV-001 | Stock Receiving | [`sops/INV-RCV-001-stock-receiving.md`](sops/INV-RCV-001-stock-receiving.md) |
| INV-ISS-001 | Stock Issuing | [`sops/INV-ISS-001-stock-issuing.md`](sops/INV-ISS-001-stock-issuing.md) |
| INV-TRF-001 | Stock Transfers Between Locations | [`sops/INV-TRF-001-stock-transfers.md`](sops/INV-TRF-001-stock-transfers.md) |
| INV-CNT-001 | Stock Count Procedures | [`sops/INV-CNT-001-stock-counting.md`](sops/INV-CNT-001-stock-counting.md) |
| INV-SHR-001 | Shrinkage Investigation | [`sops/INV-SHR-001-shrinkage-investigation.md`](sops/INV-SHR-001-shrinkage-investigation.md) |
| INV-DSP-001 | Warehousing and Dispatch | [`sops/INV-DSP-001-warehousing-dispatch.md`](sops/INV-DSP-001-warehousing-dispatch.md) |
| INV-FLT-001 | Fleet and Logistics Controls | [`sops/INV-FLT-001-fleet-management.md`](sops/INV-FLT-001-fleet-management.md) |

---

## 14. Templates Index

| Template ID | Title | File |
|-------------|-------|------|
| INV-TPL-001 | Stock Card / Bin Card | [`templates/INV-TPL-001-stock-card.md`](templates/INV-TPL-001-stock-card.md) |
| INV-TPL-002 | Stores Request / Issue Form | [`templates/INV-TPL-002-stores-request-form.md`](templates/INV-TPL-002-stores-request-form.md) |
| INV-TPL-003 | Stock Transfer Note | [`templates/INV-TPL-003-stock-transfer-note.md`](templates/INV-TPL-003-stock-transfer-note.md) |
| INV-TPL-004 | Stock Count Sheet | [`templates/INV-TPL-004-stock-count-sheet.md`](templates/INV-TPL-004-stock-count-sheet.md) |
| INV-TPL-005 | Stock Variance Investigation Form | [`templates/INV-TPL-005-variance-investigation-form.md`](templates/INV-TPL-005-variance-investigation-form.md) |
| INV-TPL-006 | Dispatch Note | [`templates/INV-TPL-006-dispatch-note.md`](templates/INV-TPL-006-dispatch-note.md) |
| INV-TPL-007 | Trip Authorization Form | [`templates/INV-TPL-007-trip-authorization-form.md`](templates/INV-TPL-007-trip-authorization-form.md) |
| INV-TPL-008 | Vehicle Logbook | [`templates/INV-TPL-008-vehicle-logbook.md`](templates/INV-TPL-008-vehicle-logbook.md) |

---

## 15. KPIs & Reporting

### 15.1 Inventory KPIs

| KPI | Formula | Target | Frequency |
|-----|---------|--------|-----------|
| Inventory Accuracy | (Correct count items / Total items counted) x 100 | > 97% | Monthly |
| Shrinkage Rate | (Shrinkage value / Total inventory value) x 100 | < 1% per quarter | Quarterly |
| Stock Turnover | Cost of Goods Sold / Average Inventory Value | Sector-dependent (ASSUMPTION) | Monthly |
| Days of Stock on Hand | (Average Inventory / COGS) x 365 | < 45 days (ASSUMPTION) | Monthly |
| Dead Stock % | Dead stock value / Total inventory value x 100 | < 3% | Quarterly |
| GRN Processing Time | Time from delivery to GRN completion | Same day (< 4 hours) | Weekly |
| Stockout Rate | (Stockout incidents / Total requisitions) x 100 | < 2% | Monthly |
| Order Fill Rate | (Requisitions fully filled / Total requisitions) x 100 | > 95% | Monthly |

### 15.2 Logistics KPIs

| KPI | Formula | Target | Frequency |
|-----|---------|--------|-----------|
| On-Time Delivery | (Deliveries on time / Total deliveries) x 100 | > 95% | Weekly |
| Fuel Efficiency | Actual km/litre vs. benchmark km/litre | Within 15% of benchmark | Monthly |
| Vehicle Utilization | (Active trip hours / Available hours) x 100 | > 70% | Monthly |
| Vehicle Downtime | (Days out of service / Total days) x 100 | < 5% | Monthly |
| Trip Authorization Compliance | (Authorized trips / Total trips) x 100 | 100% | Weekly |
| POD Return Rate (within 24 hrs) | (PODs returned on time / Total dispatches) x 100 | > 98% | Weekly |
| Maintenance Compliance | (Services done on schedule / Services due) x 100 | 100% | Monthly |
| Accident/Incident Rate | Incidents per 10,000 km | < 0.5 | Monthly |

### 15.3 Reports

| Report | Prepared By | Frequency | Submitted To |
|--------|------------|-----------|-------------|
| Daily Stock Movement Summary | Stores/Inventory Officer | Daily | Operations Manager |
| Weekly Spot Check Log | Stores/Inventory Officer | Weekly | Operations Manager |
| Monthly Inventory Report | Stores/Inventory Officer + Finance | Monthly | Operations Manager, Finance Manager |
| Monthly Fleet Report | Logistics Coordinator | Monthly | Operations Manager |
| Quarterly Full Count Report | Operations Manager | Quarterly | MD, Finance Manager, Internal Auditor |
| Quarterly Shrinkage Report | Operations Manager | Quarterly | MD |
| Dead Stock / Slow Mover Report | Stores/Inventory Officer | Quarterly | Operations Manager |
| Annual Inventory Valuation | Finance Manager | Annually | MD, Board, External Auditors |

---

## 16. Questions & Assumptions

| # | Item | Type | Default Used | Action Required |
|---|------|------|-------------|-----------------|
| 1 | Inventory valuation method | ASSUMPTION | Weighted Average Cost | Confirm with Finance Manager and auditors |
| 2 | Number of store locations | ASSUMPTION | 1 Main Store + potential sub-stores | Confirm current locations |
| 3 | Fleet size | ASSUMPTION | Not specified; framework scales to any size | Provide vehicle register |
| 4 | GPS tracking installed | ASSUMPTION | Assumed available on primary vehicles | Confirm GPS provider and coverage |
| 5 | CCTV in stores | ASSUMPTION | Recommended but not confirmed | Confirm current security infrastructure |
| 6 | Pest control contract | ASSUMPTION | In place | Confirm provider |
| 7 | Fuel card provider | ASSUMPTION | Available | Confirm fuel management arrangement |
| 8 | ERP for inventory | ASSUMPTION | Odoo inventory module | Confirm ERP platform |
| 9 | Stock turnover target | ASSUMPTION | Sector-dependent; to be baselined | Set targets after 3 months of data |
| 10 | Approval thresholds (UGX) | ASSUMPTION | As stated in Section 5.5 | Confirm with MD and align with DoA |
| 11 | Working hours for drivers | ASSUMPTION | 8 hours max continuous | Confirm compliance with Uganda employment law |
| 12 | Insurance coverage | QUESTION | Unknown | Provide details of vehicle and goods-in-transit insurance |
| 13 | Hazardous materials | QUESTION | Unknown | Confirm if any stock requires special handling/licensing |
| 14 | Cold chain requirements | QUESTION | Unknown | Confirm if temperature-controlled storage needed |
| 15 | Customs/bonded warehouse | QUESTION | Unknown | Confirm if import operations require bonded facility |

---

*Awdeer Investments Limited — Inventory, Stores & Logistics System*
*Part E of the Business Operating System*
*Version 1.0 — February 2026*
