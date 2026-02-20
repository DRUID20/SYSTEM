# SOP: SAL-ORD-001 — Order Management

## Awdeer Investments Limited

| Field | Detail |
|-------|--------|
| SOP ID | SAL-ORD-001 |
| Title | Order Management |
| Version | 1.0 |
| Effective Date | February 2026 |
| Owner | Sales Manager |
| Approved By | Managing Director |
| Review Cycle | Annually or upon significant change |
| Classification | Internal |

---

## 1. Purpose

This SOP defines the standard process for receiving, validating, entering, fulfilling, and closing customer orders. It ensures accurate order capture, proper credit controls, timely fulfilment coordination, correct invoicing handoff, and complete order lifecycle tracking from signed contract/PO to final payment and closure.

---

## 2. Scope

| In Scope | Out of Scope |
|----------|-------------|
| Order receipt and validation | Quotation preparation (see SAL-QTC-001) |
| Credit check and approval | Warehouse picking/packing/shipping (see Part E — Inventory) |
| Order entry in ERP/system | Financial invoicing and accounting (see Part C — Finance) |
| Order confirmation to customer | Procurement of materials (see Part D — Procurement) |
| Fulfilment coordination with Operations | Customer complaint handling (see SAL-CMP-001) |
| Delivery confirmation and sign-off | |
| Invoice trigger and handoff to Finance | |
| Payment monitoring and follow-up | |
| Order closure | |

---

## 3. RACI Matrix

| Activity | Sales Executive | Sales Manager | Operations Manager | Finance / AR | MD |
|----------|:-:|:-:|:-:|:-:|:-:|
| Receive and validate order/PO | R | A | I | I | — |
| Perform credit check (new/large) | I | I | — | R/A | C (large) |
| Enter order in ERP/system | R | A | I | I | — |
| Send order confirmation to customer | R | I | I | — | — |
| Coordinate fulfilment with Operations | R | I | R/A | — | — |
| Track fulfilment progress | R | I | R | — | — |
| Confirm delivery (customer sign-off) | I | I | R/A | — | — |
| Trigger invoice to Finance | R | I | I | R/A | — |
| Monitor payment and follow up | C | I | — | R/A | I (overdue) |
| Close order in system | R | A | C | C | — |
| Resolve order discrepancies | R | A | C | C | C (escalated) |
| Monthly order report | I | R/A | C | C | I |

---

## 4. Inputs & Outputs

### 4.1 Inputs

| Input | Source | Format |
|-------|--------|--------|
| Signed contract, PO, or written acceptance | Customer via Sales Executive | PDF, email, physical document |
| Approved quotation | SAL-QTC-001 output | Quotation document (SAL-TPL-002) |
| Customer master data (segment, credit terms) | CRM / ERP | System record |
| Product/service availability | Operations / Inventory | Stock status, capacity |
| Credit limit and payment history | Finance / AR | ERP or credit file |

### 4.2 Outputs

| Output | Destination | Format |
|--------|------------|--------|
| Order confirmation to customer | Customer | Email / printed document |
| Sales order in ERP/system | ERP / Order tracker | System record |
| Fulfilment request to Operations | Operations Manager | Work order / dispatch request |
| Delivery note (signed by customer) | File / CRM | Scanned PDF / physical |
| Invoice request to Finance | Finance / AR | Invoice trigger in ERP or email |
| Order closure record | CRM / ERP | System record |
| Monthly order fulfilment report | Sales Manager, MD | Report |

---

## 5. Step-by-Step Workflow

### Step 1: Receive Customer Order

| Detail | Description |
|--------|------------|
| **Action** | Receive signed contract, customer PO, or formal written acceptance from the customer |
| **Who** | Sales Executive |
| **How** | Customer provides via email, hand delivery, or through CRM portal |
| **SLA** | Acknowledge receipt to customer same business day |
| **Notes** | If order is verbal only (e.g., phone), send written confirmation request to customer before proceeding |

### Step 2: Validate Order Against Quotation

| Detail | Description |
|--------|------------|
| **Action** | Verify that the customer's order matches the approved quotation in all material respects |
| **Who** | Sales Executive; Sales Manager confirms |
| **Checklist** | Products/services match quotation line items; Quantities match; Unit prices and total match; Payment terms match; Delivery terms and timeline match; Customer details (name, address, contact) are correct; VAT treatment is correct |
| **SLA** | Same business day as order received |
| **If discrepancy found** | Flag to Sales Manager; do not enter order until discrepancy is resolved with the customer |

### Step 3: Credit Check

| Detail | Description |
|--------|------------|
| **Action** | Perform a credit assessment before confirming the order |
| **Who** | Finance / AR Officer; Finance Manager approves |
| **When required** | New customers (first order); Existing customers exceeding credit limit; Orders > UGX 20,000,000; Customers with overdue invoices |
| **How** | Check customer payment history; Verify current outstanding balance; Confirm credit limit; For new customers: request trade references or advance payment |
| **Outcomes** | Approved: proceed to order entry; Conditional: proceed with modified terms (e.g., advance payment, reduced order); Declined: notify Sales Manager, Sales Executive communicates to customer |
| **SLA** | 1 business day |
| **Lean version** | MD makes credit decisions informally based on relationship and payment history |

### Step 4: Enter Order in System

| Detail | Description |
|--------|------------|
| **Action** | Create a formal sales order in the ERP or order tracking system |
| **Who** | Sales Executive |
| **How** | Enter: customer, order date, line items, quantities, prices, delivery date, payment terms, special instructions |
| **Order Number** | Sequential format: `AWD-SO-YYYY-NNNN` (e.g., AWD-SO-2026-0001) |
| **SLA** | Same business day as credit check approval |
| **Notes** | Attach signed quotation/contract and PO to the order record |

### Step 5: Send Order Confirmation to Customer

| Detail | Description |
|--------|------------|
| **Action** | Generate and send an order confirmation to the customer |
| **Who** | Sales Executive |
| **How** | Order confirmation includes: order number, line items, confirmed delivery date, payment terms, contact for queries |
| **SLA** | Same business day as order entry |
| **Controlled version** | Auto-generated from ERP and emailed to customer |
| **Lean version** | Email confirmation prepared manually referencing the order |

### Step 6: Coordinate Fulfilment

| Detail | Description |
|--------|------------|
| **Action** | Hand off the order to Operations for fulfilment (product delivery or service execution) |
| **Who** | Sales Executive (initiates); Operations Manager (executes) |
| **How** | Create fulfilment/work order from sales order; communicate delivery requirements, customer address, special instructions, timeline |
| **SLA** | Fulfilment handoff same day as order entry |
| **Coordination** | If stock is unavailable: Operations notifies Sales Executive; Sales Executive communicates revised timeline to customer; If make-to-order: Sales Executive initiates purchase requisition per Procurement (Part D) |

### Step 7: Track Fulfilment Progress

| Detail | Description |
|--------|------------|
| **Action** | Monitor the progress of order fulfilment and keep the customer informed |
| **Who** | Sales Executive (customer communication); Operations Manager (execution tracking) |
| **How** | Regular check-ins with Operations; proactive customer updates if delays arise |
| **SLA** | Customer updated within 24 hours of any change to committed delivery date |
| **Lean version** | Informal check via WhatsApp/phone with Operations Manager |
| **Controlled version** | ERP workflow status tracking; automated alerts for delays |

### Step 8: Delivery Confirmation

| Detail | Description |
|--------|------------|
| **Action** | Confirm that the product has been delivered or service has been completed, with customer acknowledgement |
| **Who** | Operations (delivers); Customer (signs); Sales Executive (files) |
| **How** | Customer signs delivery note or acknowledgement form at point of delivery; For services: customer signs completion certificate or acceptance email |
| **SLA** | Signed delivery note obtained at time of delivery |
| **Notes** | If customer raises issues at delivery, log per SAL-CMP-001 (Complaint Handling) |
| **Filing** | Scanned/photographed delivery note attached to order record in system |

### Step 9: Trigger Invoice

| Detail | Description |
|--------|------------|
| **Action** | Request Finance to generate the customer invoice based on confirmed delivery |
| **Who** | Sales Executive (triggers); Finance / AR (generates invoice) |
| **How** | In ERP: confirm delivery on sales order, which triggers invoice generation; or send invoice request email to Finance with: order number, delivery confirmation, billing details |
| **SLA** | Invoice generated within 2 business days of confirmed delivery |
| **Control** | Invoice must match sales order and delivery note (three-way match) |

### Step 10: Monitor Payment

| Detail | Description |
|--------|------------|
| **Action** | Track customer payment against invoice and follow up on overdue amounts |
| **Who** | Finance / AR Officer (primary); Sales Executive (supports) |
| **How** | AR aging report reviewed weekly; Payment follow-up per Finance SOP; Sales Executive assists with customer relationship for overdue > 30 days |
| **Escalation** | Overdue 15 days: AR Officer reminder; Overdue 30 days: Sales Manager + AR Officer escalate; Overdue 60 days: MD + Finance Manager review, potential service suspension; Overdue 90 days: MD decision on legal action or write-off |
| **SLA** | First follow-up within 5 days of due date |

### Step 11: Close Order

| Detail | Description |
|--------|------------|
| **Action** | Close the order in the system once fully delivered and fully paid |
| **Who** | Sales Executive; Sales Manager confirms |
| **How** | Verify: all items delivered (delivery note on file); invoice issued; payment received in full; no outstanding disputes |
| **SLA** | Within 5 business days of final payment received |
| **Notes** | If partial delivery or partial payment: order remains open with notes until fully resolved |

---

## 6. Controls & Approvals

| Control Point | Control Description | Owner |
|--------------|-------------------|-------|
| Order-to-quotation match | Every order is validated against the approved quotation before entry | Sales Manager |
| Credit check before fulfilment | Orders above threshold or for new customers require Finance approval | Finance Manager |
| Sequential order numbering | Prevents missing or duplicate orders | ERP system / Sales Manager |
| Three-way match (order-delivery-invoice) | Invoice amount matches order and delivery note | Finance |
| Delivery sign-off | Customer acknowledges receipt; proof of delivery on file | Operations Manager |
| Segregation: sell vs collect | Sales does not handle cash or payment processing | Finance / MD |
| Payment monitoring | AR aging reviewed weekly; overdue escalation path defined | Finance Manager |
| Order closure verification | Order not closed until delivery complete and payment received | Sales Manager |
| No verbal-only orders | All orders must have written documentation (PO, email, signed acceptance) | Sales Executive |
| Monthly reconciliation | Open orders reconciled monthly; stale orders investigated | Sales Manager + Finance |

---

## 7. Documents & Forms

| Document | Reference | Purpose |
|----------|-----------|---------|
| Quotation Template | SAL-TPL-002 | Reference for order validation |
| Sales Contract Outline | SAL-TPL-004 | Formal contract for high-value orders |
| Lead Tracking Sheet | SAL-TPL-001 | Pipeline reference |
| Delivery Note | (Operations template) | Proof of delivery signed by customer |
| Sales Order Form | (ERP-generated) | System record of order |
| Invoice | (Finance template) | Customer billing document |
| AR Aging Report | (Finance) | Payment monitoring |

---

## 8. KPIs

| KPI | Definition | Target | Measurement Frequency |
|-----|-----------|--------|----------------------|
| Order Entry Accuracy | % of orders entered without errors (matching quotation) | > 98% | Monthly |
| Order Confirmation Time | Average time from order receipt to confirmation sent | Same day | Monthly |
| On-Time Delivery Rate | % of orders delivered on or before committed date | > 95% | Monthly |
| Order Fill Rate | % of order line items fulfilled completely on first delivery | > 90% | Monthly |
| Order-to-Cash Cycle Time | Average days from order entry to payment received | < 45 days (depends on terms) | Monthly |
| Invoice Accuracy | % of invoices issued without requiring credit note or correction | > 99% | Monthly |
| Overdue Receivables Ratio | Value of overdue invoices / Total outstanding AR | < 15% | Weekly |
| Order Dispute Rate | % of orders with customer-raised discrepancies | < 5% | Monthly |
| Open Order Aging | Average age of open (unfulfilled) orders | < 14 days | Weekly |
| Monthly Order Volume | Number and value of orders processed | Track trend | Monthly |

---

## 9. Lean Version — Summary

| Element | Lean Approach |
|---------|--------------|
| Order receipt | Sales Lead receives PO/acceptance by email or in person |
| Validation | Sales Lead manually compares order to quotation |
| Credit check | MD decides on credit for new customers; no formal process for existing |
| Order entry | Logged in spreadsheet or simple order tracker |
| Order confirmation | Email from Sales Lead to customer |
| Fulfilment coordination | Direct communication with Operations Manager (phone/WhatsApp) |
| Delivery confirmation | Photo of signed delivery note sent via WhatsApp; filed in shared folder |
| Invoice trigger | Email to Finance Manager with order details and delivery confirmation |
| Payment monitoring | Finance Manager tracks; Sales Lead follows up if asked |
| Order closure | Sales Lead marks as closed in spreadsheet when paid |
| Reporting | Monthly summary: orders received, fulfilled, outstanding |

---

## 10. Controlled Version — Summary

| Element | Controlled Approach |
|---------|-------------------|
| Order receipt | Logged in CRM/ERP from signed PO/contract |
| Validation | Sales Manager verifies order-to-quotation match in ERP |
| Credit check | Formal credit check via Finance; credit limits in ERP |
| Order entry | Full ERP sales order with auto-numbering, stock reservation |
| Order confirmation | Auto-generated from ERP, emailed to customer |
| Fulfilment coordination | ERP workflow: sales order triggers picking/delivery in Operations module |
| Delivery confirmation | Delivery note generated from ERP, signed, scanned, attached |
| Invoice trigger | Automatic: confirmed delivery in ERP triggers invoice generation |
| Payment monitoring | Automated AR aging alerts; structured escalation per aging brackets |
| Order closure | System closes order when delivery confirmed + payment applied |
| Reporting | Dashboard: order volume, fill rate, on-time delivery, order-to-cash cycle |
| Analytics | Trend analysis by business line, customer segment, delivery performance |

---

## 11. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | February 2026 | Sales Manager | Initial release |

---

*Awdeer Investments Limited — Business Operating System*
