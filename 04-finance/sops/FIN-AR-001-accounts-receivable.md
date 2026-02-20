# Accounts Receivable

**Document ID:** FIN-AR-001
**Version:** 1.0
**Effective Date:** 2026-02-20
**Process Owner:** Financial Controller
**Department:** Finance & Accounting
**Classification:** Internal

---

## 1. Purpose

To establish end-to-end procedures for managing accounts receivable at Awdeer Investments Limited, covering customer onboarding and KYC, credit assessment, invoicing, collections, dunning, and bad debt management. This SOP ensures revenue is collected efficiently while managing credit risk.

---

## 2. Scope

Covers all trade receivables across all business lines (Energy, Real Estate, Logistics, Retail, Services) and branches. Applies to all credit sales; cash/POS sales are excluded from credit management but included in invoicing.

---

## 3. RACI Matrix

| Activity | AR Officer | Sales Team | Financial Controller | CFO | Legal |
|----------|-----------|------------|---------------------|-----|-------|
| Customer onboarding/KYC | R | C | A | I | C |
| Credit limit setting | C | R (request) | A | A (above UGX 50M) | — |
| Invoice generation | R | C (data) | I | — | — |
| Collections follow-up | R | C | A | I | — |
| Dunning process | R | I | A | I | C |
| Bad debt write-off | C | — | R | A | C |
| AR aging review | R | — | A | I | — |
| Credit note issuance | R | R (request) | A | I | — |

---

## 4. Inputs and Outputs

### Inputs
- Customer onboarding form (FIN-TPL-003)
- Sales contracts / purchase orders from customers
- Delivery notes / proof of delivery / completion certificates
- Credit limit request from Sales
- Payment receipts (bank, mobile money, cash)
- Customer correspondence (disputes, queries)

### Outputs
- Approved customer master record in ERP
- Tax-compliant invoices (FIN-TPL-004) via EFRIS
- Credit notes (FIN-TPL-005)
- AR aging report (FIN-TPL-006)
- Collections report
- Bad debt provision schedule
- Customer statements

---

## 5. Customer Onboarding and KYC

### 5.1 Step-by-Step Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Sales team submits Customer Onboarding Form (FIN-TPL-003) | Sales Team | Before first transaction |
| 2 | AR Officer verifies completeness of form and supporting documents | AR Officer | 1 BD |
| 3 | KYC checks performed (see 5.2) | AR Officer | 2 BD |
| 4 | Credit assessment performed (see Section 6) | AR Officer + FC | 3 BD |
| 5 | Customer master record created in ERP with approved credit terms | AR Officer | 1 BD after approval |
| 6 | Sales team notified of approved credit terms | AR Officer | Same day |

### 5.2 KYC Requirements

**Corporate Customers:**

| Document | Required |
|----------|----------|
| Certificate of Incorporation / Registration | Yes |
| Trading license | Yes |
| TIN certificate (URA) | Yes |
| VAT registration certificate (if registered) | Yes |
| Company directors / authorized persons list | Yes |
| Physical address verification | Yes |
| Bank reference letter | For credit above UGX 20,000,000 |
| Trade references (minimum 2) | For credit above UGX 20,000,000 |
| Latest audited accounts | For credit above UGX 50,000,000 |

**Individual Customers:**

| Document | Required |
|----------|----------|
| National ID / Passport | Yes |
| TIN (if applicable) | Yes |
| Proof of address (utility bill / LC letter) | Yes |
| Employment / business verification | For credit sales |

### 5.3 Sanctions and PEP Screening

- All customers with credit facilities above UGX 50,000,000 screened against:
  - Uganda Financial Intelligence Authority (FIA) guidance
  - UN Sanctions List
  - Internal Politically Exposed Persons (PEP) register
- Screening refreshed annually for active credit customers

---

## 6. Credit Limit Setting

### 6.1 Credit Assessment Criteria

| Factor | Weight | Assessment |
|--------|--------|-----------|
| Payment history (existing customers) | 30% | Analysis of past 12 months payment behavior |
| Financial strength | 25% | Review of financial statements, if available |
| Trade references | 15% | Feedback from two trade references |
| Business relationship value | 15% | Annual revenue potential |
| Industry/sector risk | 15% | Sector-specific default rates |

### 6.2 Credit Limit Approval Authority

| Credit Limit (UGX) | Approver |
|--------------------|----------|
| Up to 5,000,000 | AR Officer + Financial Controller |
| 5,000,001 — 20,000,000 | Financial Controller |
| 20,000,001 — 50,000,000 | CFO |
| 50,000,001 — 200,000,000 | CFO + CEO |
| Above 200,000,000 | Board Finance Committee |

### 6.3 Standard Credit Terms

| Customer Category | Payment Terms | Credit Period |
|-------------------|--------------|---------------|
| Government / KCCA / Agencies | Net 60 | 60 days |
| Large Corporates | Net 30 | 30 days |
| SMEs | Net 14 — Net 30 | 14–30 days |
| Retail / Walk-in | Cash / Proforma | 0 days |
| New customers (first 3 months) | Proforma / Net 14 | 0–14 days |

### 6.4 Credit Limit Review

- Credit limits reviewed **semi-annually** or upon:
  - Customer request for increase
  - Deterioration in payment behavior (2+ late payments)
  - Change in customer financial condition
  - Significant increase in order volume

---

## 7. Invoicing

### 7.1 Invoice Generation Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Delivery note / completion certificate / timesheet received from Operations | Operations | Within 2 BD of delivery |
| 2 | AR Officer verifies delivery documentation against contract/PO | AR Officer | 1 BD |
| 3 | Invoice generated in ERP using FIN-TPL-004 template | AR Officer | 1 BD after verification |
| 4 | Invoice transmitted through EFRIS to URA | ERP/EFRIS | Automatic |
| 5 | Invoice dispatched to customer (email + hard copy if required) | AR Officer | Same day |
| 6 | Invoice recorded in AR subledger | ERP | Automatic |

### 7.2 Invoice Requirements (URA / EFRIS Compliant)

Every invoice must contain:
- Company name, address, TIN, and VAT number
- Customer name, address, TIN (if registered)
- EFRIS invoice number (system-generated)
- Invoice date and due date
- Description of goods/services
- Quantity, unit price, and total (UGX)
- VAT amount (18%) separately stated
- Payment terms
- Bank account details for payment

### 7.3 Credit Notes

| Scenario | Process |
|----------|---------|
| Goods returned | Credit note raised upon receipt of returned goods and inspection |
| Pricing error | Credit note raised upon approval by Financial Controller |
| Service shortfall | Credit note raised upon documented complaint and approval |
| Duplicate invoice | Credit note raised and original voided |

**Approval:** All credit notes require Financial Controller approval. Credit notes above UGX 5,000,000 require CFO approval.

Credit notes must be transmitted through EFRIS.

---

## 8. Collections and Dunning

### 8.1 Collections Workflow

| Days Past Due | Action | Owner |
|---------------|--------|-------|
| Due date | Send payment reminder (email/SMS) 3 days before due date | AR Officer |
| 1–7 days | Courtesy call + email reminder | AR Officer |
| 8–14 days | Second follow-up call; escalate to Sales relationship manager | AR Officer + Sales |
| 15–30 days | **First formal demand letter** (email + hard copy) | AR Officer |
| 31–45 days | Account placed on credit hold (no further deliveries) | Financial Controller |
| 46–60 days | **Second formal demand letter**; meeting with customer requested | Financial Controller |
| 61–90 days | **Final demand letter** (7-day notice); legal action warning | Financial Controller + Legal |
| 91+ days | Hand over to Legal for recovery; consider debt collection agency | CFO + Legal |

### 8.2 Dunning Letter Schedule

| Letter | Timing | Tone | Signer |
|--------|--------|------|--------|
| Reminder | 3 days before due | Friendly | AR Officer |
| 1st Demand | 15 days past due | Firm but polite | Financial Controller |
| 2nd Demand | 46 days past due | Urgent | CFO |
| Final Demand | 61 days past due | Legal notice | Legal / CFO |

### 8.3 Payment Arrangements

- For customers experiencing genuine financial difficulty, a structured payment plan may be agreed
- Payment plans require CFO approval
- Plans must be documented in writing with the customer
- Default on a payment plan triggers immediate escalation to legal

---

## 9. Bad Debt Management

### 9.1 Provision for Expected Credit Losses (IFRS 9)

| Aging Bucket | ECL Rate | Action |
|-------------|----------|--------|
| Current (0–30 days) | 1% | Standard monitoring |
| 31–60 days | 5% | Active follow-up |
| 61–90 days | 15% | Credit hold; formal demand |
| 91–180 days | 40% | Legal action initiated |
| 181–365 days | 75% | Debt recovery / write-down |
| Over 365 days | 100% | Write-off consideration |

### 9.2 Bad Debt Write-Off Process

| Step | Action | Owner |
|------|--------|-------|
| 1 | AR Officer prepares write-off recommendation with full history | AR Officer |
| 2 | Confirmation that all collection efforts exhausted (demand letters, legal) | Financial Controller |
| 3 | Write-off approval obtained per authority matrix | Approver |
| 4 | Journal entry: Debit 6420 (Bad Debt Expense), Credit 1105 (Allowance) | Senior Accountant |
| 5 | Customer account flagged in ERP (no future credit) | AR Officer |
| 6 | Supporting documentation archived | AR Officer |

### 9.3 Write-Off Approval Authority

| Amount (UGX) | Approver |
|-------------|----------|
| Up to 2,000,000 | Financial Controller |
| 2,000,001 — 10,000,000 | CFO |
| 10,000,001 — 50,000,000 | CEO + CFO |
| Above 50,000,000 | Board |

### 9.4 Tax Treatment (Uganda)

- Bad debts are deductible for income tax purposes only if:
  - The debt was previously included in income
  - Reasonable steps were taken to collect (demand letters, legal action)
  - The debt is written off in the books
- URA may require evidence of legal proceedings for large write-offs

---

## 10. AR Aging Review

- AR aging report (FIN-TPL-006) generated **weekly** by AR Officer
- Reviewed by Financial Controller every **Monday**
- Aging >60 days reported to CFO **weekly**
- Full AR aging review in monthly Management Accounts Pack
- Customer concentration analysis quarterly (no single customer >20% of AR)

---

## 11. Controls and Approvals

| Control | Description |
|---------|-------------|
| KYC completion | No credit sales without approved customer master |
| Credit limit enforcement | ERP blocks orders exceeding credit limit |
| Invoice accuracy | Invoices verified against delivery documentation before issuance |
| EFRIS compliance | All invoices transmitted through EFRIS |
| Credit note approval | All credit notes approved by Financial Controller or CFO |
| Segregation of duties | AR Officer cannot approve write-offs or credit notes |
| Aged debt escalation | Automatic escalation at defined aging thresholds |
| Monthly AR reconciliation | Subledger must agree to GL control account |

---

## 12. Documents and Forms

| Document | Reference |
|----------|-----------|
| Customer Onboarding Form | FIN-TPL-003 |
| Invoice Template | FIN-TPL-004 |
| Credit Note Template | FIN-TPL-005 |
| AR Aging Report | FIN-TPL-006 |

---

## 13. KPIs

| KPI | Target |
|-----|--------|
| Days Sales Outstanding (DSO) | < 35 days |
| AR > 90 days as % of total AR | < 5% |
| Bad debt write-off as % of revenue | < 1% |
| Invoice accuracy rate | > 99% |
| Customer onboarding time | < 5 BD |
| Collection effectiveness index | > 90% |
| EFRIS compliance | 100% |

---

## 14. Lean Version

For early-stage or low-volume operations:

- Simplified customer onboarding (TIN + ID + basic form)
- Credit limits set by CFO for all customers
- Manual invoice generation (Word/Excel template via EFRIS)
- Weekly collections follow-up by Finance Manager
- Monthly aging review
- Bad debt provision calculated quarterly

---

## 15. Controlled Version

Full process as described above, plus:

- ERP-enforced credit limits with automated blocking
- Automated dunning workflows (system-generated letters/emails)
- Real-time AR dashboard with aging by business line and customer
- Weekly collections meetings (AR Officer, Sales, Financial Controller)
- Credit insurance for customers with limits above UGX 200,000,000
- External credit checks for large customers (CRB query)
- Quarterly customer profitability analysis (revenue vs cost to collect)

---

## 16. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2026-02-20 | Financial Controller | Initial release |

---

*This is a controlled document. Unauthorized reproduction or distribution is prohibited.*
