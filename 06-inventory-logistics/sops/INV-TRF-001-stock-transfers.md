# INV-TRF-001 — Stock Transfers Between Locations SOP

## Document Control

| Field | Detail |
|-------|--------|
| Document ID | INV-TRF-001 |
| Title | Stock Transfers Between Locations Standard Operating Procedure |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Stores/Inventory Officer |
| Approved By | Operations Manager |
| Review Cycle | Annually or after significant process change |

---

## 1. Purpose

To establish a standardized procedure for transferring stock between Awdeer Investments Limited store locations, ensuring that inter-location movements are properly authorized, documented, physically verified at both ends, and accurately reflected in inventory records.

---

## 2. Scope

This SOP applies to:

- All transfers of stock between any two Awdeer Investments Limited store or warehouse locations
- Transfers between Main Store and Sub-Stores, between Sub-Stores, and between any combination of locations
- All categories of inventory items
- Both routine replenishment transfers and ad-hoc/emergency transfers

This SOP does **not** cover:

- Issues to internal departments (covered under INV-ISS-001)
- Dispatch to external customers (covered under INV-DSP-001)
- Returns to suppliers (covered under INV-RCV-001)
- Movement of items within the same store location (internal relocation — handled by Stores Officer)

---

## 3. RACI Matrix

### 3.1 Lean Version

| Activity | Requesting Store | Sending Store | Operations Manager | Finance |
|----------|:---:|:---:|:---:|:---:|
| Raise transfer request | R | I | A | — |
| Confirm stock availability | — | R | I | — |
| Approve transfer | — | — | R/A | I |
| Pick and pack items | — | R | I | — |
| Complete Stock Transfer Note | — | R | I | — |
| Arrange transport | — | R | A | — |
| Dispatch goods | — | R | I | — |
| Receive and inspect | R | — | I | — |
| Confirm receipt on STN | R | — | I | — |
| Update stock cards (both ends) | R | R | I | I |
| Forward STN to Finance | R | — | I | R/A |

### 3.2 Controlled Version

| Activity | Requesting Store Officer | Sending Store Officer | Logistics Coord | Ops Manager | Finance | Internal Auditor |
|----------|:---:|:---:|:---:|:---:|:---:|:---:|
| Raise transfer request (ERP) | R | I | I | I | — | — |
| Confirm stock availability | — | R | — | I | — | — |
| Approve transfer | — | — | — | R/A | I | — |
| Generate pick list | — | R | — | — | — | — |
| Pick, pack, label | — | R | — | — | — | — |
| Issue STN (triplicate) | — | R/A | I | I | I | — |
| Arrange transport; Trip Auth | — | C | R | A | — | — |
| Gate check (sending) | — | C | I | — | — | — |
| Physical transit | — | — | R | I | — | — |
| Receive and inspect | R | — | I | I | — | — |
| Report variances | R | C | C | A | I | I |
| Confirm receipt on STN/ERP | R/A | — | I | I | I | — |
| Update system (both ends) | R | R | — | I | I | — |
| Cost reallocation | — | — | — | A | R | — |
| File documentation | R | R | C | I | R | I |

**Legend:** R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## 4. Inputs & Outputs

### 4.1 Inputs

| Input | Source | Purpose |
|-------|--------|---------|
| Transfer Request | Requesting location | Formal request for stock |
| Stock availability data | Sending location / ERP | Confirms items available to transfer |
| Operations Manager approval | Operations Manager | Authorization |
| Transport availability | Logistics Coordinator | Vehicle and driver assignment |
| Trip Authorization Form (INV-TPL-007) | Logistics Coordinator | Authorizes vehicle movement |

### 4.2 Outputs

| Output | Destination | Purpose |
|--------|-------------|---------|
| Stock Transfer Note (INV-TPL-003) | Sending store, Receiving store, Finance | Official transfer record |
| Updated stock cards (both locations) | Both stores | Adjusted balances |
| Updated ERP records (both locations) | System | Real-time visibility |
| Variance report (if applicable) | Operations Manager, Finance | Discrepancy resolution |
| Cost reallocation entry | Finance | Correct cost centre allocation |

---

## 5. Step-by-Step Workflow

### 5.1 Lean Version (Small Team < 15 People)

#### Step 1: Transfer Request

- Requesting location identifies need for stock from another location
- Request submitted to Operations Manager: item description, quantity needed, urgency, reason
- Can be via email, WhatsApp message, or verbal (followed by written confirmation)

#### Step 2: Approval

- Operations Manager reviews request against business need and sending store's stock levels
- Operations Manager approves or rejects with reason
- Notification sent to both requesting and sending stores

#### Step 3: Preparation at Sending Store

- Stores Assistant at sending location picks requested items
- Counts and inspects items for condition
- Completes Stock Transfer Note (INV-TPL-003) in duplicate:
  - Copy 1: accompanies goods to receiving store
  - Copy 2: retained at sending store
- STN includes: date, sending store, receiving store, item descriptions, quantities, condition, sender signature

#### Step 4: Transport

- Operations Manager arranges transport (company vehicle or other means)
- If company vehicle: Trip Authorization Form completed
- Items securely loaded; STN accompanies the goods

#### Step 5: Receipt at Receiving Store

- Stores Assistant at receiving location:
  - Counts all items received
  - Checks condition against STN
  - Notes any variances on STN (short, damaged, wrong items)
  - Signs STN as receiver
- If variances found: Operations Manager notified immediately

#### Step 6: Record Update

- Sending store updates stock card: decrements quantity, references STN number
- Receiving store updates stock card: increments quantity, references STN number
- Both updates done on same day as physical transfer
- Signed STN copy forwarded to Finance for cost reallocation

### 5.2 Controlled Version (Mid-Size Team 15–100+ People)

#### Step 1: Raise Transfer Request in System

- Requesting location's Stores/Inventory Officer raises transfer request in ERP
- Required fields: requesting location, sending location, item codes, descriptions, quantities, unit of measure, reason for transfer, urgency level, required date

#### Step 2: Sending Store Confirms Availability

- Sending location's Stores/Inventory Officer reviews request
- Confirms stock is available and not reserved for other commitments
- If insufficient: proposes partial transfer or alternative source; notifies requester

#### Step 3: Operations Manager Approval

- Transfer request routed to Operations Manager in system
- Operations Manager reviews: business justification, stock impact on sending location, transport cost consideration
- Approves, modifies (e.g., reduced quantity), or rejects with reason
- Both locations notified of decision

#### Step 4: Pick and Pack

- Sending store's Stores/Inventory Officer generates pick list from approved transfer
- Stores Assistant picks items from designated bin locations
- Items counted, inspected for condition, and packed securely for transit
- Fragile or hazardous items packed with appropriate protection and labelling

#### Step 5: Issue Stock Transfer Note

- Stores/Inventory Officer (Sending) issues STN in triplicate:
  - **Copy 1:** Accompanies goods (becomes receiving store's record)
  - **Copy 2:** Retained at sending store
  - **Copy 3:** Sent to Finance
- STN includes:
  - Sequential STN number
  - Date
  - Sending store and receiving store details
  - Approved transfer reference number
  - Line-by-line: item code, description, UoM, quantity sent, condition, bin location (from)
  - Sender name and signature
  - Vehicle details and driver name
  - Space for receiver signature and variance notes

#### Step 6: Arrange Transport

- Logistics Coordinator assigns vehicle and driver
- Trip Authorization Form (INV-TPL-007) completed and approved
- If third-party transport: Logistics Coordinator arranges and documents transporter details
- Estimated transit time communicated to receiving location

#### Step 7: Dispatch

- Items loaded onto vehicle under Stores Assistant supervision
- Security (if applicable) checks loaded items against STN at gate
- Sending store decrements stock in system immediately upon dispatch
- Items marked as "In Transit" in system

#### Step 8: Receipt and Inspection

- Receiving location's Stores/Inventory Officer and Stores Assistant receive goods
- Independent count: count items without reference to STN quantities first, then compare
- Inspect condition: any damage, seal breakage, spoilage noted
- Variances recorded on STN with details

#### Step 9: Confirm Receipt

- Receiving Stores/Inventory Officer signs STN confirming receipt
- If no variance: receipt confirmed in ERP; receiving location stock incremented
- If variance exists:
  - Partial receipt confirmed for undisputed items
  - Variance flagged in system
  - Operations Manager and sending store notified immediately
  - Investigation per shrinkage/variance procedures (INV-SHR-001 if warranted)

#### Step 10: System and Record Updates

- Receiving store updates ERP: goods received against transfer order
- "In Transit" status cleared
- Bin locations assigned at receiving store
- Stock cards / bin cards updated at both locations
- STN copies filed at both locations and with Finance

#### Step 11: Cost Reallocation

- Finance processes cost reallocation if transfer crosses cost centres or business lines
- Transfer valued at Weighted Average Cost at time of dispatch
- No mark-up or margin on internal transfers

#### Step 12: Documentation and Filing

- Sending store: STN Copy 2 + transfer request + pick list filed
- Receiving store: STN Copy 1 + receipt confirmation filed
- Finance: STN Copy 3 + cost reallocation entry filed
- All filed chronologically and by STN number

---

## 6. Controls & Approvals

| Control | Description | Version |
|---------|-------------|---------|
| Approval required | All transfers require Operations Manager approval | Both |
| STN mandatory | No stock moves between locations without a Stock Transfer Note | Both |
| Independent count at receipt | Receiving store counts independently before comparing to STN | Controlled |
| Same-day system update | Both stores update records on the day of physical transfer | Both |
| In-transit tracking | Items marked "In Transit" between dispatch and receipt | Controlled |
| Variance investigation | Any variance between sent and received quantities investigated | Both |
| No self-transfer approval | The person requesting cannot be the sole approver | Both |
| Transport documentation | Trip Authorization required for company vehicles | Both |
| Gate check | Security verifies items against STN at dispatch gate | Controlled |
| Triplicate STN | Three copies ensure all parties (sender, receiver, Finance) have records | Controlled |
| Cost centre alignment | Finance reallocates costs when transfer crosses cost centres | Controlled |

---

## 7. Documents & Forms

| Document | Template Reference | Purpose |
|----------|--------------------|---------|
| Stock Transfer Note | INV-TPL-003 | Primary transfer record |
| Stock Card / Bin Card | INV-TPL-001 | Balance tracking at each location |
| Trip Authorization Form | INV-TPL-007 | Vehicle authorization for transport |
| Stock Variance Investigation Form | INV-TPL-005 | For transfer discrepancies |
| Transfer Request | ERP or manual form | Initiation document |

---

## 8. KPIs

| KPI | Formula | Target | Measurement Frequency |
|-----|---------|--------|-----------------------|
| Transfer Accuracy | (Transfers without variance / Total transfers) x 100 | > 98% | Monthly |
| Transfer Processing Time | Time from approved request to receiving store confirmation | < 24 hours (same city); < 48 hours (inter-city) | Per transfer |
| STN Compliance | (Transfers with complete STN / Total transfers) x 100 | 100% | Monthly |
| Transit Loss Rate | (Items lost in transit / Total items transferred) x 100 | 0% | Monthly |
| Same-Day Update Rate | (Transfers updated same day at both ends / Total transfers) x 100 | > 95% | Monthly |
| Variance Investigation Closure | Average days to resolve transfer variances | < 5 business days | Monthly |

---

## 9. Process Flowchart (Text)

```
START
  │
  ├─► Requesting store raises transfer request
  │
  ├─► Sending store confirms stock availability
  │         │
  │    ├── Available ──► Continue
  │    └── Not available ──► Notify requester; propose alternatives ──► END or revise
  │
  ├─► Operations Manager approves? ──► NO ──► Reject with reason ──► END
  │         │
  │        YES
  │         │
  ├─► Sending store picks, packs, issues STN
  │
  ├─► Transport arranged (Trip Authorization if company vehicle)
  │
  ├─► Goods dispatched; sending store decrements stock; items "In Transit"
  │
  ├─► Receiving store counts and inspects
  │         │
  │    ├── No variance ──► Confirm receipt; increment stock
  │    └── Variance ──► Note on STN; notify Ops Manager; investigate
  │
  ├─► System updated both ends (same day)
  │
  ├─► Finance processes cost reallocation (if applicable)
  │
  ├─► STN copies filed at sender, receiver, Finance
  │
  └─► END
```

---

## 10. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | February 2026 | Operations Manager | Initial release |

---

*Awdeer Investments Limited — INV-TRF-001 Stock Transfers SOP*
*Version 1.0 — February 2026*
