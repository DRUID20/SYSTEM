# Awdeer Investments Limited — KPI & Dashboard Pack

## Overview

This document defines all Key Performance Indicators (KPIs) by department, reporting cadence, data sources, and dashboard layouts for management visibility.

---

## 1. Finance KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| Revenue | Total revenue across all business lines | Per budget | Monthly | GL / Sales module | CFO |
| Gross Profit Margin | (Revenue - COGS) / Revenue × 100 | > 30% (ASSUMPTION) | Monthly | GL | CFO |
| Net Profit Margin | Net Income / Revenue × 100 | > 10% (ASSUMPTION) | Monthly | GL | CFO |
| Operating Cash Flow | Cash generated from operations | Positive | Monthly | Cash flow statement | CFO |
| Current Ratio | Current Assets / Current Liabilities | > 1.5 | Monthly | Balance Sheet | CFO |
| Days Sales Outstanding (DSO) | Avg AR / (Revenue / 365) | < 45 days | Monthly | AR module | CFO |
| Days Payable Outstanding (DPO) | Avg AP / (COGS / 365) | 30–60 days | Monthly | AP module | CFO |
| Budget Variance | (Actual - Budget) / Budget × 100 | < 10% variance | Monthly | GL vs Budget | CFO |
| Month-End Close Time | Business days to close books | ≤ BD 10 | Monthly | Finance team | CFO |
| Tax Filing Compliance | % of filings submitted on time | 100% | Monthly | Tax calendar | CFO |
| Petty Cash Variance | Unaccounted petty cash / Total float × 100 | 0% | Weekly | Petty cash log | CFO |
| Bad Debt Ratio | Bad debt write-off / Total revenue × 100 | < 1% | Quarterly | AR module | CFO |

## 2. Procurement KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| PR-to-PO Cycle Time | Days from PR submission to PO issuance | < 5 days | Monthly | Procurement module | Operations |
| PO Compliance Rate | % of purchases with valid PO | 100% | Monthly | AP vs PO matching | Operations |
| Cost Savings | Negotiated savings vs initial quotes | > 5% | Quarterly | Bid comparisons | Operations |
| Supplier On-Time Delivery | % of deliveries on/before due date | > 90% | Monthly | GRN dates vs PO dates | Operations |
| Supplier Defect Rate | % of goods received with quality issues | < 2% | Monthly | GRN rejections | Operations |
| Emergency Purchase Rate | % of purchases without proper PR | < 5% | Monthly | Procurement module | Operations |
| Supplier Concentration | % of spend with top 3 suppliers | < 40% | Quarterly | AP analysis | Operations |

## 3. Inventory & Logistics KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| Inventory Turnover | COGS / Average Inventory | > 6x (ASSUMPTION) | Monthly | GL + Stock module | Operations |
| Stock Accuracy | Counted qty vs system qty match rate | > 98% | Monthly | Cycle counts | Operations |
| Shrinkage Rate | Value lost / Total inventory value × 100 | < 1% | Monthly | Variance reports | Operations |
| Stockout Rate | # items out of stock / Total SKUs × 100 | < 3% | Weekly | Stock module | Operations |
| Dead Stock % | Stock with no movement > 90 days / Total | < 5% | Monthly | Stock aging | Operations |
| Order Fulfillment Rate | Orders shipped on time / Total orders × 100 | > 95% | Monthly | Dispatch records | Operations |
| Fleet Utilization | Active trips / Available vehicle-days × 100 | > 75% | Monthly | Trip logs | Operations |
| Fuel Cost per KM | Total fuel cost / Total KM driven | Trend down | Monthly | Vehicle logbooks | Operations |

## 4. Sales & Marketing KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| Pipeline Value | Total value of active opportunities | > 3x monthly target | Weekly | CRM | Sales |
| Conversion Rate | Won deals / Total qualified leads × 100 | > 25% | Monthly | CRM | Sales |
| Average Deal Size | Total revenue / Number of deals | Trend up | Monthly | CRM / Sales module | Sales |
| Customer Acquisition Cost (CAC) | Total sales+marketing cost / New customers | Trend down | Quarterly | GL + CRM | Sales |
| Customer Retention Rate | (Customers end - New) / Customers start × 100 | > 85% | Quarterly | CRM | Sales |
| Revenue per Business Line | Revenue breakdown by Energy, RE, Logistics, Retail, Services | Per budget | Monthly | GL by cost center | Sales / CFO |
| Net Promoter Score (NPS) | Customer survey score | > 50 | Quarterly | Survey tool | Sales |
| Complaint Resolution Time | Avg days to resolve customer complaints | < 3 days | Monthly | Complaint log | Sales |
| Quotation-to-Order Rate | Orders / Quotations issued × 100 | > 40% | Monthly | Sales module | Sales |

## 5. Human Resources KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| Headcount | Total employees by department/grade | Per plan | Monthly | HR module | HR |
| Time-to-Hire | Days from requisition to offer acceptance | < 30 days | Monthly | HR records | HR |
| Employee Turnover Rate | Exits / Average headcount × 100 | < 15% p.a. | Monthly | HR module | HR |
| Absenteeism Rate | Unplanned absence days / Total working days × 100 | < 3% | Monthly | Attendance records | HR |
| Training Hours per Employee | Total training hours / Headcount | > 20 hrs/year | Quarterly | Training log | HR |
| Probation Pass Rate | Confirmed / Total probationers × 100 | > 85% | Quarterly | HR records | HR |
| Payroll Accuracy | Payroll errors / Total payslips × 100 | < 1% | Monthly | Payroll module | HR |
| Leave Utilization | Leave taken / Leave entitled × 100 | 70–90% | Quarterly | Leave module | HR |
| NSSF/PAYE Compliance | % of remittances filed on time | 100% | Monthly | Payroll / Tax | HR / CFO |

## 6. Legal & Compliance KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| Contract Turnaround Time | Days from request to fully signed contract | < 10 days | Monthly | Contract log | Management |
| License Renewal Compliance | % of licenses renewed before expiry | 100% | Monthly | Compliance calendar | Management |
| Open Compliance Issues | Count of overdue compliance items | 0 | Monthly | Compliance register | Management |
| Incident Response Time | Hours from incident report to initial response | < 24 hours | Per incident | Incident log | Management |
| Whistleblowing Cases | # of cases reported and resolved | Track trend | Quarterly | Whistleblowing log | Management |

## 7. IT KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| System Uptime | % of time core systems are available | > 99% | Monthly | IT monitoring | IT |
| Helpdesk Response Time | Avg time to first response on IT tickets | < 4 hours | Monthly | Helpdesk log | IT |
| Helpdesk Resolution Time | Avg time to close IT tickets | < 24 hours | Monthly | Helpdesk log | IT |
| Backup Success Rate | % of successful backups | 100% | Weekly | Backup logs | IT |
| Access Provisioning Time | Hours from request to account creation | < 8 hours | Monthly | Access log | IT |
| Security Incidents | # of security incidents (malware, breaches) | 0 | Monthly | Incident log | IT |

## 8. Internal Audit KPIs

| KPI | Definition | Target | Frequency | Data Source | Dashboard |
|-----|-----------|--------|-----------|-------------|-----------|
| Audit Plan Completion | % of planned audits completed | > 90% | Quarterly | Audit plan | Management |
| Findings per Audit | Avg findings per audit engagement | Trend down | Per audit | Audit reports | Management |
| Critical/High Findings Open | # of unresolved critical/high findings | 0 critical, < 5 high | Monthly | CAPA tracker | Management |
| CAPA Closure Rate | % of CAPAs closed by due date | > 85% | Monthly | CAPA tracker | Management |
| Repeat Findings Rate | Findings recurring from prior audits / Total | < 10% | Quarterly | Audit reports | Management |

---

## Dashboard Specifications

### CFO Dashboard
**Audience:** CFO, Finance Manager, Managing Director
**Refresh:** Monthly (by BD 12)
**Sections:**
1. Cash Position — current bank balances, 13-week forecast chart
2. P&L Summary — revenue, gross profit, net profit (actual vs budget)
3. AR Aging — 0-30, 31-60, 61-90, 90+ days (bar chart + table)
4. AP Aging — 0-30, 31-60, 61-90, 90+ days (bar chart + table)
5. Budget vs Actual — variance by GL category (waterfall chart)
6. Revenue by Business Line — pie chart + trend
7. Tax Compliance Status — traffic light (Green/Amber/Red)
8. Working Capital — current ratio, quick ratio trend

### Operations Dashboard
**Audience:** Operations Manager, Procurement Manager, Stores Officer
**Refresh:** Weekly
**Sections:**
1. Procurement Pipeline — PRs pending, POs pending delivery
2. Stock Levels — by category, items below reorder level (alerts)
3. Delivery Status — pending dispatches, delayed orders
4. Supplier Performance — on-time delivery %, defect rate
5. Fleet Status — vehicles in use, maintenance due, fuel consumption
6. Inventory Value — by location, by category

### Sales Dashboard
**Audience:** Sales Manager, Sales Executives, Managing Director
**Refresh:** Weekly
**Sections:**
1. Pipeline — value by stage (funnel chart)
2. Revenue — MTD actual vs target (gauge chart)
3. Conversion Rate — trend chart
4. Top Deals — list of top 10 opportunities
5. Customer Activity — new leads, quotations sent, orders received
6. Revenue by Business Line — MTD breakdown

### HR Dashboard
**Audience:** HR Manager, Managing Director
**Refresh:** Monthly
**Sections:**
1. Headcount — by department, grade, gender
2. Recruitment — open positions, pipeline status
3. Turnover — monthly rate, reasons for exit
4. Leave — utilization by department
5. Payroll — total cost, PAYE/NSSF status
6. Training — hours delivered vs plan

### Management / MD Dashboard
**Audience:** Managing Director, Board
**Refresh:** Monthly (detailed), Weekly (snapshot)
**Sections:**
1. Financial Summary — revenue, profit, cash (vs last month and budget)
2. Top 5 KPIs — traffic light status
3. Business Line Performance — revenue + margin by line
4. Key Risks — top 5 from risk register
5. Compliance Status — traffic light
6. People Summary — headcount, hires, exits
7. Audit Findings — open critical/high items
8. Strategic Initiatives — progress by project

---

## Reporting Cadence Summary

| Report | Audience | Frequency | Due Date | Owner |
|--------|----------|-----------|----------|-------|
| Daily Cash Position | Finance Manager | Daily | By 10 AM | Accountant |
| Daily Sales Report | Sales Manager | Daily | By 6 PM | Sales Lead |
| Daily Branch Report | Operations Manager | Daily | By 7 PM | Branch Manager |
| Weekly Cash Forecast | CFO / MD | Weekly | Monday AM | Finance Manager |
| Weekly Sales Pipeline | Sales Manager / MD | Weekly | Monday AM | Sales Manager |
| Weekly Operations Summary | Operations Manager | Weekly | Friday PM | Operations Manager |
| Monthly Management Accounts | MD / Board | Monthly | BD 12 | Finance Manager |
| Monthly KPI Scorecard | MD / Department Heads | Monthly | BD 15 | Each Department Head |
| Monthly HR Report | MD | Monthly | BD 10 | HR Manager |
| Monthly Compliance Status | MD | Monthly | BD 10 | Legal/Compliance Officer |
| Quarterly Board Pack | Board of Directors | Quarterly | 5 days before board meeting | MD + Finance Manager |
| Quarterly Risk Review | Board / Audit Committee | Quarterly | With board pack | Risk Owner |
| Quarterly Audit Report | Board / Audit Committee | Quarterly | With board pack | Internal Auditor |
| Annual Budget | Board | Annually | December | Finance Manager |
| Annual Audit Report | Board | Annually | Q1 following year | External Auditor |

---
*Awdeer Investments Limited — KPI & Dashboard Pack v1.0*
*February 2026*
