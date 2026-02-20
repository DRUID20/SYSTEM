# SOP: PRO-FRD-001 — Procurement Fraud Prevention Controls

## Awdeer Investments Limited — Uganda

| Field | Detail |
|-------|--------|
| SOP Code | PRO-FRD-001 |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Operations Manager (Lean) / Procurement Manager + Internal Auditor (Controlled) |
| Approved By | Managing Director |
| Review Cycle | Annually or upon material change |

---

## 1. Purpose

This SOP establishes the controls, monitoring procedures, and response protocols for preventing, detecting, and responding to procurement fraud at Awdeer Investments Limited. Procurement fraud undermines value for money, erodes trust, and can result in significant financial loss and legal liability. This SOP ensures that robust preventive and detective controls are embedded throughout the procurement process.

---

## 2. Scope

**In Scope:**
- All fraud risks within the procurement lifecycle (requisition through payment)
- Split purchase detection and prevention
- Vendor conflict of interest management
- Bid rigging and collusion prevention
- Fictitious supplier detection
- Invoice fraud prevention
- Kickback and bribery prevention
- Post-award contract manipulation
- Whistleblower management for procurement fraud

**Out of Scope:**
- General financial fraud (governed by FIN-FRD-001)
- Employee expense fraud (governed by FIN-EXP-001)
- Cybersecurity fraud (governed by IT-SEC-001)
- Customer fraud (governed by SAL-FRD-001)

---

## 3. RACI Matrix

### Lean Version

| Activity | Operations Manager | Finance Manager | MD |
|----------|-------------------|-----------------|-----|
| Implement preventive controls | **R, A** | C | I |
| Monitor procurement patterns | **R** | **R, A** | I |
| Manage conflict of interest declarations | **R** | **A** | I |
| Conduct split-purchase reviews | R | **R, A** | I |
| Investigate flagged transactions | R | **R** | **A** |
| Report fraud incidents | **R** | **R** | **A** |
| Enforce consequences | — | C | **R, A** |
| Manage whistleblower reports | — | R | **A** |
| Annual fraud risk assessment | **R** | **R** | **A** |

### Controlled Version

| Activity | Proc. Officer | Proc. Manager | Finance Manager | Internal Auditor | Legal/Compliance | MD | Board |
|----------|--------------|---------------|-----------------|-----------------|-----------------|-----|-------|
| Implement preventive controls | R | **R, A** | C | C | C | I | — |
| Monitor procurement patterns (ongoing) | **R** | **A** | — | I | — | — | — |
| Conduct data analytics / pattern reviews | — | C | — | **R, A** | — | I | — |
| Manage conflict of interest program | R | R | — | C | **R, A** | I | — |
| Conduct split-purchase reviews | R | R | R | **R, A** | — | I | — |
| Bid integrity monitoring | R | **R, A** | — | C | — | — | — |
| Supplier due diligence (fraud prevention) | **R** | **A** | C | C | C | — | — |
| Investigate flagged transactions | — | C | C | **R, A** | C | I | — |
| Investigate suspected fraud | — | C | C | **R** | **R** | **A** | I |
| Report confirmed fraud | — | — | I | **R** | R | **A** | **A** |
| Enforce consequences | — | C | C | I | **R** | **A** | **A** (if >UGX 50M) |
| Manage whistleblower reports | — | — | — | **R** | **A** | I | I |
| Annual fraud risk assessment | R | **R** | R | **R, A** | C | I | I |
| Quarterly fraud controls report | — | R | R | **R, A** | — | I | I |

---

## 4. Inputs and Outputs

### Inputs

| Input | Source | Format |
|-------|--------|--------|
| Procurement transaction data | ERP / Procurement records | System reports |
| Conflict of interest declarations | Staff and suppliers | Signed declaration forms |
| Bid/quotation documents | Procurement files | Physical/digital documents |
| Supplier master data | ERP / ASL | System data |
| Whistleblower reports | Whistleblower channel | Anonymous reports |
| Internal audit reports | Internal Audit | Audit reports |
| Market price benchmarks | Procurement research | Price database |

### Outputs

| Output | Destination | Format |
|--------|-------------|--------|
| Split Purchase Analysis Report | MD, Internal Audit | Analytical report |
| Conflict of Interest Register | Legal/Compliance, Internal Audit | Register/database |
| Bid Integrity Report | Procurement Manager, MD | Investigation report |
| Fraud Investigation Report | MD, Board (if material) | Confidential report |
| Quarterly Fraud Controls Report | MD, Board | Dashboard/report |
| Disciplinary Referral | HR | Referral memo |
| Supplier Blacklist Update | Procurement, all staff | Updated blacklist |
| Whistleblower Case File | Confidential register | Case record |

---

## 5. Step-by-Step Workflow

### 5.1 Split Purchase Prevention and Detection

#### Definition
Split purchasing occurs when a buyer deliberately divides a purchase into smaller orders to avoid higher procurement thresholds, thereby circumventing competitive sourcing requirements and approval authorities.

#### Red Flags

| Red Flag | Indicator |
|----------|-----------|
| Sequential POs to same supplier | Multiple POs within 30 days, same supplier, same category |
| Just-below-threshold amounts | PO values consistently just below threshold limits (e.g., UGX 490,000, UGX 4,900,000) |
| Same requester, same category | One person repeatedly placing same-category orders in quick succession |
| Artificially split line items | Items that logically belong together placed on separate POs |
| Timing patterns | Orders placed at month-end or just before budget cycle reset |

#### Lean Version — Controls and Monitoring

| Step | Action | Responsible | Frequency |
|------|--------|-------------|-----------|
| 1 | Finance Manager reviews monthly procurement spend report grouped by: supplier, category, requester | FM | Monthly |
| 2 | Flag any supplier receiving more than 3 POs in the same category within 30 days | FM | Monthly |
| 3 | Flag PO values clustering just below threshold limits (within 10% below threshold) | FM | Monthly |
| 4 | Investigate flagged transactions: interview requester, review business justification, assess whether a single PO at the higher tier was appropriate | OM + FM | Within 5 BD of flag |
| 5 | Determine finding: legitimate business need (clear) OR suspected split purchase (escalate to MD) | OM + FM | Within 2 BD of investigation |
| 6 | For confirmed split purchases: disciplinary action per HR policy, re-process procurement at correct tier, document incident | MD | Immediate |
| 7 | Maintain Split Purchase Incident Log | FM | Ongoing |

#### Controlled Version — Controls and Monitoring

| Step | Action | Responsible | Frequency |
|------|--------|-------------|-----------|
| 1 | ERP system applies automated split-purchase detection rules: flags multiple POs to same supplier, same category, within 30 days that cumulatively exceed a threshold. Flags PO values within 10% below any threshold limit. Flags same requester, same category, >2 POs in 30 days | ERP System | Automatic (real-time) |
| 2 | Procurement Officer reviews system-flagged transactions daily | PO | Daily |
| 3 | Procurement Manager reviews weekly summary of flagged transactions | PM | Weekly |
| 4 | Internal Auditor conducts monthly data analytics review: Benford's Law analysis on PO values, cluster analysis around threshold amounts, trend analysis by requester/supplier/category | Internal Auditor | Monthly |
| 5 | Investigate flagged transactions: formal investigation with documentation, interview requester, review all related POs, assess cumulative spend | Internal Auditor + PM | Within 5 BD of flag |
| 6 | Classification of finding: False positive — document and clear. Unintentional split — counseling and re-training. Deliberate split — disciplinary referral | Internal Auditor | Within 3 BD of investigation |
| 7 | For deliberate split purchases: refer to HR for disciplinary action (written warning to termination), re-process procurement at correct tier, report to MD and Board (if value exceeds UGX 50M), update fraud incident register | Internal Auditor + MD | Immediate |
| 8 | Quarterly Split Purchase Analysis Report to MD | Internal Auditor | Quarterly |

### 5.2 Vendor Conflict of Interest (COI) Management

#### Definition
A conflict of interest exists when an Awdeer employee involved in procurement has a personal, family, or financial relationship with a supplier that could influence — or could be perceived to influence — their procurement decisions.

#### COI Declaration Requirements

| Requirement | Lean | Controlled |
|-------------|------|-----------|
| **Who must declare** | All staff involved in procurement (requesting, approving, sourcing, receiving, paying) | ALL staff company-wide |
| **When — Annual** | January of each year | January of each year |
| **When — Per transaction** | For Tier 3+ procurements | For Tier 2+ procurements |
| **When — On joining** | Within first week of employment | Within first week of employment |
| **When — Change occurs** | Within 5 BD of any change in circumstances | Within 5 BD of any change in circumstances |
| **Supplier declarations** | At registration on ASL | At registration + annually |
| **Register maintained by** | Finance Manager | Compliance Officer |
| **Review** | MD reviews annually | Compliance Officer reviews quarterly; Internal Audit tests annually |

#### Relationships Requiring Declaration

| Relationship Type | Examples |
|-------------------|----------|
| Family — immediate | Spouse, children, parents, siblings |
| Family — extended | In-laws, uncles, aunts, cousins, nieces, nephews |
| Financial interest | Ownership, shareholding, directorship in supplier entity |
| Business relationship | Partnership, joint venture, business association outside Awdeer |
| Employment history | Previous employment with supplier (within last 5 years) |
| Personal friendship | Close personal friendship with supplier principals/key staff |
| Gift/hospitality | Any gift or hospitality received from supplier (regardless of value) |

#### COI Management Process

| Step | Action | Lean | Controlled |
|------|--------|------|-----------|
| 1 | Distribute COI declaration forms to all required staff | OM | Compliance Officer |
| 2 | Collect completed declarations (100% compliance target) | OM | Compliance Officer via ERP |
| 3 | Review all declarations for actual or potential conflicts | FM | Compliance Officer |
| 4 | For declared conflicts — determine management action: recuse person from relevant procurement decisions, assign alternative approver/buyer, add monitoring controls | FM + MD | Compliance Officer + PM + MD |
| 5 | For undisclosed conflicts discovered — treat as serious breach: immediate removal from procurement role, disciplinary investigation, review all transactions for influence | MD | Compliance + Internal Audit + MD |
| 6 | Maintain COI Register with all declarations and management actions | FM | Compliance Officer (ERP) |
| 7 | Annual report to MD on COI program | FM | Compliance Officer |
| 8 | Internal Audit tests COI controls annually | N/A (Lean) | Internal Auditor |

#### Supplier COI Controls

| Control | Description |
|---------|-------------|
| Director cross-reference | At registration, cross-reference supplier directors against all Awdeer employees, directors, and their declared family members |
| Bank account check | Flag suppliers with bank accounts in names matching any Awdeer employee |
| Address check | Flag suppliers with registered addresses matching any Awdeer employee's home address |
| Annual refresh | Repeat all cross-references annually as part of ASL review |
| Change notification | Suppliers must notify of any change in directors or ownership within 30 days |

### 5.3 Bid Rigging and Collusion Prevention

#### Definition
Bid rigging is an illegal practice where competing suppliers conspire to predetermine the outcome of a competitive bidding process. Forms include cover bidding (deliberately high bids), bid suppression (agreement not to bid), and market allocation (dividing markets among conspirators).

#### Red Flags for Bid Rigging

| Red Flag | Indicator |
|----------|-----------|
| Identical pricing patterns | Bids with identical or very similar pricing structures |
| Round-number bids | Multiple bids with suspiciously round numbers |
| Rotating winners | Pattern where suppliers take turns winning bids |
| Consistent runner-up | Same supplier consistently second-lowest by small margin |
| Geographic patterns | Suppliers appear to divide contracts by geography |
| Common details | Bids with similar formatting, errors, fonts, or letterhead styles |
| Last-minute withdrawals | Suppliers withdrawing bids just before evaluation |
| Subcontracting to losers | Winning supplier subcontracting to losing bidders |
| Common contact details | Different suppliers sharing phone numbers, emails, or addresses |
| Common directors | Different supplier companies with overlapping directors or shareholders |

#### Lean Version — Bid Integrity Controls

| Step | Action | Responsible | Frequency |
|------|--------|-------------|-----------|
| 1 | All quotation requests sent simultaneously to all invited suppliers | OM | Per procurement |
| 2 | Quotations requested in sealed envelopes for Tier 3+ | OM | Per procurement |
| 3 | All communication with suppliers during bidding through OM only | OM | Per procurement |
| 4 | Open quotations in presence of at least 2 people for Tier 2+ | OM + FM/MD | Per procurement |
| 5 | Check for common addresses, phone numbers, or contact persons across bidders | OM | Per procurement |
| 6 | Compare bid amounts — flag suspicious patterns (identical amounts, round numbers, consistent margins) | OM | Per procurement |
| 7 | Document reasons for supplier selection on Bid Comparison Sheet | OM | Per procurement |
| 8 | Rotate invited suppliers — no single supplier invited to more than 60% of bids in a category per year | OM | Ongoing |
| 9 | Maintain market price benchmarks — flag bids >15% above benchmark | OM | Per procurement |
| 10 | Report any suspected collusion to MD immediately | OM | As detected |

#### Controlled Version — Bid Integrity Controls

| Step | Action | Responsible | Frequency |
|------|--------|-------------|-----------|
| 1 | ERP-based RFQ/tender system: bids submitted electronically with timestamps, system locks out late bids, no visibility of other bids before closing | System / PO | Per procurement |
| 2 | Sealed bid process for manual submissions (Tier 4–5): numbered, sealed envelopes, stored in safe until opening date | PO | Per procurement |
| 3 | Formal Bid Opening Session for Tier 4–5: minimum 3 Tender Committee members present, bid opening minutes recorded, supplier representatives may attend (optional) | Tender Committee | Per Tier 4–5 procurement |
| 4 | Independent scoring: each evaluator scores independently before any group discussion, scores sealed and submitted to Procurement Manager, group discussion only after all scores submitted | Evaluators | Per procurement |
| 5 | Cross-reference supplier details across all bids: common directors (URSB search), common registered addresses, common phone numbers or emails, common bank accounts, common tax identification, similar company names/branding | PO + Compliance | Per procurement |
| 6 | Statistical analysis of bid prices: flag identical or near-identical prices, flag consistent percentage differences between bidders, compare against historical prices and market benchmarks, flag pricing anomalies using statistical models | Internal Auditor | Quarterly (analytical review) |
| 7 | Supplier rotation tracking: system reports on bid invitation frequency per supplier, flag suppliers consistently invited together, flag rotating winner patterns | PO + Internal Auditor | Quarterly |
| 8 | Communication controls: all supplier queries during bidding submitted in writing, responses shared with all bidders simultaneously (for RFQ addenda), no informal communication with bidders during evaluation | PM | Per procurement |
| 9 | Post-award monitoring: flag winning supplier subcontracting to losing bidder, monitor if losing bidders become "consultants" to winner, review supplier referral patterns | PM + Internal Auditor | Per major contract |
| 10 | Annual bid integrity audit: Internal Audit reviews sample of procurements for bid rigging indicators, report findings to MD and Board | Internal Auditor | Annually |

### 5.4 Fictitious Supplier Prevention

| Step | Action | Lean | Controlled |
|------|--------|------|-----------|
| 1 | Verify legal registration with URSB (online search or written confirmation) | OM | PO + Legal |
| 2 | Verify TIN with URA | OM / FM | PO / FM |
| 3 | Obtain bank confirmation letter (direct from bank, not supplier) | FM | FM (direct bank request) |
| 4 | Physical site visit for all new suppliers with expected annual spend >UGX 10M | OM | PO + PM |
| 5 | Cross-reference supplier address against Awdeer employee addresses | FM | Compliance Officer |
| 6 | Cross-reference supplier bank account name against employee names | FM | AP Officer + Compliance |
| 7 | Verify at least 2 of 3 trade references (direct contact, not referral from supplier) | OM | PO (documented calls/emails) |
| 8 | No payments to personal bank accounts for company suppliers | FM controls | ERP blocks personal accounts |
| 9 | New supplier setup requires independent approval (not by person requesting the purchase) | MD approves all | PM approves (not requester or PO who sourced) |
| 10 | Dormant supplier review: flag suppliers with no transactions in 12 months; require re-verification before any new PO | FM reviews list annually | System auto-flags; PO re-verifies |

### 5.5 Invoice Fraud Prevention

| Control | Lean | Controlled |
|---------|------|-----------|
| Three-way match (PO + GRN + Invoice) | FM performs manual match before every payment | ERP auto-match; exceptions flagged for manual review |
| Duplicate invoice detection | FM checks register before processing | ERP auto-detects duplicate invoice numbers, amounts, and dates |
| Invoice amount verification | FM compares against PO unit prices and totals | ERP compares; tolerance set at 5% or UGX 250,000 |
| Tax compliance check | FM verifies TIN on invoice, correct VAT, WHT applicability | ERP validates tax details; flags non-compliant invoices |
| Invoice sequence monitoring | FM notes sequential invoice numbers from same supplier | System flags gaps or anomalies in supplier invoice sequences |
| Altered invoice detection | FM inspects for signs of alteration (whiteout, mismatched fonts) | Digital invoices preferred; physical invoices scanned and verified |
| Credit note monitoring | FM reviews all credit notes for legitimacy | System requires approval workflow for credit note processing |

### 5.6 Kickback and Bribery Prevention

| Control | Description | Version |
|---------|-------------|---------|
| Anti-bribery policy | Company-wide policy prohibiting giving/receiving of bribes | Both |
| Gift/hospitality register | All gifts from suppliers reported and registered (any value above UGX 100,000) | Both |
| Gift limits | Maximum UGX 200,000 per gift; no cash gifts; gifts above limit returned to sender | Both |
| Staff rotation | Procurement staff rotated across supplier categories every 2 years | Controlled |
| Lifestyle monitoring | Flag procurement staff with lifestyle inconsistent with income (with appropriate privacy protections) | Controlled |
| Supplier commitment | Anti-corruption clause in all contracts and PO terms | Both |
| Whistleblower channel | Anonymous reporting channel for suspected kickbacks | Both |
| Surprise audits | Unannounced audits of procurement files and processes | Controlled |
| Declaration requirement | Staff must declare any approach/offer of kickback within 24 hours | Both |

### 5.7 Fraud Investigation and Response Protocol

| Step | Action | Lean | Controlled |
|------|--------|------|-----------|
| 1 | Fraud suspicion raised (detection, whistleblower, audit finding) | Any channel | Any channel |
| 2 | Initial assessment — is there a reasonable basis for investigation? | FM assesses | Internal Auditor assesses |
| 3 | Secure evidence: preserve documents, system records, emails; restrict access if needed | FM + OM | Internal Auditor + IT |
| 4 | Formal investigation: interview witnesses, review documentation, trace transactions, analyze patterns | FM + MD | Internal Auditor + Legal |
| 5 | Determine findings: no fraud found (close case), suspected fraud (continue), confirmed fraud (escalate) | MD decides | Investigation Committee decides |
| 6 | For confirmed fraud: quantify financial loss, identify all involved parties (staff and suppliers), refer staff to HR for disciplinary process, suspend/blacklist involved supplier(s), recover losses where possible, report to police if criminal threshold met | MD | MD + Board + Legal |
| 7 | Implement corrective actions: strengthen controls, address root cause, train staff | OM + FM | Internal Auditor + PM |
| 8 | Document lessons learned and update fraud risk register | FM | Internal Auditor |
| 9 | Report to Board (for material fraud — threshold: UGX 10M or any fraud by management) | MD reports | Internal Auditor reports independently |

### 5.8 Whistleblower Management

| Element | Detail |
|---------|--------|
| **Reporting channels** | Dedicated email address (whistleblower@awdeer.co.ug), phone hotline, sealed letter to MD or Board Chair, anonymous online form (Controlled version) |
| **Who can report** | Any employee, supplier, contractor, or member of the public |
| **Protection** | Full whistleblower protection per Awdeer policy and the Whistleblowers Protection Act, 2010 (Uganda) |
| **Anonymity** | Anonymous reports accepted and investigated equally |
| **Initial response** | Acknowledgment within 2 business days (non-anonymous reports) |
| **Investigation timeline** | Initial assessment within 5 business days; full investigation within 30 business days |
| **Confidentiality** | All reports treated as strictly confidential; need-to-know basis only |
| **Non-retaliation** | Retaliation against whistleblowers is a termination-level offence |
| **Record keeping** | All reports logged in confidential Whistleblower Register |
| **Reporting** | Quarterly summary to Board (anonymized) — number of reports, status, outcomes |

---

## 6. Controls and Approvals

| Control | Description | Version |
|---------|-------------|---------|
| Segregation of duties across procurement cycle | Requester, approver, buyer, receiver, and payer are separate individuals | Both |
| Automated split-purchase detection | System flags threshold-adjacent cumulative POs | Controlled |
| Monthly procurement pattern analysis | Finance reviews spend by supplier, category, and requester | Both |
| Annual conflict of interest declarations | 100% collection from all procurement-involved staff | Both |
| Sealed bid process | Physical or electronic sealed bids for Tier 3+ | Both |
| Independent bid scoring | Evaluators score without knowledge of other evaluators' scores | Controlled |
| Market price benchmarking | All bids compared against maintained price database | Both |
| New supplier independent approval | Supplier setup approved by person not involved in the procurement request | Both |
| Three-way match before payment | PO + GRN + Invoice matched before any payment | Both |
| Duplicate detection | System/manual check for duplicate invoices before processing | Both |
| Whistleblower channel | Anonymous reporting mechanism for procurement fraud | Both |
| Annual fraud risk assessment | Formal assessment of all procurement fraud risks | Both |
| Quarterly fraud controls report | Report to management on fraud control effectiveness | Controlled |
| Surprise audits | Unannounced audits of procurement processes and files | Controlled |

---

## 7. Documents and Forms

| Document | Purpose | Format |
|----------|---------|--------|
| Conflict of Interest Declaration — Staff | Annual staff COI declaration | Signed form |
| Conflict of Interest Declaration — Supplier | Supplier COI declaration at registration | Signed form |
| Conflict of Interest Register | Master register of all declared conflicts | Spreadsheet / ERP |
| Split Purchase Analysis Report | Monthly/quarterly analysis of split-purchase indicators | Report |
| Bid Integrity Checklist | Checklist for ensuring bid process integrity | Checklist |
| Fraud Investigation Report | Findings of fraud investigation | Confidential report |
| Whistleblower Report Form | Form for reporting suspected fraud | Physical/digital form |
| Whistleblower Case Register | Log of all whistleblower reports and outcomes | Confidential register |
| Procurement Fraud Risk Register | Assessment of all procurement fraud risks | Risk register |
| Gift and Hospitality Register | Log of all gifts/hospitality from suppliers | Register |
| Supplier Blacklist | List of blacklisted suppliers | Spreadsheet / ERP |

---

## 8. Key Performance Indicators

| KPI | Target | Measurement Method | Frequency |
|-----|--------|-------------------|-----------|
| COI declarations collected (% of required) | 100% | Declarations received / required | Annually |
| Split purchase flags investigated | 100% within 10 BD | Flags investigated / total flags | Monthly |
| Confirmed procurement fraud incidents | 0 | Incident count | Quarterly |
| Financial loss from procurement fraud | UGX 0 | Total confirmed fraud losses | Quarterly |
| Whistleblower reports investigated within SLA | 100% within 30 BD | Reports completed / total reports | Quarterly |
| Three-way match rate (first pass) | ≥ 85% | First-pass matches / total invoices | Monthly |
| Supplier verification completion (new suppliers) | 100% | Suppliers fully verified / new suppliers registered | Monthly |
| Bid integrity checks performed (Tier 3+) | 100% | Checks completed / Tier 3+ procurements | Quarterly |
| Procurement staff trained on fraud prevention | 100% | Staff trained / procurement-involved staff | Annually |
| Surprise audits conducted | ≥ 4 per year | Audits conducted | Annually |
| Gift register compliance | 100% | Gifts registered / gifts declared (spot checks) | Quarterly |
| Fraud risk assessment completed | 1 per year | Assessment completed (yes/no) | Annually |

---

## 9. Annual Fraud Risk Assessment Process

| Step | Action | Lean | Controlled |
|------|--------|------|-----------|
| 1 | Review previous year's fraud incidents and near-misses | FM + OM | Internal Auditor + PM |
| 2 | Identify all procurement fraud risks (using fraud risk categories in this SOP) | FM + OM | Internal Auditor + PM + FM + Legal |
| 3 | Assess likelihood and impact of each risk | FM + OM | Fraud risk workshop |
| 4 | Evaluate existing controls — are they operating effectively? | FM + OM | Internal Auditor tests controls |
| 5 | Identify gaps and new risks | FM + OM | Workshop output |
| 6 | Develop action plan to address gaps | OM | PM + Internal Auditor |
| 7 | MD approves action plan | MD | MD (Board for material risks) |
| 8 | Update Procurement Fraud Risk Register | FM | Internal Auditor |
| 9 | Implement actions and track progress | OM | PM + Internal Auditor track |
| 10 | Report results to management | FM to MD | Internal Auditor to MD + Board |

---

## 10. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | February 2026 | System Design | Initial version |

---

*Awdeer Investments Limited*
*SOP: PRO-FRD-001 — Procurement Fraud Prevention Controls*
*Version 1.0 — February 2026*
