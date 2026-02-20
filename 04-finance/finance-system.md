# Awdeer Investments Limited — Finance System (Part C: CFO-Level)

**Document ID:** FIN-SYS-001
**Version:** 1.0
**Effective Date:** 2026-02-20
**Owner:** Chief Financial Officer (CFO)
**Classification:** Confidential

---

## 1. Purpose

This document is the master reference for the entire Finance function of Awdeer Investments Limited ("the Company"), a Ugandan registered holding company operating across five business lines: Energy, Real Estate, Logistics, Retail, and Services. It defines the Chart of Accounts, cost center architecture, and maps every finance sub-process to its governing policy, SOP, and template.

---

## 2. Scope

Applies to all entities, branches, and business lines under the Awdeer Investments Limited group. All subsidiaries and branches must adopt this system without deviation unless a written exception is approved by the CFO and Board Finance Committee.

---

## 3. Reporting Currency and Standards

| Item | Detail |
|------|--------|
| Functional Currency | Uganda Shillings (UGX) |
| Presentation Currency | UGX (USD used for investor/donor reporting where required) |
| Accounting Standards | International Financial Reporting Standards (IFRS) as adopted in Uganda |
| Tax Authority | Uganda Revenue Authority (URA) |
| Financial Year | 1 January to 31 December |
| Statutory Auditor | Appointed annually by Board resolution |

---

## 4. Chart of Accounts (COA) Design

### 4.1 Account Numbering Convention

The COA uses an **8-digit structure**:

```
[C]-[AAAA]-[BB]-[LL]
 |    |      |    |
 |    |      |    +-- Location/Branch Code (01-99)
 |    |      +------- Business Line Code (01-06)
 |    +-------------- Account Code (4 digits)
 +------------------- Class (1 digit)
```

**Class Codes:**

| Class | Range | Category |
|-------|-------|----------|
| 1 | 1000–1999 | Assets |
| 2 | 2000–2999 | Liabilities |
| 3 | 3000–3999 | Equity |
| 4 | 4000–4999 | Revenue |
| 5 | 5000–5999 | Cost of Goods Sold (COGS) |
| 6 | 6000–6999 | Operating Expenses |
| 7 | 7000–7999 | Administrative & Other Expenses |
| 8 | 8000–8999 | Other Income & Expenses |

### 4.2 Business Line Codes

| Code | Business Line | Abbreviation |
|------|--------------|--------------|
| 01 | Corporate / Holding Company | CORP |
| 02 | Energy | ENRG |
| 03 | Real Estate | REST |
| 04 | Logistics | LGST |
| 05 | Retail | RETL |
| 06 | Services | SRVC |

### 4.3 Branch/Location Codes

| Code | Location |
|------|----------|
| 01 | Head Office — Kampala |
| 02 | Kampala Branch 2 |
| 03 | Jinja |
| 04 | Mbarara |
| 05 | Gulu |
| 06 | Mbale |
| 10 | Warehouse / Depot (Namanve) |
| 99 | Intercompany / Elimination |

### 4.4 Detailed Chart of Accounts

#### Class 1: Assets (1000–1999)

**Current Assets (1000–1499)**

| Account | Name | Type |
|---------|------|------|
| 1000 | Cash on Hand — UGX | Current Asset |
| 1001 | Cash on Hand — USD | Current Asset |
| 1010 | Petty Cash — Head Office | Current Asset |
| 1011 | Petty Cash — Branch | Current Asset |
| 1050 | Bank — Main Operating Account (UGX) | Current Asset |
| 1051 | Bank — Main Operating Account (USD) | Current Asset |
| 1052 | Bank — Payroll Account (UGX) | Current Asset |
| 1053 | Bank — Tax Account (UGX) | Current Asset |
| 1054 | Bank — Collections Account (UGX) | Current Asset |
| 1055 | Bank — Fixed Deposit (UGX) | Current Asset |
| 1056 | Bank — Fixed Deposit (USD) | Current Asset |
| 1060 | Mobile Money Float — MTN MoMo | Current Asset |
| 1061 | Mobile Money Float — Airtel Money | Current Asset |
| 1100 | Accounts Receivable — Trade | Current Asset |
| 1101 | Accounts Receivable — Intercompany | Current Asset |
| 1105 | Allowance for Doubtful Debts | Contra Asset |
| 1110 | Notes Receivable | Current Asset |
| 1120 | Staff Advances & Loans | Current Asset |
| 1125 | Director Advances | Current Asset |
| 1130 | VAT Receivable (Input VAT) | Current Asset |
| 1131 | WHT Receivable (Certificates) | Current Asset |
| 1140 | Prepaid Rent | Current Asset |
| 1141 | Prepaid Insurance | Current Asset |
| 1142 | Prepaid Licenses & Subscriptions | Current Asset |
| 1143 | Other Prepayments | Current Asset |
| 1150 | Inventory — Raw Materials | Current Asset |
| 1151 | Inventory — Work in Progress | Current Asset |
| 1152 | Inventory — Finished Goods | Current Asset |
| 1153 | Inventory — Fuel & Lubricants | Current Asset |
| 1154 | Inventory — Spare Parts | Current Asset |
| 1160 | Deposits & Guarantees | Current Asset |
| 1170 | Accrued Revenue | Current Asset |
| 1199 | Other Current Assets | Current Asset |

**Non-Current Assets (1500–1999)**

| Account | Name | Type |
|---------|------|------|
| 1500 | Land | Non-Current Asset |
| 1510 | Buildings | Non-Current Asset |
| 1511 | Accumulated Depreciation — Buildings | Contra Asset |
| 1520 | Motor Vehicles | Non-Current Asset |
| 1521 | Accumulated Depreciation — Motor Vehicles | Contra Asset |
| 1530 | Plant & Machinery | Non-Current Asset |
| 1531 | Accumulated Depreciation — Plant & Machinery | Contra Asset |
| 1540 | Office Furniture & Fittings | Non-Current Asset |
| 1541 | Accumulated Depreciation — Furniture & Fittings | Contra Asset |
| 1550 | Computer Equipment & IT | Non-Current Asset |
| 1551 | Accumulated Depreciation — Computer Equipment | Contra Asset |
| 1560 | Solar/Energy Equipment | Non-Current Asset |
| 1561 | Accumulated Depreciation — Solar/Energy Equipment | Contra Asset |
| 1570 | Leasehold Improvements | Non-Current Asset |
| 1571 | Accumulated Depreciation — Leasehold Improvements | Contra Asset |
| 1580 | Capital Work in Progress (CWIP) | Non-Current Asset |
| 1600 | Intangible Assets — Software | Non-Current Asset |
| 1601 | Accumulated Amortization — Software | Contra Asset |
| 1610 | Intangible Assets — Licenses & Permits | Non-Current Asset |
| 1611 | Accumulated Amortization — Licenses | Contra Asset |
| 1620 | Goodwill | Non-Current Asset |
| 1700 | Investment in Subsidiaries | Non-Current Asset |
| 1710 | Long-Term Investments | Non-Current Asset |
| 1720 | Investment Property | Non-Current Asset |
| 1800 | Right-of-Use Assets (IFRS 16) | Non-Current Asset |
| 1801 | Accumulated Depreciation — ROU Assets | Contra Asset |
| 1900 | Deferred Tax Asset | Non-Current Asset |

#### Class 2: Liabilities (2000–2999)

**Current Liabilities (2000–2499)**

| Account | Name | Type |
|---------|------|------|
| 2000 | Accounts Payable — Trade | Current Liability |
| 2001 | Accounts Payable — Intercompany | Current Liability |
| 2010 | Accrued Expenses — General | Current Liability |
| 2011 | Accrued Salaries & Wages | Current Liability |
| 2012 | Accrued Bonus & Commissions | Current Liability |
| 2020 | VAT Payable (Output VAT) | Current Liability |
| 2021 | PAYE Payable | Current Liability |
| 2022 | NSSF Payable (Employer) | Current Liability |
| 2023 | NSSF Payable (Employee) | Current Liability |
| 2024 | WHT Payable | Current Liability |
| 2025 | Local Service Tax (LST) Payable | Current Liability |
| 2026 | Corporate Income Tax Payable | Current Liability |
| 2030 | Advances from Customers | Current Liability |
| 2040 | Short-Term Loans — Bank | Current Liability |
| 2041 | Current Portion of Long-Term Debt | Current Liability |
| 2050 | Dividends Payable | Current Liability |
| 2060 | Provision for Warranty | Current Liability |
| 2070 | Deferred Revenue — Current | Current Liability |
| 2080 | Lease Liability — Current (IFRS 16) | Current Liability |
| 2099 | Other Current Liabilities | Current Liability |

**Non-Current Liabilities (2500–2999)**

| Account | Name | Type |
|---------|------|------|
| 2500 | Long-Term Bank Loans | Non-Current Liability |
| 2510 | Shareholder Loans | Non-Current Liability |
| 2520 | Bonds / Debentures | Non-Current Liability |
| 2530 | Lease Liability — Non-Current (IFRS 16) | Non-Current Liability |
| 2540 | Deferred Revenue — Non-Current | Non-Current Liability |
| 2550 | Provision for Gratuity / End of Service | Non-Current Liability |
| 2560 | Deferred Tax Liability | Non-Current Liability |
| 2599 | Other Non-Current Liabilities | Non-Current Liability |

#### Class 3: Equity (3000–3999)

| Account | Name | Type |
|---------|------|------|
| 3000 | Ordinary Share Capital | Equity |
| 3010 | Preference Share Capital | Equity |
| 3050 | Share Premium | Equity |
| 3100 | Retained Earnings | Equity |
| 3110 | Current Year Profit / (Loss) | Equity |
| 3200 | Revaluation Reserve | Equity |
| 3210 | Foreign Currency Translation Reserve | Equity |
| 3300 | Dividends Declared | Contra Equity |
| 3400 | Non-Controlling Interest | Equity |

#### Class 4: Revenue (4000–4999)

| Account | Name | Business Line |
|---------|------|---------------|
| 4000 | Revenue — General / Other | CORP |
| 4100 | Revenue — Solar Product Sales | ENRG |
| 4101 | Revenue — Solar Installation Services | ENRG |
| 4102 | Revenue — Solar Maintenance Contracts | ENRG |
| 4103 | Revenue — Energy Trading / Power Sales | ENRG |
| 4200 | Revenue — Property Sales | REST |
| 4201 | Revenue — Rental Income | REST |
| 4202 | Revenue — Property Management Fees | REST |
| 4203 | Revenue — Development Fees | REST |
| 4300 | Revenue — Freight / Haulage | LGST |
| 4301 | Revenue — Warehousing | LGST |
| 4302 | Revenue — Clearing & Forwarding | LGST |
| 4303 | Revenue — Last-Mile Delivery | LGST |
| 4400 | Revenue — Retail Sales (General Merchandise) | RETL |
| 4401 | Revenue — Wholesale Sales | RETL |
| 4402 | Revenue — E-Commerce Sales | RETL |
| 4500 | Revenue — Consulting & Advisory Fees | SRVC |
| 4501 | Revenue — IT Services | SRVC |
| 4502 | Revenue — Training & Capacity Building | SRVC |
| 4503 | Revenue — Outsourced Staffing | SRVC |
| 4900 | Intercompany Revenue (Elimination) | CORP |

#### Class 5: Cost of Goods Sold / Direct Costs (5000–5999)

| Account | Name | Business Line |
|---------|------|---------------|
| 5000 | COGS — General | CORP |
| 5100 | COGS — Solar Equipment Purchases | ENRG |
| 5101 | COGS — Installation Labour | ENRG |
| 5102 | COGS — Batteries & Inverters | ENRG |
| 5200 | COGS — Construction Materials | REST |
| 5201 | COGS — Contractor & Subcontractor Costs | REST |
| 5202 | COGS — Land Acquisition Costs | REST |
| 5300 | COGS — Fuel & Lubricants | LGST |
| 5301 | COGS — Vehicle Maintenance & Repairs | LGST |
| 5302 | COGS — Driver Wages (Direct) | LGST |
| 5303 | COGS — Third-Party Haulage | LGST |
| 5400 | COGS — Merchandise Purchases | RETL |
| 5401 | COGS — Packaging Materials | RETL |
| 5402 | COGS — Freight-In | RETL |
| 5500 | COGS — Direct Consultant Costs | SRVC |
| 5501 | COGS — Direct Labour | SRVC |
| 5502 | COGS — Project Materials | SRVC |
| 5900 | Intercompany COGS (Elimination) | CORP |
| 5950 | Inventory Write-Down / Shrinkage | ALL |

#### Class 6: Operating Expenses (6000–6999)

| Account | Name |
|---------|------|
| 6000 | Salaries & Wages |
| 6010 | NSSF Employer Contribution (10%) |
| 6011 | Gratuity / End of Service Benefit |
| 6020 | Staff Medical Insurance |
| 6021 | Group Life / Personal Accident Insurance |
| 6030 | Staff Training & Development |
| 6040 | Recruitment Costs |
| 6050 | Staff Welfare & Meals |
| 6060 | Allowances — Transport |
| 6061 | Allowances — Housing |
| 6062 | Allowances — Communication / Airtime |
| 6100 | Rent — Office Premises |
| 6101 | Rent — Warehouse / Yard |
| 6110 | Utilities — Electricity |
| 6111 | Utilities — Water |
| 6112 | Utilities — Internet & Telecom |
| 6120 | Office Supplies & Stationery |
| 6130 | Cleaning & Sanitation |
| 6140 | Security Services |
| 6150 | Repairs & Maintenance — Building |
| 6151 | Repairs & Maintenance — Equipment |
| 6152 | Repairs & Maintenance — Vehicles |
| 6200 | Marketing & Advertising |
| 6201 | Branding & Signage |
| 6210 | Travel — Domestic |
| 6211 | Travel — International |
| 6212 | Accommodation & Hotels |
| 6213 | Per Diem & Subsistence |
| 6220 | Entertainment & Hospitality |
| 6300 | Vehicle Running Costs (Admin fleet) |
| 6301 | Fuel — Admin Vehicles |
| 6310 | Insurance — Motor Vehicle |
| 6311 | Insurance — Property |
| 6312 | Insurance — Professional Indemnity |
| 6313 | Insurance — General / Other |
| 6400 | Software Licenses & Subscriptions |
| 6401 | IT Support & Maintenance |
| 6410 | Depreciation Expense |
| 6411 | Amortization Expense |
| 6420 | Bad Debt Expense |
| 6430 | Bank Charges & Fees |
| 6431 | Mobile Money Charges |
| 6440 | Courier & Postage |
| 6450 | Printing & Photocopying |
| 6460 | Subscriptions & Memberships |

#### Class 7: Administrative & Other Expenses (7000–7999)

| Account | Name |
|---------|------|
| 7000 | Directors' Fees & Sitting Allowances |
| 7010 | Audit Fees — External |
| 7020 | Legal & Professional Fees |
| 7030 | Consulting Fees |
| 7040 | Accounting & Tax Advisory Fees |
| 7050 | Company Secretary Fees |
| 7060 | Regulatory & Compliance Fees |
| 7070 | Licenses & Permits (Non-Capitalised) |
| 7080 | AGM & Meeting Expenses |
| 7100 | Penalties & Fines |
| 7110 | Donations & CSR |
| 7120 | Sponsorships |
| 7200 | Foreign Exchange Loss |
| 7300 | Restructuring Costs |
| 7400 | Impairment Loss |

#### Class 8: Other Income & Expenses (8000–8999)

| Account | Name |
|---------|------|
| 8000 | Interest Income — Bank Deposits |
| 8001 | Interest Income — Staff Loans |
| 8010 | Dividend Income |
| 8020 | Gain on Disposal of Assets |
| 8030 | Rental Income — Non-Core |
| 8040 | Foreign Exchange Gain |
| 8050 | Miscellaneous Income |
| 8100 | Interest Expense — Bank Loans |
| 8101 | Interest Expense — Shareholder Loans |
| 8102 | Interest on Lease Liabilities (IFRS 16) |
| 8110 | Loss on Disposal of Assets |
| 8200 | Corporate Income Tax Expense |
| 8210 | Deferred Tax Expense / (Benefit) |

---

## 5. Cost Center Structure

### 5.1 Cost Center Numbering

```
[BL]-[DEPT]-[LOC]
 |     |      |
 |     |      +-- Location (01-99)
 |     +--------- Department (100-999)
 +--------------- Business Line (01-06)
```

### 5.2 Departments

| Code | Department |
|------|-----------|
| 100 | Executive / General Management |
| 200 | Finance & Accounting |
| 210 | Treasury |
| 300 | Human Resources |
| 400 | Operations |
| 410 | Procurement / Supply Chain |
| 500 | Sales & Marketing |
| 600 | Information Technology |
| 700 | Legal & Compliance |
| 800 | Projects / PMO |
| 900 | Shared Services / Corporate |

### 5.3 Cost Center Examples

| Cost Center | Description |
|-------------|-------------|
| 01-100-01 | Corporate — Executive — Head Office |
| 01-200-01 | Corporate — Finance — Head Office |
| 02-400-01 | Energy — Operations — Head Office |
| 02-500-03 | Energy — Sales — Jinja |
| 03-400-01 | Real Estate — Operations — Head Office |
| 03-800-04 | Real Estate — Projects — Mbarara |
| 04-400-10 | Logistics — Operations — Namanve Depot |
| 05-500-01 | Retail — Sales — Head Office |
| 06-400-01 | Services — Operations — Head Office |

### 5.4 Profit Centers (Business Lines)

Each business line is also a profit center, enabling P&L reporting by:
- Revenue and direct cost per business line
- Allocated shared costs (based on headcount, revenue, or square footage)
- Contribution margin by business line
- Net profit by business line after full allocation

---

## 6. Finance Sub-Processes Map

### 6.1 Policies

| Document ID | Title | Path |
|-------------|-------|------|
| FIN-POL-001 | Accounting Policies Manual | `policies/FIN-POL-001-accounting-policies.md` |

### 6.2 Standard Operating Procedures (SOPs)

| Document ID | Title | Path |
|-------------|-------|------|
| FIN-MEC-001 | Month-End Close Process | `sops/FIN-MEC-001-month-end-close.md` |
| FIN-BNK-001 | Bank & Cash Management | `sops/FIN-BNK-001-bank-cash-management.md` |
| FIN-AR-001 | Accounts Receivable | `sops/FIN-AR-001-accounts-receivable.md` |
| FIN-AP-001 | Accounts Payable | `sops/FIN-AP-001-accounts-payable.md` |
| FIN-TAX-001 | Tax Compliance | `sops/FIN-TAX-001-tax-compliance.md` |
| FIN-RPT-001 | Management Reporting | `sops/FIN-RPT-001-management-reporting.md` |
| FIN-AST-001 | Fixed Assets | `sops/FIN-AST-001-fixed-assets.md` |
| FIN-CTL-001 | Internal Controls | `sops/FIN-CTL-001-internal-controls.md` |

### 6.3 Templates & Forms

| Document ID | Title | Path |
|-------------|-------|------|
| FIN-TPL-001 | Payment Voucher | `templates/FIN-TPL-001-payment-voucher.md` |
| FIN-TPL-002 | Supplier Onboarding Form | `templates/FIN-TPL-002-supplier-onboarding-form.md` |
| FIN-TPL-003 | Customer Onboarding Form | `templates/FIN-TPL-003-customer-onboarding-form.md` |
| FIN-TPL-004 | Invoice Template | `templates/FIN-TPL-004-invoice-template.md` |
| FIN-TPL-005 | Credit Note Template | `templates/FIN-TPL-005-credit-note-template.md` |
| FIN-TPL-006 | AR Aging Report | `templates/FIN-TPL-006-ar-aging-report.md` |
| FIN-TPL-007 | AP Aging Report | `templates/FIN-TPL-007-ap-aging-report.md` |
| FIN-TPL-008 | Bank Reconciliation | `templates/FIN-TPL-008-bank-reconciliation.md` |
| FIN-TPL-009 | Petty Cash Log | `templates/FIN-TPL-009-petty-cash-log.md` |
| FIN-TPL-010 | Month-End Checklist | `templates/FIN-TPL-010-month-end-checklist.md` |
| FIN-TPL-011 | Management Accounts Pack | `templates/FIN-TPL-011-management-accounts-pack.md` |
| FIN-TPL-012 | Asset Register | `templates/FIN-TPL-012-asset-register.md` |
| FIN-TPL-013 | Chart of Accounts | `templates/FIN-TPL-013-chart-of-accounts.md` |

---

## 7. Finance Organization Structure

```
Chief Financial Officer (CFO)
|
+-- Financial Controller
|   +-- Senior Accountant
|   +-- Accounts Receivable Officer
|   +-- Accounts Payable Officer
|   +-- Tax Accountant
|   +-- Fixed Assets Accountant
|   +-- Branch Accountants (x4)
|
+-- Treasury Manager
|   +-- Treasury Officer
|   +-- Cash Management Officer
|
+-- FP&A Manager
|   +-- Budget Analyst
|   +-- Financial Analyst
|
+-- Internal Audit Manager (dotted line to Board)
    +-- Internal Auditor(s)
```

---

## 8. Key Financial Controls Framework

| Control Area | Primary Control | Frequency |
|-------------|----------------|-----------|
| Cash & Bank | Daily bank reconciliation | Daily |
| Accounts Receivable | Weekly aging review | Weekly |
| Accounts Payable | 3-way matching before payment | Per transaction |
| Payroll | Dual authorization | Monthly |
| Fixed Assets | Physical verification | Annually |
| Intercompany | Monthly reconciliation | Monthly |
| Tax | Filing calendar compliance | Per schedule |
| Month-End Close | BD10 close target | Monthly |
| Financial Statements | Board review | Quarterly |
| External Audit | Statutory audit | Annually |

---

## 9. Approval Authority Matrix (Summary)

| Transaction Type | Up to UGX 1M | UGX 1M–5M | UGX 5M–20M | UGX 20M–100M | Above UGX 100M |
|-----------------|-------------|-----------|------------|--------------|----------------|
| Operational Expenses | Line Manager | HOD | CFO | CEO | Board |
| Capital Expenditure | — | HOD + CFO | CFO + CEO | CEO + Board | Board |
| Payment Release | AP Officer | Financial Controller | CFO | CEO + CFO | Board + CFO |
| Write-Offs | — | Financial Controller | CFO | CEO | Board |
| Contracts / Commitments | — | HOD | CFO + Legal | CEO | Board |

---

## 10. Technology Stack

| Function | Recommended Tool |
|----------|-----------------|
| Accounting / ERP | QuickBooks Enterprise / Odoo / Tally |
| Payroll | Integrated with ERP or BambooHR |
| Tax Filing | URA e-Tax Portal (EFRIS for e-invoicing) |
| Banking | Bank Internet Banking Portals |
| Reporting | Excel + Power BI / Google Data Studio |
| Document Management | Google Drive / SharePoint |
| Expense Management | ERP module or Expensify |

---

## 11. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2026-02-20 | CFO | Initial release |

---

*This is a controlled document. Unauthorized reproduction or distribution is prohibited. Printed copies are uncontrolled.*
