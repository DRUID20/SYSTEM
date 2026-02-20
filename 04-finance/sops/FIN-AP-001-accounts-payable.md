# Accounts Payable

**Document ID:** FIN-AP-001
**Version:** 1.0
**Effective Date:** 2026-02-20
**Process Owner:** Financial Controller
**Department:** Finance & Accounting
**Classification:** Internal

---

## 1. Purpose

To establish end-to-end procedures for managing accounts payable at Awdeer Investments Limited, covering supplier onboarding, purchase order matching, invoice processing, payment runs, and payment approvals. This SOP ensures that the Company pays only for goods and services properly received, at the correct amounts, within agreed terms, while maintaining strong controls against fraud and error.

---

## 2. Scope

Covers all supplier payments across all business lines (Energy, Real Estate, Logistics, Retail, Services) and branches. Includes trade payables, expense reimbursements, and intercompany payables. Excludes payroll (covered under HR) and tax payments (covered under FIN-TAX-001).

---

## 3. RACI Matrix

| Activity | AP Officer | Procurement | Requesting Dept | Financial Controller | CFO |
|----------|-----------|-------------|----------------|---------------------|-----|
| Supplier onboarding | R | C | C | A | I |
| PO matching | R | C | — | A | — |
| Invoice processing | R | — | C (if disputed) | A | — |
| Payment batch preparation | R | — | — | A | — |
| Payment authorization | — | — | — | R (up to limit) | A |
| Payment execution | R | — | — | C | A |
| Supplier statement reconciliation | R | — | — | A | I |
| AP aging review | R | — | — | A | I |

---

## 4. Inputs and Outputs

### Inputs
- Supplier onboarding form (FIN-TPL-002)
- Purchase orders (from Procurement)
- Goods Received Notes (GRN) / Service Completion Certificates
- Supplier invoices (tax invoices)
- Payment vouchers (FIN-TPL-001)
- Supplier contracts and terms

### Outputs
- Approved supplier master record in ERP
- Processed and coded invoices in AP subledger
- Payment vouchers (approved)
- Payment runs (EFT / cheque / mobile money)
- AP aging report (FIN-TPL-007)
- WHT certificates issued to suppliers
- Supplier statements reconciliation

---

## 5. Supplier Onboarding

### 5.1 Step-by-Step Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Requesting department or Procurement submits Supplier Onboarding Form (FIN-TPL-002) | Requester | Before first transaction |
| 2 | AP Officer verifies completeness and supporting documents | AP Officer | 1 BD |
| 3 | Duplicate check performed in ERP (name, TIN, bank details) | AP Officer | Same day |
| 4 | Sanctions / debarment screening | AP Officer | 1 BD |
| 5 | Bank account verification (require cancelled cheque or bank confirmation letter) | AP Officer | 2 BD |
| 6 | Supplier master record created in ERP | AP Officer | 1 BD after checks |
| 7 | Financial Controller approves new supplier in ERP | Financial Controller | 1 BD |
| 8 | Requester and Procurement notified | AP Officer | Same day |

### 5.2 Required Documents

| Document | Required |
|----------|----------|
| Certificate of Incorporation / Business Registration | Yes |
| Trading license | Yes |
| TIN certificate (URA) | Yes |
| VAT registration certificate (if applicable) | Yes |
| Bank account details (cancelled cheque or bank letter) | Yes |
| Completed Supplier Onboarding Form (FIN-TPL-002) | Yes |
| Tax clearance certificate | For contracts > UGX 50,000,000 |
| NSSF compliance certificate | For labour-intensive contracts |
| Company profile / product catalogue | Recommended |

### 5.3 Supplier Master Data Maintenance

- Supplier records reviewed **annually** for accuracy
- Changes to supplier bank details require:
  - Written request on supplier letterhead
  - Verbal confirmation to a known contact number (NOT from the change request)
  - Financial Controller approval
  - This is a critical fraud control; any deviation is escalated to CFO

---

## 6. Purchase Order (PO) Matching

### 6.1 Matching Types

| Type | Documents Matched | Used For |
|------|------------------|----------|
| **2-Way Match** | PO + Invoice | Services where GRN is impractical |
| **3-Way Match** | PO + GRN + Invoice | Goods and materials procurement |

### 6.2 Matching Tolerance

| Item | Tolerance |
|------|-----------|
| Quantity variance | +/- 5% or 2 units (whichever is lower) |
| Price variance | +/- 2% or UGX 50,000 (whichever is lower) |
| Total value variance | UGX 100,000 maximum |

Invoices exceeding tolerance must be investigated and approved by Financial Controller before processing.

### 6.3 3-Way Match Process

| Step | Action | Owner |
|------|--------|-------|
| 1 | Purchase Order raised and approved per procurement policy | Procurement |
| 2 | Goods delivered; GRN prepared by receiving department | Warehouse / Requester |
| 3 | Supplier invoice received by AP | AP Officer |
| 4 | AP Officer matches Invoice to PO and GRN | AP Officer |
| 5 | If match within tolerance: invoice coded and posted to AP subledger | AP Officer |
| 6 | If mismatch: flag for investigation; contact Procurement / Supplier | AP Officer |
| 7 | Resolution documented; corrected invoice or approved variance | AP Officer + Procurement |
| 8 | Matched invoice queued for payment | AP Officer |

### 6.4 Non-PO Invoices

Certain invoices may not have a PO:
- Utilities (electricity, water, internet)
- Rent (per lease agreement)
- Insurance premiums
- Professional fees (with engagement letter)
- Regulatory fees

These require **department head approval** and Financial Controller sign-off before processing.

---

## 7. Invoice Processing

### 7.1 Invoice Receipt and Registration

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Invoice received (email / hard copy) and date-stamped | AP Officer | Same day |
| 2 | Invoice reviewed for completeness and tax compliance | AP Officer | 1 BD |
| 3 | EFRIS validation check (verify invoice is EFRIS-compliant) | AP Officer | Same day |
| 4 | Invoice coded to correct GL account, cost center, and business line | AP Officer | 1 BD |
| 5 | Invoice matched to PO/GRN (per Section 6) | AP Officer | 1 BD |
| 6 | Invoice posted to AP subledger | AP Officer | Same day after match |
| 7 | Scanned copy filed in document management system | AP Officer | Same day |

### 7.2 Invoice Coding Rules

| Expense Type | GL Account Class | Cost Center |
|-------------|-----------------|-------------|
| Direct materials / inventory | 5xxx (COGS) | Business line operations |
| Staff-related expenses | 6000–6062 | Department cost center |
| Premises costs | 6100–6152 | Location cost center |
| Marketing | 6200–6201 | Business line sales |
| Travel | 6210–6213 | Traveler's department |
| Professional fees | 7020–7040 | Corporate |
| Capital items (> UGX 500,000, > 12 months life) | 1500–1620 | Asset register |

### 7.3 WHT on Supplier Invoices

| Payment Type | WHT Rate | Deduction |
|-------------|----------|-----------|
| Service fees (resident) | 6% | Deducted from payment; WHT certificate issued |
| Service fees (non-resident) | 15% | Deducted from payment; WHT certificate issued |
| Goods purchase (above UGX 1,000,000) | 6% | Deducted from payment; WHT certificate issued |
| Rent | 6% | Deducted from payment |

AP Officer must calculate WHT at invoice posting and create the WHT payable entry.

---

## 8. Payment Runs

### 8.1 Payment Schedule

| Payment Type | Frequency | Day |
|-------------|-----------|-----|
| Supplier payments (regular) | Bi-weekly | Every 2nd and 4th Thursday |
| Urgent / ad-hoc payments | As needed | Any day with CFO approval |
| Statutory payments (PAYE, NSSF, VAT, WHT) | Monthly | By 15th of following month |
| Rent | Monthly | Per lease agreement |
| Utilities | Monthly | On receipt of invoice |

### 8.2 Payment Run Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | AP Officer generates list of invoices due for payment | AP Officer | 2 BD before payment run |
| 2 | AP Officer prepares Payment Vouchers (FIN-TPL-001) for each payment | AP Officer | 1 BD before payment run |
| 3 | Payment vouchers submitted with full supporting documents | AP Officer | 1 BD before payment run |
| 4 | Financial Controller reviews and approves payment batch | Financial Controller | Payment run day |
| 5 | CFO approves payments above threshold (see 8.3) | CFO | Payment run day |
| 6 | Payment batch uploaded to internet banking / cheques prepared | Treasury Officer | Payment run day |
| 7 | Two signatories authorize payment in banking system | Signatories | Payment run day |
| 8 | Payment confirmation downloaded and matched to vouchers | AP Officer | 1 BD after payment |
| 9 | WHT certificates generated and sent to suppliers | AP Officer | Within 5 BD |
| 10 | Payment posted in GL | AP Officer | Same day as payment |

### 8.3 Payment Approval Authority

| Payment Amount (UGX) | Approver(s) |
|----------------------|-------------|
| Up to 1,000,000 | Financial Controller |
| 1,000,001 — 5,000,000 | Financial Controller |
| 5,000,001 — 20,000,000 | CFO |
| 20,000,001 — 100,000,000 | CFO + CEO |
| Above 100,000,000 | Board resolution |

### 8.4 Payment Methods

| Method | Used For | Controls |
|--------|---------|----------|
| EFT / RTGS | Supplier payments > UGX 1,000,000 | Dual authorization on banking platform |
| Cheque | Where EFT not possible | Two signatories; cheque register maintained |
| Mobile Money | Small payments < UGX 500,000 | Pre-approved by Financial Controller; daily limit |
| Cash | Not permitted for supplier payments | Exception only with CFO written approval |

---

## 9. Supplier Statement Reconciliation

| Step | Action | Owner | Frequency |
|------|--------|-------|-----------|
| 1 | Request statements from top 20 suppliers (by value) | AP Officer | Monthly |
| 2 | Reconcile supplier statement to AP subledger balance | AP Officer | Monthly by BD7 |
| 3 | Investigate and resolve discrepancies | AP Officer | Within 5 BD |
| 4 | Document reconciliation and file | AP Officer | Monthly |
| 5 | Financial Controller reviews reconciliations | Financial Controller | Monthly |

---

## 10. Controls and Approvals

| Control | Description |
|---------|-------------|
| Supplier onboarding approval | New suppliers approved by Financial Controller |
| Bank detail change verification | Verbal callback to known number + FC approval |
| PO matching | 3-way match for goods; 2-way match for services |
| Segregation of duties | AP Officer cannot approve payments or sign cheques |
| Payment dual authorization | Two bank signatories for all payments |
| Invoice duplication check | System check for duplicate invoice numbers per supplier |
| WHT compliance | WHT calculated and deducted before payment |
| Approval limits | Enforced per authority matrix |
| Supplier statement reconciliation | Monthly for top 20 suppliers |
| AP aging review | Weekly by Financial Controller |

---

## 11. Documents and Forms

| Document | Reference |
|----------|-----------|
| Supplier Onboarding Form | FIN-TPL-002 |
| Payment Voucher | FIN-TPL-001 |
| AP Aging Report | FIN-TPL-007 |
| Invoice Template (for reference) | FIN-TPL-004 |

---

## 12. KPIs

| KPI | Target |
|-----|--------|
| Days Payable Outstanding (DPO) | 30–45 days (align with terms) |
| Invoice processing time | < 3 BD from receipt to posting |
| 3-way match rate (first pass) | > 90% |
| Early payment discount capture rate | > 80% (where offered) |
| Duplicate payment rate | 0% |
| WHT compliance rate | 100% |
| Supplier onboarding time | < 5 BD |
| AP aging > 60 days (excluding disputes) | < 5% of total AP |

---

## 13. Lean Version

For early-stage or low-volume operations:

- Simplified supplier form (basic details + bank + TIN)
- 2-way matching for all invoices (PO + invoice)
- Weekly payment run (Thursdays)
- Financial Controller approves all payments (single approver up to UGX 5M)
- Quarterly supplier statement reconciliation (top 10)
- Manual WHT calculation and certificate preparation

---

## 14. Controlled Version

Full process as described above, plus:

- ERP-enforced 3-way matching with automated tolerance checks
- Automated payment approval workflows with electronic audit trail
- Supplier self-service portal for invoice submission and payment status
- Automated duplicate invoice detection (by amount, date, and supplier)
- Supplier performance scoring (delivery, invoice accuracy, compliance)
- Annual supplier audit (top 10 suppliers by spend)
- Procurement card program for low-value purchases with monthly reconciliation
- Early payment discount optimization (dynamic discounting)

---

## 15. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2026-02-20 | Financial Controller | Initial release |

---

*This is a controlled document. Unauthorized reproduction or distribution is prohibited.*
