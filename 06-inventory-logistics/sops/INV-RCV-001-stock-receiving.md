# INV-RCV-001 — Stock Receiving SOP

## Document Control

| Field | Detail |
|-------|--------|
| Document ID | INV-RCV-001 |
| Title | Stock Receiving Standard Operating Procedure |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Stores/Inventory Officer |
| Approved By | Operations Manager |
| Review Cycle | Annually or after significant process change |

---

## 1. Purpose

To establish a standardized procedure for receiving goods into Awdeer Investments Limited stores and warehouses, ensuring that all deliveries are verified against purchase orders, inspected for quality and quantity, accurately recorded, and properly stored.

---

## 2. Scope

This SOP applies to:

- All goods received at any Awdeer Investments Limited store or warehouse location
- All categories of inventory: raw materials, finished goods, consumables, spare parts, fuel, equipment
- All personnel involved in the receiving process: stores staff, procurement, finance, security
- Both planned (PO-based) deliveries and emergency/ad-hoc receipts

This SOP does **not** cover:

- Receipt of fixed assets (covered under Finance asset management procedures)
- Receipt of services (covered under Procurement)
- Internal stock transfers (covered under INV-TRF-001)

---

## 3. RACI Matrix

### 3.1 Lean Version

| Activity | Stores Assistant | Operations Manager | Finance | Procurement |
|----------|:---:|:---:|:---:|:---:|
| Receive delivery at gate | R/A | I | — | I |
| Check delivery against PO | R | A | — | C |
| Physical count and inspection | R | A | — | — |
| Complete GRN | R | A | I | I |
| Update stock card / system | R | A | I | — |
| Handle discrepancies | R | A | I | R |
| Forward documents to Finance | R | I | R/A | — |
| Handle returns to supplier | R | A | I | R |

### 3.2 Controlled Version

| Activity | Security | Stores Asst | Stores/Inv. Officer | Ops Manager | Finance | Procurement |
|----------|:---:|:---:|:---:|:---:|:---:|:---:|
| Gate entry logging | R | — | I | I | — | — |
| Check delivery note vs PO | — | R | A | I | — | C |
| Quantity count | — | R | A | I | — | — |
| Quality inspection | — | C | R/A | I | — | C |
| Specialist QC (if needed) | — | — | C | A | — | R |
| Complete GRN | — | C | R/A | I | I | I |
| System update (ERP) | — | C | R/A | I | I | — |
| Update bin card / stock card | — | R | A | I | — | — |
| Bin allocation and shelving | — | R | A | — | — | — |
| Three-way match | — | — | C | I | R/A | C |
| Handle discrepancies/damages | — | — | R | A | I | R |
| Quarantine management | — | R | R/A | A | I | C |
| Supplier return processing | — | C | R | A | I | R/A |

**Legend:** R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## 4. Inputs & Outputs

### 4.1 Inputs

| Input | Source | Purpose |
|-------|--------|---------|
| Approved Purchase Order (PO) | Procurement | Reference for expected delivery |
| Supplier Delivery Note / Packing List | Supplier | Lists items being delivered |
| Supplier Invoice (if delivered with goods) | Supplier | For three-way match |
| Quality specifications / technical requirements | Procurement / Technical | Inspection criteria |
| Stock card / bin card (current) | Stores | Current balance verification |

### 4.2 Outputs

| Output | Destination | Purpose |
|--------|-------------|---------|
| Goods Received Note (GRN) | Finance, Stores, Supplier | Official receipt record |
| Updated stock card / bin card | Stores | Accurate stock balance |
| Updated ERP inventory record | System | Real-time stock visibility |
| Discrepancy / damage report | Procurement, Operations Manager | Variance resolution |
| Return to Supplier Note (if applicable) | Supplier, Procurement | Short delivery or quality rejection |

---

## 5. Step-by-Step Workflow

### 5.1 Lean Version (Small Team < 15 People)

#### Step 1: Delivery Arrival

- Supplier/transporter arrives at premises with goods
- Stores Assistant verifies that a valid, approved Purchase Order exists for the delivery
- If no PO exists: **do not accept delivery**; contact Operations Manager immediately

#### Step 2: Preliminary Check

- Stores Assistant receives supplier's delivery note / packing list
- Cross-references delivery note against PO: item descriptions, quantities ordered, unit of measure
- Notes any obvious external damage to packaging before offloading

#### Step 3: Offloading and Physical Count

- Goods offloaded to Receiving Bay (not directly to storage shelves)
- Stores Assistant counts every item delivered
- For bulk items: count packages/units; weigh if required
- For sealed containers: verify seal integrity and count/weight per container

#### Step 4: Quality Inspection

- Visual inspection for damage, expiry dates, correct specifications
- For technical/specialized items: request Operations Manager or technical person to verify
- Items failing quality check are separated immediately and marked "REJECTED"

#### Step 5: Complete Goods Received Note (GRN)

- Stores Assistant completes GRN with:
  - GRN number (sequential)
  - Date of receipt
  - PO number
  - Supplier name
  - Item descriptions and quantities received
  - Any variances from PO (short delivery, over-delivery, damages)
  - Stores Assistant signature
- Supplier representative / driver signs GRN as acknowledgment

#### Step 6: Update Records

- Stock card / bin card updated with received quantity
- Items moved to designated storage location (FIFO arrangement)
- Stock card shows: date, GRN reference, quantity in, new balance

#### Step 7: Document Forwarding

- GRN + copy of delivery note forwarded to Operations Manager for review
- Operations Manager spot-checks a sample of received goods (recommended: 20% of line items)
- Operations Manager signs off and forwards to Finance for three-way match (PO + GRN + Invoice)

#### Step 8: Handle Discrepancies

- If quantity variance exists: note on GRN; Operations Manager contacts supplier via Procurement
- If quality issue exists: items held in separate area; Operations Manager decides accept/reject/return
- Return to Supplier Note completed if goods are being sent back

### 5.2 Controlled Version (Mid-Size Team 15–100+ People)

#### Step 1: Gate Registration

- Supplier vehicle arrives at gate
- Security logs: date, time, vehicle registration, driver name, supplier name, delivery note number
- Security verifies a delivery is expected (checks with Stores/Inventory Officer or against delivery schedule)
- Vehicle directed to designated Receiving Bay

#### Step 2: Document Verification

- Stores Assistant receives supplier delivery note and packing list
- Stores/Inventory Officer retrieves corresponding approved PO from system
- Verifies: supplier name matches PO, item descriptions match, quantities ordered, delivery within PO validity period
- If no valid PO: **refuse delivery**; notify Procurement Manager immediately

#### Step 3: Offloading

- Goods offloaded to Receiving Bay only (never directly to storage)
- Offloading supervised by Stores Assistant
- Any damage observed during offloading noted immediately with photographic evidence

#### Step 4: Quantity Verification

- Stores Assistant performs physical count of all items
- Count performed independently — not based on delivery note quantities
- For large deliveries: systematic counting by item line; use tally sheets
- For weight-based items: use calibrated scales; record gross, tare, and net weights
- Results recorded on count sheet or directly on GRN draft

#### Step 5: Quality Inspection

- Stores/Inventory Officer inspects quality:
  - Visual condition (no damage, leaks, corrosion)
  - Specifications match PO requirements (size, grade, model, colour)
  - Expiry dates checked (minimum 75% shelf life remaining — ASSUMPTION)
  - Packaging integrity
  - Certifications / certificates of analysis where required
- For technical or specialized items: relevant technical person called to inspect
- Items failing inspection separated to **Quarantine Area**

#### Step 6: GRN Issuance

- Stores/Inventory Officer completes GRN in system (or manually in triplicate):
  - **Copy 1:** Stores (filed with stock card)
  - **Copy 2:** Finance (for three-way match)
  - **Copy 3:** Supplier/Transporter (proof of delivery)
- GRN includes:
  - Sequential GRN number
  - Date and time of receipt
  - PO number
  - Supplier name and delivery note number
  - Line-by-line: item code, description, unit of measure, quantity ordered, quantity received, quantity accepted, quantity rejected, variance
  - Bin location assigned
  - Receiver signature (Stores/Inventory Officer)
  - Supplier/driver signature
- GRN must be issued **on the same day** as physical receipt

#### Step 7: System Update

- Stores/Inventory Officer posts goods receipt in ERP system
- System automatically calculates new Weighted Average Cost
- Bin location recorded in system
- Stock card / bin card at shelf level updated by Stores Assistant

#### Step 8: Shelving and Storage

- Stores Assistant moves accepted goods to designated bin locations
- FIFO/FEFO arrangement maintained: new stock placed behind existing stock
- Bin card updated with: date, GRN reference, quantity added, new balance
- Items requiring special storage conditions (temperature, humidity) placed in appropriate area

#### Step 9: Three-Way Match

- Finance receives GRN copy
- Finance performs three-way match: PO vs. GRN vs. Supplier Invoice
- Matched documents proceed to payment processing (per Finance AP procedures)
- Mismatches flagged and resolved with Stores/Inventory Officer and Procurement

#### Step 10: Discrepancy Management

- **Quantity variance (short delivery):** Noted on GRN; Procurement contacts supplier for balance delivery or credit note
- **Quantity variance (over-delivery):** Noted on GRN; excess held pending decision — accept (with PO amendment) or return
- **Quality rejection:** Items in Quarantine; Stores/Inventory Officer raises rejection report; Procurement arranges return or replacement
- **Damaged goods:** Photographic evidence; transporter liability assessed; insurance claim if applicable
- All discrepancies documented with resolution timeline (maximum 5 business days)

#### Step 11: Quarantine Processing

- Rejected/damaged goods held in Quarantine Area with clear labelling
- Quarantine register maintained: item, quantity, reason, date quarantined, PO reference
- Resolution within 10 business days: return to supplier, rework/repair, write-off
- Operations Manager approves quarantine resolution; Finance notified of any financial impact

---

## 6. Controls & Approvals

| Control | Description | Version |
|---------|-------------|---------|
| No PO, No Receipt | Goods cannot be received without a valid, approved PO | Both |
| Same-day GRN | GRN must be issued on the day of physical receipt | Both |
| No backdating | GRNs cannot be backdated; system enforced where possible | Both |
| Independent count | Physical count must be independent of delivery note quantities | Controlled |
| Segregation of duties | Person raising PO cannot be the person receiving goods | Both |
| Photographic evidence | Required for all damages and quality rejections | Controlled |
| Dual signature | Both receiver and supplier/driver sign GRN | Both |
| Quarantine separation | Rejected goods physically separated from accepted stock | Both |
| Shelf-life minimum | Minimum 75% shelf life remaining for perishable/expiring items (ASSUMPTION) | Both |
| System reconciliation | Physical receipt reconciled to system record same day | Controlled |
| Spot-check by manager | Operations Manager spot-checks 20% of receipts | Lean |
| Three-way match | PO + GRN + Invoice matched before payment | Both |

---

## 7. Documents & Forms

| Document | Template Reference | Purpose |
|----------|--------------------|---------|
| Goods Received Note (GRN) | Part of ERP system or manual form | Primary receiving record |
| Stock Card / Bin Card | INV-TPL-001 | Item-level stock balance tracker |
| Stores Request Form | INV-TPL-002 | (Referenced for issuing, not receiving) |
| Stock Variance Investigation Form | INV-TPL-005 | For receiving discrepancies requiring investigation |
| Purchase Order | PRO-PUR-001 (Procurement) | Reference document for expected delivery |
| Supplier Delivery Note | External (Supplier) | Supplier's delivery record |
| Return to Supplier Note | Internal form | For goods being returned |

---

## 8. KPIs

| KPI | Formula | Target | Measurement Frequency |
|-----|---------|--------|-----------------------|
| GRN Processing Time | Time from delivery arrival to GRN completion | < 4 hours (same day) | Per receipt; weekly summary |
| Receiving Accuracy | (GRNs without errors / Total GRNs) x 100 | > 98% | Monthly |
| Supplier Delivery Accuracy | (Deliveries matching PO / Total deliveries) x 100 | > 95% | Monthly |
| Quarantine Resolution Time | Average days from quarantine to resolution | < 10 business days | Monthly |
| Damage/Rejection Rate | (Rejected line items / Total line items received) x 100 | < 2% | Monthly |
| Same-Day GRN Compliance | (GRNs issued same day / Total GRNs) x 100 | 100% | Weekly |
| Three-Way Match Rate | (Documents matched first time / Total receipts) x 100 | > 90% | Monthly |

---

## 9. Process Flowchart (Text)

```
START
  │
  ├─► Supplier arrives with goods
  │
  ├─► Valid PO exists? ──► NO ──► Refuse delivery; notify Procurement ──► END
  │         │
  │        YES
  │         │
  ├─► Offload to Receiving Bay
  │
  ├─► Physical count (independent of delivery note)
  │
  ├─► Quality inspection
  │         │
  │    ├── PASS ──► Record on GRN (quantities accepted)
  │    │
  │    └── FAIL ──► Move to Quarantine; record on GRN (quantities rejected)
  │                    │
  │                    ├─► Notify Procurement for supplier resolution
  │                    └─► Resolve within 10 days
  │
  ├─► GRN issued (same day)
  │
  ├─► System updated; stock card updated
  │
  ├─► Items shelved in bin location (FIFO/FEFO)
  │
  ├─► GRN forwarded to Finance for three-way match
  │
  └─► END
```

---

## 10. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | February 2026 | Operations Manager | Initial release |

---

*Awdeer Investments Limited — INV-RCV-001 Stock Receiving SOP*
*Version 1.0 — February 2026*
