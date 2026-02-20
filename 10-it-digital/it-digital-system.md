# Awdeer Investments Limited — IT & Digital Operations

## Part I: IT & Digital Operations System

---

## 1. Purpose

This document defines the complete IT and digital operations framework for Awdeer Investments Limited. It covers the technology stack, access controls, data protection, backup and recovery, cyber hygiene, naming conventions, helpdesk processes, and the governance structures required to operate technology safely, efficiently, and at scale.

All processes are provided in two versions:
- **Lean** — for small teams (fewer than 15 people, limited IT staff)
- **Controlled** — for mid-size teams (15-100+ people, dedicated IT function)

## 2. Scope

| Area | Included |
|------|----------|
| Core tools stack | Email, ERP, document management, communication, CRM, HR, project management |
| Access control | Role-based access, provisioning, deprovisioning, periodic review |
| Backup & disaster recovery | Backup schedules, recovery procedures, business continuity |
| Cyber hygiene | Password policy, phishing awareness, device security, incident response |
| Naming conventions | Drives, folders, documents, emails |
| Helpdesk process | Support requests, ticketing, escalation, resolution tracking |
| IT onboarding/offboarding | Account setup, equipment issue, access removal |
| IT asset management | Equipment register, lifecycle tracking, disposal |

---

## 3. Core Tools Stack

### 3.1 Recommended Technology Stack

> **ASSUMPTION**: Odoo is selected as the ERP platform (open source, cost-effective for Uganda). Google Workspace is the primary collaboration suite. Confirm platform choices with directors before implementation.

| Function | Primary Tool | Backup / Alternative | License Model |
|----------|-------------|---------------------|---------------|
| Email & Calendar | Google Workspace (Gmail) | — | Per-user/month subscription |
| Cloud Storage & Docs | Google Drive, Docs, Sheets, Slides | Local backup drive | Included in Workspace |
| Video Conferencing | Google Meet | Zoom (free tier) | Included in Workspace |
| Internal Communication | Google Chat | WhatsApp Business (field teams) | Included in Workspace / Free |
| ERP / Accounting | Odoo (Community or Enterprise) | QuickBooks, Xero | Open source / subscription |
| CRM | Odoo CRM module | HubSpot (free tier) | Included in Odoo / Free |
| HR Management | Odoo HR module | BambooHR, manual spreadsheets | Included in Odoo |
| Project Management | Google Sheets + Odoo Projects | Trello (free tier) | Included |
| Document Management | Google Drive (structured folders) | — | Included in Workspace |
| Payroll | Odoo Payroll module | Standalone payroll software | Included in Odoo |
| Inventory | Odoo Inventory module | Google Sheets | Included in Odoo |
| Website / Marketing | Odoo Website (optional) | WordPress | Included in Odoo |
| Antivirus / Security | Windows Defender + Malwarebytes | Kaspersky | Free / subscription |
| Password Manager | Bitwarden (Teams) | Google Password Manager | Free / subscription |
| Backup | Google Vault + local NAS (ASSUMPTION) | External hard drives | Subscription + one-time |

### 3.2 Google Workspace Configuration

| Setting | Configuration |
|---------|--------------|
| Domain | @awdeerinvestments.co.ug (ASSUMPTION) |
| Admin Console | Managed by IT Administrator |
| 2-Step Verification | Enforced for all users |
| Mobile Device Management | Basic MDM enabled |
| Data Loss Prevention | Enabled for sensitive folders |
| Sharing defaults | Internal only; external sharing requires approval |
| Storage allocation | Per Google Workspace plan tier |

### 3.3 Odoo Module Deployment Plan

| Phase | Modules | Timeline (ASSUMPTION) |
|-------|---------|----------------------|
| Phase 1 (Month 1-2) | Accounting, Contacts, Invoicing | Immediate |
| Phase 2 (Month 2-3) | CRM, Sales, Purchase | Month 2 |
| Phase 3 (Month 3-4) | Inventory, HR, Payroll | Month 3 |
| Phase 4 (Month 4-6) | Projects, Helpdesk, Website | Month 4 |

---

## 4. Google Drive Folder Structure

### 4.1 Top-Level Structure

```
Awdeer Investments/
├── 01-Governance/
│   ├── Board-Minutes/
│   ├── Resolutions/
│   ├── Policies/
│   ├── Delegation-of-Authority/
│   └── Risk-Register/
├── 02-Finance/
│   ├── Chart-of-Accounts/
│   ├── Monthly-Close/
│   ├── Tax-Filings/
│   ├── Bank-Reconciliations/
│   ├── Budgets/
│   ├── Management-Reports/
│   ├── Payables/
│   ├── Receivables/
│   └── Fixed-Assets/
├── 03-Operations/
│   ├── Daily-Reports/
│   ├── Fleet-Management/
│   ├── Warehouse/
│   └── Logistics/
├── 04-Procurement/
│   ├── Purchase-Requisitions/
│   ├── Purchase-Orders/
│   ├── Supplier-Files/
│   ├── Contracts/
│   └── Evaluations/
├── 05-Sales-Marketing/
│   ├── Pipeline-Reports/
│   ├── Proposals/
│   ├── Marketing-Materials/
│   ├── Customer-Files/
│   └── Campaigns/
├── 06-HR/
│   ├── Employee-Files/ (RESTRICTED)
│   ├── Recruitment/
│   ├── Policies/
│   ├── Training/
│   ├── Payroll/ (RESTRICTED)
│   ├── Performance/
│   └── Leave-Records/
├── 07-Legal-Compliance/
│   ├── Contracts/
│   ├── Licenses-Permits/
│   ├── Compliance-Register/
│   ├── AML-KYC/
│   └── Data-Protection/
├── 08-IT/
│   ├── Asset-Register/
│   ├── Access-Logs/
│   ├── Backup-Logs/
│   ├── Policies/
│   ├── Vendor-Contracts/
│   └── Incident-Reports/
├── 09-Projects/
│   ├── Active/
│   │   └── [Project-Name]/
│   │       ├── Plans/
│   │       ├── Reports/
│   │       └── Correspondence/
│   ├── Completed/
│   └── Pipeline/
├── 10-Templates/
│   ├── Finance/
│   ├── HR/
│   ├── Procurement/
│   ├── Sales/
│   ├── IT/
│   ├── Legal/
│   └── Operations/
└── 11-Archive/
    ├── FY-2024/
    ├── FY-2025/
    └── FY-2026/
```

### 4.2 Folder Access Matrix

| Folder | MD | Finance | Operations | Procurement | Sales | HR | Legal | IT | Audit |
|--------|:--:|:-------:|:----------:|:-----------:|:-----:|:--:|:-----:|:--:|:-----:|
| 01-Governance | RW | R | R | R | R | R | RW | R | R |
| 02-Finance | R | RW | — | R | — | R | R | RW | R |
| 03-Operations | R | R | RW | R | R | — | — | R | R |
| 04-Procurement | R | R | R | RW | — | — | R | R | R |
| 05-Sales-Marketing | R | R | R | — | RW | — | — | R | R |
| 06-HR | R | R* | — | — | — | RW | R | R* | R |
| 07-Legal-Compliance | R | R | R | R | R | R | RW | R | R |
| 08-IT | R | — | — | — | — | — | — | RW | R |
| 09-Projects | RW | R | RW | R | RW | R | R | R | R |
| 10-Templates | RW | R | R | R | R | R | R | RW | R |
| 11-Archive | R | R | R | R | R | R | R | RW | R |

**Legend**: RW = Read/Write, R = Read Only, — = No Access, R* = Limited access (non-personal data only)

---

## 5. Access Control Policy

### 5.1 Principles

1. **Least Privilege** — Users receive only the minimum access required for their role
2. **Role-Based Access Control (RBAC)** — Access is assigned by role, not by individual
3. **Segregation of Duties** — No single person has end-to-end control over critical processes
4. **Timely Deprovisioning** — Access is revoked within 2 hours of termination, same-day for resignations
5. **Periodic Review** — All access rights reviewed quarterly (Lean) or monthly (Controlled)

### 5.2 Role-Based Access Matrix — Systems

| Role | Google Workspace | Odoo ERP | Odoo CRM | Odoo HR | Odoo Inventory | Google Drive (Admin) |
|------|:----------------:|:--------:|:--------:|:-------:|:--------------:|:-------------------:|
| Managing Director | Full | Full (Read) | Full | Full (Read) | Full (Read) | Full |
| CFO / Finance Manager | Full | Full | Read | Payroll | Read | Finance folders |
| Accountant | Full | AP/AR/GL | — | — | Read | Finance folders |
| Operations Manager | Full | Read | Read | — | Full | Operations folders |
| Procurement Manager | Full | Purchase | — | — | Read | Procurement folders |
| Sales Manager | Full | Read | Full | — | Read | Sales folders |
| Sales Executive | Email only | — | Own pipeline | — | — | Sales folders |
| HR Manager | Full | — | — | Full | — | HR folders |
| HR Officer | Full | — | — | Employee/Leave | — | HR folders (limited) |
| IT Administrator | Full + Admin | System Admin | System Admin | System Admin | System Admin | Full Admin |
| Internal Auditor | Full | Read (All) | Read | Read | Read | Read (All) |
| Legal/Compliance | Full | Read | Read | Read | — | Legal folders |

### 5.3 Access Provisioning Process

#### Lean Version

| Step | Action | Responsible | Approver |
|------|--------|-------------|----------|
| 1 | Line manager emails IT with new hire details and role | Line Manager | — |
| 2 | IT creates accounts based on role access matrix | IT Support | — |
| 3 | IT shares credentials securely with new employee | IT Support | — |
| 4 | Employee signs IT Acceptable Use Policy | New Employee | Line Manager |
| 5 | IT logs access granted in Access Register (Google Sheet) | IT Support | — |

#### Controlled Version

| Step | Action | Responsible | Approver |
|------|--------|-------------|----------|
| 1 | HR submits IT Access Request Form (IT-TPL-001) | HR Officer | — |
| 2 | Line manager approves access scope | Line Manager | — |
| 3 | IT Administrator reviews against role matrix | IT Administrator | — |
| 4 | IT creates accounts, configures access per approved form | IT Administrator | — |
| 5 | IT sends credentials via secure channel (not email) | IT Administrator | — |
| 6 | Employee completes IT security awareness training | New Employee | IT Administrator |
| 7 | Employee signs IT Acceptable Use Policy | New Employee | HR Manager |
| 8 | IT logs all access in Access Management System | IT Administrator | — |
| 9 | IT Manager approves and signs off provisioning | IT Administrator | MD (for elevated access) |

### 5.4 Access Deprovisioning Process

| Trigger | Action | Timeline | Responsible |
|---------|--------|----------|-------------|
| Resignation (voluntary) | Disable all accounts, revoke Drive access, collect equipment | Same business day | IT Administrator |
| Termination (involuntary) | Disable all accounts immediately, revoke all access | Within 2 hours of notification | IT Administrator |
| Role change | Adjust access to match new role, remove old privileges | Within 24 hours | IT Administrator |
| Leave of absence (>30 days) | Suspend accounts, maintain data | Before leave starts | IT Administrator |
| Contract end (temporary staff) | Disable accounts, revoke access | On contract end date | IT Administrator |

### 5.5 Periodic Access Review

| Item | Lean | Controlled |
|------|------|------------|
| Review frequency | Quarterly | Monthly |
| Reviewer | MD + IT Support | IT Administrator + Department Heads |
| Scope | All user accounts and system access | All accounts, permissions, API keys, shared drives |
| Output | Updated access register | Access review report with exceptions and actions |
| Escalation | Anomalies reported to MD | Anomalies reported to IT Manager and Internal Audit |

### 5.6 RACI — Access Control

| Activity | IT Admin | Line Manager | HR | MD | Internal Audit |
|----------|:--------:|:------------:|:--:|:--:|:--------------:|
| Request new access | I | R | A | I | — |
| Approve access scope | — | A | C | I | — |
| Provision accounts | R/A | I | I | — | — |
| Revoke access (termination) | R/A | C | R | I | I |
| Periodic access review | R | C | C | A | C |
| Access audit | C | — | — | I | R/A |

---

## 6. Backup Policy and Disaster Recovery Plan

### 6.1 Backup Policy

#### 6.1.1 Backup Scope

| Data Category | Location | Backup Method | Frequency |
|---------------|----------|---------------|-----------|
| Google Workspace (Email, Drive) | Google Cloud | Google Vault + third-party backup (ASSUMPTION) | Continuous (Google) + Daily (third-party) |
| Odoo ERP database | Server / Cloud | Automated database dump | Daily |
| Odoo file attachments | Server / Cloud | File-level backup | Daily |
| Local files (if any) | Workstations | Sync to Google Drive | Continuous |
| Financial records | ERP + Drive | Dedicated backup to external drive | Weekly |
| HR/Payroll data | ERP + Drive | Encrypted backup | Weekly |
| IT configuration files | IT server | Manual backup + versioning | Weekly |
| Website (if applicable) | Odoo hosting | Full site backup | Weekly |

#### 6.1.2 Backup Schedule

| Backup Type | Frequency | Retention | Storage Location |
|-------------|-----------|-----------|-----------------|
| Full system backup | Weekly (Sunday) | 12 weeks | Off-site / cloud storage |
| Incremental backup | Daily (midnight) | 30 days | Local NAS + cloud |
| Database snapshot | Every 6 hours | 7 days | Cloud storage |
| Transaction log backup | Hourly | 48 hours | Cloud storage |
| Monthly archive | Monthly (1st) | 7 years (per URA requirements) | Off-site + cloud |

#### 6.1.3 Backup Verification

| Check | Frequency | Responsible | Method |
|-------|-----------|-------------|--------|
| Backup completion check | Daily | IT Administrator | Automated alert review |
| Backup integrity test | Weekly | IT Administrator | Checksum verification |
| Test restore (sample data) | Monthly | IT Administrator | Restore to test environment |
| Full disaster recovery drill | Quarterly (Controlled) / Bi-annually (Lean) | IT Administrator + MD | Full system restore simulation |

### 6.2 Disaster Recovery Plan

#### 6.2.1 Recovery Objectives

| Metric | Target (Lean) | Target (Controlled) |
|--------|--------------|---------------------|
| Recovery Time Objective (RTO) | 24 hours | 4 hours |
| Recovery Point Objective (RPO) | 24 hours | 6 hours |
| Maximum Tolerable Downtime (MTD) | 48 hours | 12 hours |

#### 6.2.2 Disaster Scenarios and Response

| Scenario | Impact | Response | Recovery Steps |
|----------|--------|----------|----------------|
| Internet outage | No cloud access | Switch to mobile hotspot; work from local copies | 1. Activate backup internet 2. Notify staff 3. Use offline mode |
| Server failure (Odoo) | ERP down | Restore from latest backup to standby server | 1. Activate standby 2. Restore DB 3. Verify data 4. Resume operations |
| Ransomware attack | Data encrypted | Isolate affected systems; restore from clean backup | 1. Isolate systems 2. Assess scope 3. Clean restore 4. Change all passwords |
| Hardware theft/loss | Data exposure | Remote wipe device; restore data from cloud | 1. Remote wipe 2. Report to police 3. Change passwords 4. Restore from backup |
| Power outage (extended) | All systems down | UPS for critical systems; generator backup | 1. UPS sustains 30 min 2. Generator activates 3. Prioritize critical systems |
| Google Workspace outage | Email/Drive down | Use WhatsApp for comms; local file copies | 1. Monitor Google status 2. Use alternatives 3. Resume when restored |
| Fire/flood (office) | Total loss | Activate remote work; all data in cloud | 1. Ensure staff safety 2. Activate remote work 3. Restore from cloud backups |

#### 6.2.3 Emergency Contact List

| Role | Contact | Phone (TEMPLATE) | Responsibility |
|------|---------|-------------------|----------------|
| IT Administrator | [Name] | [Number] | First responder for all IT incidents |
| Managing Director | [Name] | [Number] | Decision authority for disaster declaration |
| ISP Provider | [Provider name] | [Number] | Internet connectivity issues |
| Odoo Hosting Provider | [Provider name] | [Number] | ERP server issues |
| Google Workspace Support | Google Admin Console | Online | Workspace issues |
| Hardware Vendor | [Vendor name] | [Number] | Equipment replacement |
| Insurance Provider | [Provider name] | [Number] | Claim filing |

### 6.3 RACI — Backup & Disaster Recovery

| Activity | IT Admin | MD | Finance Mgr | Dept Heads | Internal Audit |
|----------|:--------:|:--:|:-----------:|:----------:|:--------------:|
| Daily backup execution | R/A | — | — | — | — |
| Backup verification | R/A | — | — | — | I |
| Test restore | R/A | I | — | — | C |
| DR drill (quarterly) | R | A | C | C | C |
| DR plan update | R | A | C | C | C |
| Incident response | R/A | A | I | I | I |
| Post-incident review | R | A | C | C | R |

---

## 7. Cyber Hygiene SOPs

### 7.1 Password Management

#### 7.1.1 Password Policy

| Requirement | Lean | Controlled |
|-------------|------|------------|
| Minimum length | 10 characters | 12 characters |
| Complexity | Upper + lower + number | Upper + lower + number + special character |
| Expiry | Every 180 days | Every 90 days |
| History | Cannot reuse last 3 passwords | Cannot reuse last 6 passwords |
| Lockout | 5 failed attempts = 15-minute lockout | 5 failed attempts = 30-minute lockout + IT alert |
| Multi-Factor Authentication (MFA) | Required for Google Workspace admin | Required for all users on all systems |
| Password manager | Recommended (Bitwarden) | Mandatory (Bitwarden Teams) |
| Shared accounts | Discouraged | Prohibited |
| Default passwords | Must be changed on first login | Must be changed on first login; system-enforced |

#### 7.1.2 Password Dos and Don'ts

| Do | Don't |
|----|-------|
| Use a password manager | Write passwords on sticky notes |
| Use unique passwords per system | Reuse the same password across systems |
| Enable MFA wherever possible | Share passwords via email, WhatsApp, or SMS |
| Report suspected compromise immediately | Use personal information in passwords |
| Use passphrases (e.g., "Coffee-Rain-Kampala-42!") | Use dictionary words or common patterns |

### 7.2 Phishing Awareness

#### 7.2.1 Training Requirements

| Item | Lean | Controlled |
|------|------|------------|
| Initial training | During onboarding (30-minute session) | During onboarding (1-hour session + test) |
| Refresher training | Annually | Quarterly |
| Simulated phishing tests | — | Quarterly (using Google Workspace tools or free services) |
| Reporting mechanism | Forward to IT support email | Forward to phishing@awdeerinvestments.co.ug + report button |

#### 7.2.2 Phishing Red Flags — Staff Quick Reference

| Red Flag | Example |
|----------|---------|
| Urgent action demanded | "Your account will be locked in 1 hour!" |
| Unknown sender | Email from someone you don't recognize asking for data |
| Suspicious links | Hover shows different URL than displayed text |
| Unexpected attachments | Invoice or receipt you weren't expecting |
| Request for credentials | "Please confirm your password" |
| Generic greeting | "Dear Customer" instead of your name |
| Spelling/grammar errors | Unprofessional language in supposedly official email |
| Mismatched email domain | support@g00gle.com instead of google.com |

### 7.3 Device Security

#### 7.3.1 Company Devices

| Requirement | Lean | Controlled |
|-------------|------|------------|
| Screen lock | Auto-lock after 5 minutes | Auto-lock after 3 minutes |
| Disk encryption | Recommended | Mandatory (BitLocker/FileVault) |
| Antivirus | Windows Defender (active + updated) | Enterprise antivirus + monthly scans |
| Software updates | Auto-update enabled | Managed updates via IT (tested then deployed) |
| USB drives | Allowed with caution | Disabled by policy; exceptions require IT approval |
| Personal use | Limited personal use allowed | No personal use; separate personal devices |
| Remote wipe capability | — | Enabled for all company devices |
| VPN | — | Required for remote access |

#### 7.3.2 Personal Devices (BYOD)

| Item | Lean | Controlled |
|------|------|------------|
| BYOD policy | Informal; access via Google Workspace only | Formal BYOD policy required; MDM enrollment |
| Minimum requirements | Screen lock + updated OS | Screen lock + updated OS + antivirus + MDM |
| Data separation | Gmail app only | Managed profile with containerized company data |
| Lost device | User reports to IT; password reset | User reports to IT; remote wipe of company data |

### 7.4 Email Security

| Control | Lean | Controlled |
|---------|------|------------|
| Spam filtering | Google default | Google + additional filtering rules |
| External email banner | — | Enabled ("[EXTERNAL]" tag on incoming) |
| Auto-forwarding | Disabled for all users | Disabled + monitored |
| Large attachment policy | Use Drive links instead | Enforced via DLP rules |
| Sensitive data in email | Discouraged; use Drive sharing | Prohibited; DLP rules block sensitive content |

### 7.5 Incident Response

| Step | Action | Responsible | Timeline |
|------|--------|-------------|----------|
| 1 | Detect / Report incident | Any employee | Immediately |
| 2 | Contain — isolate affected system | IT Administrator | Within 1 hour |
| 3 | Assess — determine scope and severity | IT Administrator | Within 2 hours |
| 4 | Escalate — notify MD if critical | IT Administrator | Within 2 hours |
| 5 | Eradicate — remove threat | IT Administrator | Within 24 hours |
| 6 | Recover — restore from backup if needed | IT Administrator | Per RTO targets |
| 7 | Document — complete incident report | IT Administrator | Within 48 hours |
| 8 | Review — lessons learned, update controls | IT Admin + MD | Within 1 week |

### 7.6 RACI — Cyber Hygiene

| Activity | IT Admin | All Staff | HR | MD | Internal Audit |
|----------|:--------:|:---------:|:--:|:--:|:--------------:|
| Password policy enforcement | R/A | R | C | I | C |
| Phishing training delivery | R/A | R | C | I | — |
| Device security compliance | R/A | R | — | I | C |
| Incident detection | C | R | — | I | — |
| Incident response | R/A | I | I | A | I |
| Security awareness program | R/A | — | C | A | C |
| Policy review & update | R | — | C | A | C |

---

## 8. Naming Conventions

### 8.1 Document Naming Standard

**Format**: `[DEPT]-[AREA]-[SEQ] Description vX.X [YYYY-MM-DD]`

| Component | Rule | Example |
|-----------|------|---------|
| DEPT | 2-3 letter department code (uppercase) | IT, FIN, HR, PRO, SAL, LEG, GOV, OPS |
| AREA | 2-4 letter area code (uppercase) | ACC (access), BKP (backup), SEC (security) |
| SEQ | 3-digit sequential number | 001, 002, 003 |
| Description | Short descriptive title (Title Case, hyphens for spaces) | Access-Control-Policy |
| Version | vX.X format | v1.0, v1.1, v2.0 |
| Date | ISO format (optional, for dated documents) | 2026-02-20 |

**Examples**:
- `IT-ACC-001 Access-Control-Policy v1.0.pdf`
- `FIN-AP-001 Payment-Voucher v1.0 2026-02-15.pdf`
- `HR-REC-001 Job-Description-Template v2.0.docx`
- `PRO-PUR-001 Purchase-Requisition v1.0 2026-02-20.pdf`

### 8.2 Folder Naming Standard

| Rule | Standard | Example |
|------|----------|---------|
| Top-level folders | NN-Name (numbered, Title Case with hyphens) | 01-Governance, 02-Finance |
| Sub-folders | Descriptive (Title Case with hyphens) | Board-Minutes, Tax-Filings |
| Project folders | [Project-Code]-[Name] | PRJ-001-New-Warehouse |
| Year folders | FY-YYYY | FY-2026 |
| Month folders | YYYY-MM-Description | 2026-02-Monthly-Close |

### 8.3 Email Subject Line Convention

**Format**: `[DEPT] Action — Brief Description`

| Type | Format | Example |
|------|--------|---------|
| Request | [DEPT] Request — Description | [FIN] Request — Payment Approval for Supplier XYZ |
| Approval | [DEPT] Approved — Description | [PRO] Approved — PO-2026-0045 |
| Report | [DEPT] Report — Description | [SAL] Report — Weekly Pipeline Update |
| Action Required | [DEPT] ACTION — Description | [IT] ACTION — Password Reset Required |
| FYI | [DEPT] FYI — Description | [HR] FYI — New Leave Policy Effective March 1 |

### 8.4 System Account Naming

| System | Format | Example |
|--------|--------|---------|
| Google Workspace email | firstname.lastname@awdeerinvestments.co.ug | john.doe@awdeerinvestments.co.ug |
| Google Group (department) | dept@awdeerinvestments.co.ug | finance@awdeerinvestments.co.ug |
| Google Group (project) | project-name@awdeerinvestments.co.ug | warehouse-project@awdeerinvestments.co.ug |
| Odoo username | firstname.lastname | john.doe |
| Shared mailbox | function@awdeerinvestments.co.ug | info@, support@, hr@ |
| IT admin account | admin-firstname | admin-john |

### 8.5 IT Asset Naming

| Asset Type | Format | Example |
|------------|--------|---------|
| Laptop | AWD-LPT-[SEQ] | AWD-LPT-001 |
| Desktop | AWD-DSK-[SEQ] | AWD-DSK-001 |
| Printer | AWD-PRT-[SEQ] | AWD-PRT-001 |
| Router/Switch | AWD-NET-[SEQ] | AWD-NET-001 |
| Phone | AWD-PHN-[SEQ] | AWD-PHN-001 |
| Server | AWD-SVR-[SEQ] | AWD-SVR-001 |
| UPS | AWD-UPS-[SEQ] | AWD-UPS-001 |
| External Drive | AWD-EXT-[SEQ] | AWD-EXT-001 |

---

## 9. IT Helpdesk / Support Process

### 9.1 Lean Version — Email-Based

#### Process Flow

```
User has IT issue
    ↓
User sends email to it-support@awdeerinvestments.co.ug
(or WhatsApp message to IT Support)
    ↓
IT Support logs issue in Google Sheet (IT Ticket Log)
    ↓
IT Support assigns priority (High / Medium / Low)
    ↓
IT Support resolves issue
    ↓
IT Support updates log with resolution
    ↓
User confirms resolution
    ↓
Ticket closed in log
```

#### Priority Matrix (Lean)

| Priority | Definition | Response Time | Resolution Target |
|----------|-----------|---------------|-------------------|
| High | System down, cannot work | 1 hour | 4 hours |
| Medium | System slow or partially working | 4 hours | 24 hours |
| Low | Cosmetic issue, feature request | 24 hours | 1 week |

#### Ticket Log Fields (Google Sheet)

| Field | Description |
|-------|-------------|
| Ticket # | Auto-generated (IT-YYYY-NNNN) |
| Date Reported | Date issue was reported |
| Reported By | Employee name |
| Department | Department |
| Category | Hardware / Software / Network / Access / Other |
| Priority | High / Medium / Low |
| Description | Brief description of issue |
| Assigned To | IT support person |
| Status | Open / In Progress / Resolved / Closed |
| Resolution | How it was resolved |
| Date Resolved | Date resolved |
| Satisfaction | OK / Not Satisfied (optional) |

### 9.2 Controlled Version — Structured Ticketing

#### Process Flow

```
User has IT issue
    ↓
User submits Google Form (IT Support Request)
    ↓
Form auto-populates Google Sheet + sends email to IT team
    ↓
IT Administrator triages and assigns ticket
    ↓
IT team member acknowledges within SLA
    ↓
IT resolves or escalates
    ↓
User receives email notification
    ↓
User confirms resolution (or re-opens)
    ↓
IT closes ticket + updates knowledge base
    ↓
Monthly: IT generates support metrics report
```

#### Priority & SLA Matrix (Controlled)

| Priority | Definition | Response Time | Resolution Target | Escalation |
|----------|-----------|---------------|-------------------|------------|
| P1 — Critical | All users affected, business stopped | 15 minutes | 2 hours | Immediate to MD |
| P2 — High | Department affected, workaround possible | 1 hour | 4 hours | After 2 hours to IT Manager |
| P3 — Medium | Individual affected, workaround exists | 4 hours | 24 hours | After 8 hours to IT Manager |
| P4 — Low | Minor issue, enhancement request | 24 hours | 1 week | Weekly review |

#### Escalation Path

| Level | Who | When |
|-------|-----|------|
| Level 1 | IT Support Staff | First response, basic troubleshooting |
| Level 2 | IT Administrator | Complex issues, system-level problems |
| Level 3 | External Vendor / Consultant | Infrastructure, ERP, specialized systems |
| Level 4 | MD | Business continuity decisions, emergency spend |

### 9.3 RACI — Helpdesk Process

| Activity | IT Support | IT Admin | Requester | Dept Head | MD |
|----------|:----------:|:--------:|:---------:|:---------:|:--:|
| Submit request | I | I | R/A | — | — |
| Triage & assign | R/A | A | I | — | — |
| First-line resolution | R/A | I | I | — | — |
| Escalation (Level 2) | R | R/A | I | I | — |
| Escalation (Level 3) | C | R/A | I | I | I |
| Emergency declaration | I | R | — | C | A |
| Monthly metrics review | R | R/A | — | I | I |

---

## 10. IT Onboarding & Offboarding

### 10.1 Onboarding Checklist Summary

> Full checklist: See template IT-TPL-002-it-onboarding-checklist.md

| Category | Items |
|----------|-------|
| Accounts | Google Workspace account, Odoo account, department Google Group |
| Equipment | Laptop/desktop, phone (if applicable), charger, peripherals |
| Access | Drive folder access per role matrix, Odoo modules per role |
| Security | MFA setup, password manager enrollment, antivirus check |
| Training | IT security awareness briefing, tool orientation, acceptable use policy signing |
| Documentation | Asset assignment form signed, access logged in register |

### 10.2 Offboarding Checklist Summary

| Category | Items | Timeline |
|----------|-------|----------|
| Accounts | Disable Google Workspace, suspend Odoo account, remove from groups | Immediate (involuntary) / Last day (voluntary) |
| Data | Transfer Drive ownership to manager, archive mailbox, export relevant data | Within 24 hours |
| Equipment | Collect laptop, phone, charger, ID card, keys, any peripherals | Last day |
| Access | Revoke VPN, remove MFA, revoke shared passwords | Immediate |
| Records | Update asset register, update access register, file offboarding checklist | Within 48 hours |
| Vendor access | Revoke any external system access (bank, URA, etc.) | Within 24 hours |

### 10.3 RACI — Onboarding/Offboarding

| Activity | IT Admin | HR | Line Manager | Employee | MD |
|----------|:--------:|:--:|:------------:|:--------:|:--:|
| Initiate onboarding request | I | R/A | C | — | — |
| Create accounts | R/A | I | I | — | — |
| Issue equipment | R/A | I | I | R | — |
| Conduct IT training | R/A | C | — | R | — |
| Initiate offboarding | I | R/A | C | — | I |
| Disable accounts | R/A | C | I | — | — |
| Collect equipment | R/A | C | R | R | — |
| Data transfer & archive | R/A | I | A | — | — |

---

## 11. IT Budget (ASSUMPTION)

### 11.1 Estimated Annual IT Costs

| Category | Item | Monthly (UGX) | Annual (UGX) | Notes |
|----------|------|---------------|-------------|-------|
| Software | Google Workspace (10 users) | 1,500,000 | 18,000,000 | ~$40/user/year |
| Software | Odoo Enterprise (10 users) | 2,500,000 | 30,000,000 | Or free Community edition |
| Software | Antivirus (10 licenses) | 250,000 | 3,000,000 | — |
| Software | Bitwarden Teams | 100,000 | 1,200,000 | — |
| Infrastructure | Internet (fiber) | 500,000 | 6,000,000 | Dedicated business line |
| Infrastructure | Backup internet (mobile) | 200,000 | 2,400,000 | Failover connection |
| Infrastructure | Cloud hosting (Odoo) | 400,000 | 4,800,000 | If cloud-hosted |
| Hardware | Laptop replacement (2/year) | — | 10,000,000 | Lifecycle replacement |
| Hardware | Printer consumables | 200,000 | 2,400,000 | — |
| Hardware | UPS batteries (replacement) | — | 1,500,000 | Annual replacement |
| Services | IT support (outsourced/part-time) | 1,000,000 | 12,000,000 | Lean version |
| Services | Annual security audit | — | 5,000,000 | Controlled version |
| Training | Staff IT training | — | 2,000,000 | Annual budget |
| Contingency | Emergency fund (10%) | — | 9,830,000 | — |
| **TOTAL** | | | **~108,130,000** | **~$28,500 USD** |

> **Note**: All figures are estimates based on typical Ugandan market rates as of 2026. Actual costs will vary. USD conversion at approximately 3,800 UGX = 1 USD.

---

## 12. KPIs — IT & Digital Operations

| KPI | Target (Lean) | Target (Controlled) | Measurement Frequency |
|-----|--------------|---------------------|----------------------|
| System uptime | > 95% | > 99% | Monthly |
| Helpdesk first-response time | < 4 hours | < 1 hour | Weekly |
| Helpdesk resolution rate (within SLA) | > 80% | > 90% | Monthly |
| Backup success rate | > 95% | > 99% | Weekly |
| Successful test restores | 1/quarter | 1/month | As scheduled |
| Security incidents | < 2/quarter | 0 critical/quarter | Monthly |
| MFA adoption rate | > 80% | 100% | Monthly |
| Password policy compliance | > 80% | > 95% | Monthly |
| Onboarding IT setup time | < 2 business days | < 1 business day | Per occurrence |
| Offboarding completion time | < 24 hours | < 4 hours | Per occurrence |
| Asset register accuracy | > 90% | > 98% | Quarterly |
| Staff security training completion | > 80% | 100% | Quarterly |
| Open helpdesk tickets (aging > 7 days) | < 5 | 0 | Weekly |

---

## 13. Related Documents

| Document Code | Title | Location |
|---------------|-------|----------|
| IT-ACC-001 | User Access Control SOP | `10-it-digital/sops/` |
| IT-BKP-001 | Backup and Disaster Recovery SOP | `10-it-digital/sops/` |
| IT-SEC-001 | Cyber Hygiene and Security Awareness SOP | `10-it-digital/sops/` |
| IT-HLP-001 | IT Helpdesk / Support Request SOP | `10-it-digital/sops/` |
| IT-ONB-001 | IT Onboarding and Offboarding SOP | `10-it-digital/sops/` |
| IT-TPL-001 | System Access Request Form | `10-it-digital/templates/` |
| IT-TPL-002 | IT Onboarding Checklist | `10-it-digital/templates/` |
| IT-TPL-003 | Password Policy Document | `10-it-digital/templates/` |
| IT-TPL-004 | Backup Verification Checklist | `10-it-digital/templates/` |
| IT-TPL-005 | IT Equipment Asset Register | `10-it-digital/templates/` |

---

## 14. Assumptions & Decisions Log

| # | Item | Type | Default Used | Action Required |
|---|------|------|-------------|-----------------|
| 1 | ERP platform | ASSUMPTION | Odoo (open source, cost-effective) | Confirm with directors |
| 2 | Email/collaboration platform | ASSUMPTION | Google Workspace | Confirm with directors |
| 3 | Company domain | ASSUMPTION | awdeerinvestments.co.ug | Confirm and register |
| 4 | Number of users (initial) | ASSUMPTION | 10 users | Confirm headcount |
| 5 | Hosting model for Odoo | ASSUMPTION | Cloud-hosted | Confirm cloud vs. on-premise |
| 6 | Internet provider | ASSUMPTION | Fiber + mobile backup | Confirm ISP |
| 7 | Password manager | ASSUMPTION | Bitwarden Teams | Confirm tool choice |
| 8 | BYOD policy stance | ASSUMPTION | Allowed with basic controls | Confirm policy direction |
| 9 | IT support model | ASSUMPTION | Outsourced / part-time (Lean) | Confirm staffing model |
| 10 | Backup storage | ASSUMPTION | Cloud + local NAS | Confirm infrastructure |
| 11 | Budget figures | ASSUMPTION | Based on 2026 Uganda market rates | Confirm actual quotes |
| 12 | Data residency requirements | QUESTION | Unknown | Confirm if data must stay in Uganda |
| 13 | Existing IT infrastructure | QUESTION | None assumed | Provide current inventory |
| 14 | Current email setup | QUESTION | None assumed | Provide current email details |
| 15 | Compliance requirements (NITA-U) | QUESTION | Unknown | Confirm regulatory requirements |

---

*Awdeer Investments Limited — IT & Digital Operations*
*Version 1.0 — February 2026*
