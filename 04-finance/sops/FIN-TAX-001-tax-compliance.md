# Tax Compliance

**Document ID:** FIN-TAX-001
**Version:** 1.0
**Effective Date:** 2026-02-20
**Process Owner:** Financial Controller
**Department:** Finance & Accounting
**Classification:** Internal

---

## 1. Purpose

To establish comprehensive procedures for managing all tax obligations of Awdeer Investments Limited in compliance with Ugandan tax law. This SOP covers VAT, WHT, PAYE, NSSF, Corporate Income Tax (CIT), and other statutory obligations, ensuring timely filing, accurate computation, and audit readiness.

---

## 2. Scope

Covers all tax obligations applicable to Awdeer Investments Limited and its subsidiaries across all business lines and branches. Governed by:
- Income Tax Act, Cap 340
- Value Added Tax Act, Cap 349
- Tax Procedures Code Act, 2014
- NSSF Act, Cap 222
- Local Governments Act (Local Service Tax)
- East African Community Customs Management Act (for imports)

---

## 3. RACI Matrix

| Activity | Tax Accountant | Senior Accountant | Financial Controller | CFO | External Tax Advisor |
|----------|---------------|-------------------|---------------------|-----|---------------------|
| VAT computation & filing | R | C | A | I | C (annually) |
| WHT computation & remittance | R | C | A | I | — |
| PAYE computation & filing | R | C (payroll data) | A | I | — |
| NSSF computation & remittance | R | C (payroll data) | A | I | — |
| CIT provisional payments | R | C | A | A | C |
| CIT annual return | R | C | R | A | R |
| Tax audit management | C | C | R | A | R |
| Transfer pricing documentation | C | — | R | A | R |
| EFRIS compliance | R | R | A | I | — |
| Tax planning & strategy | C | — | C | A | R |

---

## 4. Inputs and Outputs

### Inputs
- Sales invoices (EFRIS) and credit notes
- Purchase invoices (EFRIS verified)
- Payroll data (gross salaries, allowances, deductions)
- Import documentation (customs entries, duty assessments)
- Supplier payment records (for WHT)
- Bank interest certificates
- Prior period tax returns and assessments
- Financial statements

### Outputs
- Monthly VAT return filed on URA e-Tax
- Monthly WHT return and certificates
- Monthly PAYE return filed on URA e-Tax
- Monthly NSSF return and payment
- Quarterly CIT provisional tax payments
- Annual CIT return
- Tax compliance certificates
- Tax audit files and documentation

---

## 5. URA Filing Calendar

| Tax Type | Filing Deadline | Payment Deadline | Frequency | URA Portal |
|----------|----------------|-----------------|-----------|-----------|
| VAT | 15th of following month | 15th of following month | Monthly | e-Tax |
| WHT | 15th of following month | 15th of following month | Monthly | e-Tax |
| PAYE | 15th of following month | 15th of following month | Monthly | e-Tax |
| NSSF | 15th of following month | 15th of following month | Monthly | NSSF portal |
| LST | Annually (employer deducts monthly) | Varies by district | Annual | District |
| CIT Provisional — Q1 | End of 3rd month (31 March) | 31 March | Quarterly | e-Tax |
| CIT Provisional — Q2 | End of 6th month (30 June) | 30 June | Quarterly | e-Tax |
| CIT Provisional — Q3 | End of 9th month (30 September) | 30 September | Quarterly | e-Tax |
| CIT Provisional — Q4 | End of 12th month (31 December) | 31 December | Quarterly | e-Tax |
| CIT Annual Return | Within 6 months of year-end (30 June) | 30 June | Annual | e-Tax |
| EFRIS Compliance | Real-time (per transaction) | N/A | Per transaction | EFRIS |

---

## 6. VAT Workflow

### 6.1 VAT Rates

| Category | Rate | Examples |
|----------|------|---------|
| Standard rate | 18% | Most goods and services |
| Zero-rated | 0% | Exports, supplies to diplomats, educational materials |
| Exempt | N/A | Unprocessed food, financial services, insurance, medical, education |
| Deemed | 18% | Imported services (reverse charge) |

### 6.2 VAT Computation Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Extract all sales invoices for the month from EFRIS/ERP | Tax Accountant | BD1 |
| 2 | Calculate Output VAT (sales x 18%) | Tax Accountant | BD2 |
| 3 | Extract all purchase invoices with valid tax invoices / EFRIS numbers | Tax Accountant | BD2 |
| 4 | Calculate Input VAT (eligible purchases x 18%) | Tax Accountant | BD3 |
| 5 | Perform input VAT apportionment if mixed supplies exist | Tax Accountant | BD3 |
| 6 | Calculate Net VAT (Output VAT - Input VAT) | Tax Accountant | BD4 |
| 7 | Prepare VAT return in URA e-Tax format | Tax Accountant | BD5 |
| 8 | Financial Controller reviews and approves VAT return | Financial Controller | BD6 |
| 9 | File VAT return on URA e-Tax portal | Tax Accountant | By 15th |
| 10 | Make payment via bank transfer to URA | Treasury Officer | By 15th |
| 11 | Post VAT payment journal in GL | Tax Accountant | Same day |
| 12 | File return confirmation and payment receipt | Tax Accountant | Same day |

### 6.3 Input VAT Apportionment

Where the Company makes both taxable and exempt supplies:

```
Recoverable Input VAT = Total Input VAT x (Taxable Supplies / Total Supplies)
```

- Apportionment reviewed quarterly
- Annual adjustment at year-end based on actual proportions
- Directly attributable input VAT allocated 100% to taxable or exempt

### 6.4 VAT on Imports

- Import VAT paid at customs clearance
- Claimed as input VAT in the month of import
- Supported by customs entry and payment receipt

---

## 7. WHT Workflow

### 7.1 Step-by-Step Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Identify all payments subject to WHT during the month | Tax Accountant | Ongoing |
| 2 | Calculate WHT at applicable rate (see table below) | AP Officer / Tax Accountant | At invoice posting |
| 3 | Deduct WHT from supplier payment | AP Officer | At payment |
| 4 | Generate WHT certificate for each supplier | Tax Accountant | Within 5 BD of payment |
| 5 | Deliver WHT certificate to supplier | Tax Accountant | Within 5 BD |
| 6 | Prepare WHT return for the month | Tax Accountant | BD5 |
| 7 | Financial Controller reviews and approves | Financial Controller | BD6 |
| 8 | File WHT return on URA e-Tax | Tax Accountant | By 15th |
| 9 | Remit WHT to URA | Treasury Officer | By 15th |
| 10 | Post WHT remittance in GL (debit 2024, credit bank) | Tax Accountant | Same day |

### 7.2 WHT Rates Summary

| Payment Type | Resident | Non-Resident |
|-------------|----------|--------------|
| Professional / service fees | 6% | 15% |
| Goods purchases (above UGX 1,000,000 cumulative per month) | 6% | 6% |
| Interest | 15% | 15% |
| Dividends | 10% | 15% |
| Rent | 6% | 15% |
| Royalties | 6% | 15% |
| Commissions (non-employees) | 6% | 15% |
| Management fees | 6% | 15% |
| Insurance premiums | N/A | 15% |

### 7.3 WHT Certificates

- Must be issued on the URA-prescribed format
- Must contain: supplier name, TIN, payment amount, WHT rate, WHT amount, date
- Sequentially numbered
- Copy retained by the Company; original to supplier
- Certificate register maintained monthly

---

## 8. PAYE Workflow

### 8.1 Monthly PAYE Brackets

| Monthly Chargeable Income (UGX) | Rate |
|--------------------------------|------|
| 0 — 235,000 | 0% |
| 235,001 — 335,000 | 10% |
| 335,001 — 410,000 | 20% |
| 410,001 — 10,000,000 | 30% |
| Above 10,000,000 | 30% + 10% surcharge on excess |

### 8.2 PAYE Computation Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Receive payroll summary from HR (gross pay, allowances, deductions) | Tax Accountant | BD1 |
| 2 | Calculate chargeable income per employee (gross less NSSF employee) | Tax Accountant | BD2 |
| 3 | Apply PAYE brackets to each employee | Tax Accountant | BD2 |
| 4 | Aggregate total PAYE for the month | Tax Accountant | BD3 |
| 5 | Prepare PAYE return in URA e-Tax format | Tax Accountant | BD5 |
| 6 | Financial Controller reviews and approves | Financial Controller | BD6 |
| 7 | File PAYE return on URA e-Tax | Tax Accountant | By 15th |
| 8 | Remit PAYE to URA via Tax Account | Treasury Officer | By 15th |
| 9 | Post PAYE journal: Debit 2021 (PAYE Payable), Credit Bank | Tax Accountant | Same day |

### 8.3 Benefits in Kind

The following are taxable:
- Company car for personal use (market value of benefit)
- Employer-provided housing (15% of employment income)
- Low-interest loans (benefit = difference between market rate and actual rate)
- Employer-paid insurance premiums (above UGX 4,000,000 per year)

---

## 9. NSSF Workflow

### 9.1 Contribution Rates

| Party | Rate | Base |
|-------|------|------|
| Employer | 10% | Gross salary |
| Employee | 5% | Gross salary |
| **Total** | **15%** | **Gross salary** |

### 9.2 Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Calculate NSSF contributions per employee from payroll data | Tax Accountant | BD2 |
| 2 | Prepare NSSF schedule (employer + employee contributions) | Tax Accountant | BD3 |
| 3 | Upload contribution schedule to NSSF portal | Tax Accountant | By 15th |
| 4 | Make payment to NSSF | Treasury Officer | By 15th |
| 5 | Post journal: Debit 2022 (NSSF Employer) + Debit 2023 (NSSF Employee), Credit Bank | Tax Accountant | Same day |
| 6 | File payment confirmation | Tax Accountant | Same day |

### 9.3 Important Notes

- NSSF contributions are mandatory for all employees aged 16–55
- Late payment attracts a penalty of 5% per month
- Employer must register all new employees within 30 days of hiring
- Annual NSSF member statements must be verified

---

## 10. Corporate Income Tax (CIT)

### 10.1 Tax Rate

Standard rate: **30%** of chargeable income.

### 10.2 Provisional Tax

- Paid in **quarterly installments** based on estimated chargeable income for the year
- Each installment = 25% of estimated annual tax
- If actual tax exceeds provisional by >10%, a penalty of 20% on the shortfall applies

### 10.3 CIT Computation Process

| Step | Action | Owner | Timeline |
|------|--------|-------|----------|
| 1 | Prepare quarterly estimate of chargeable income | Tax Accountant + FC | Before quarter-end |
| 2 | Calculate provisional tax installment | Tax Accountant | Before due date |
| 3 | CFO approves provisional tax payment | CFO | Before due date |
| 4 | File provisional return and make payment | Tax Accountant | By quarter-end |
| 5 | At year-end, prepare full CIT computation | Tax Accountant + External Advisor | Within 3 months of year-end |
| 6 | Reconcile provisional payments to final CIT | Tax Accountant | Within 4 months |
| 7 | File annual return on URA e-Tax | Tax Accountant | By 30 June |
| 8 | Pay balance due (or note overpayment / credit) | Treasury Officer | By 30 June |

### 10.4 Key Deductions and Disallowances

**Allowable Deductions:**
- All expenses wholly and exclusively incurred in the production of income
- Capital allowances (depreciation per URA rates)
- Bad debts (with evidence of collection efforts)
- NSSF employer contributions
- Donations to approved organizations (up to 5% of chargeable income)
- Start-up costs (amortized over 5 years)

**Non-Deductible Expenses:**
- Fines and penalties
- Private / personal expenses
- Donations to non-approved organizations
- Income tax itself
- Provisions (unless specifically permitted)
- Entertainment expenses (50% disallowed)

### 10.5 Transfer Pricing

- Transactions with related parties must be at arm's length
- Transfer pricing documentation required if related party transactions exceed UGX 500,000,000 annually
- Documentation must be maintained and available within 30 days of URA request
- Country-by-country reporting not yet required in Uganda but may apply if parent entity threshold is met

---

## 11. Local Service Tax (LST)

| Monthly Income (UGX) | Annual LST (UGX) |
|----------------------|------------------|
| Below 100,000 | Nil |
| 100,000 — 200,000 | 10,000 |
| 200,001 — 300,000 | 20,000 |
| 300,001 — 400,000 | 30,000 |
| 400,001 — 500,000 | 40,000 |
| Above 500,000 | 100,000 |

- Deducted from employee salary
- Paid to the local government authority
- Company also pays own LST as an entity (UGX 100,000 per annum per trading location)

---

## 12. EFRIS Compliance

### 12.1 Requirements

- All sales invoices must be generated and transmitted through EFRIS
- All credit notes and debit notes transmitted through EFRIS
- EFRIS number must appear on every invoice
- ERP must be integrated with EFRIS (or EFRIS standalone used for manual invoices)

### 12.2 Process

| Step | Action | Owner |
|------|--------|-------|
| 1 | Ensure ERP-EFRIS integration is functional (daily check) | IT + Tax Accountant |
| 2 | All sales transactions transmitted in real-time | AR Officer |
| 3 | Failed transmissions investigated and resolved within 24 hours | Tax Accountant |
| 4 | Monthly EFRIS reconciliation (EFRIS totals vs ERP totals) | Tax Accountant |
| 5 | Report discrepancies to Financial Controller | Tax Accountant |

### 12.3 Penalties for Non-Compliance

- UGX 20,000,000 fine or imprisonment
- URA may close business premises
- VAT input claims may be denied for non-EFRIS invoices

---

## 13. Tax Audit Readiness

### 13.1 Documentation to Maintain

| Document | Retention Period | Location |
|----------|-----------------|----------|
| All tax returns filed | 7 years | Digital archive + e-Tax confirmations |
| Payment receipts (URA) | 7 years | Digital archive |
| VAT invoices (sales and purchases) | 7 years | EFRIS + ERP |
| WHT certificates (issued and received) | 7 years | Digital archive |
| Payroll records and PAYE computations | 7 years | HR + Finance archive |
| NSSF contribution schedules | 7 years | Digital archive |
| CIT computations and supporting schedules | 7 years | Finance archive |
| Transfer pricing documentation | 7 years | Finance archive |
| Import/customs documentation | 7 years | Procurement + Finance archive |
| Board resolutions (tax-related) | Permanent | Company Secretary |

### 13.2 Tax Audit Process

| Step | Action | Owner |
|------|--------|-------|
| 1 | Notification received from URA (audit letter) | CFO |
| 2 | Engage external tax advisor | CFO |
| 3 | Assemble tax audit file per scope of audit | Tax Accountant + External Advisor |
| 4 | Designate single point of contact for URA auditors | Financial Controller |
| 5 | All information requests channeled through designated contact | Financial Controller |
| 6 | No verbal admissions; all responses in writing | Legal |
| 7 | Review draft assessment with external advisor | CFO + External Advisor |
| 8 | File objection within 45 days if assessment is disputed | External Advisor |
| 9 | Resolution (negotiation, TAT, or court) | CFO + External Advisor + Legal |

### 13.3 Annual Tax Health Check

- External tax advisor conducts annual tax health check (January–February)
- Scope: review of all tax positions, filings, and potential exposures
- Report presented to CFO and Board Finance Committee
- Remedial actions tracked and resolved before external audit

---

## 14. Controls and Approvals

| Control | Description |
|---------|-------------|
| Filing deadline calendar | Automated reminders set 10 days, 5 days, and 1 day before each deadline |
| Dual review | All tax returns reviewed by Financial Controller before filing |
| Reconciliation | Monthly reconciliation of tax accounts (GL vs returns filed vs payments made) |
| EFRIS reconciliation | Monthly EFRIS vs ERP reconciliation |
| WHT certificate tracking | Register maintained; certificates issued within 5 BD |
| Tax provision | CIT provision updated quarterly based on latest estimates |
| Segregation | Tax Accountant prepares; Financial Controller reviews; CFO approves payments |

---

## 15. Documents and Forms

| Document | Reference |
|----------|-----------|
| Payment Voucher (for tax payments) | FIN-TPL-001 |
| Invoice Template (EFRIS-compliant) | FIN-TPL-004 |

---

## 16. KPIs

| KPI | Target |
|-----|--------|
| Filing timeliness | 100% on-time (zero late filings) |
| Penalties incurred | UGX 0 |
| WHT certificate issuance | Within 5 BD of payment |
| EFRIS compliance | 100% of invoices transmitted |
| Tax audit findings | Zero material findings |
| VAT accuracy (return vs GL) | 100% reconciled |
| CIT provisional accuracy | Within 10% of final tax |
| Tax health check completion | Annually by February |

---

## 17. Lean Version

For early-stage operations:

- Tax Accountant role combined with Senior Accountant
- Manual EFRIS invoice generation (standalone app)
- VAT and PAYE computed and filed by Senior Accountant
- CIT estimated conservatively at 30% of accounting profit
- External tax advisor engaged for annual CIT return and health check
- Quarterly tax compliance review with CFO

---

## 18. Controlled Version

Full process as described above, plus:

- Dedicated Tax Accountant
- Fully integrated ERP-EFRIS system
- Automated tax calendar with escalation workflows
- Tax risk register maintained and reviewed quarterly
- Transfer pricing study conducted annually by external advisor
- Proactive tax planning sessions (CFO + External Advisor) semi-annually
- Digital tax document management with indexed retrieval
- Real-time tax liability dashboard

---

## 19. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2026-02-20 | Financial Controller | Initial release |

---

*This is a controlled document. Unauthorized reproduction or distribution is prohibited.*
