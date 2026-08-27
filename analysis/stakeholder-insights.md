# Stakeholder Insights

## Overview

The process analysis was developed based on requirement-gathering with the **Restaurant Manager** and subsequent analysis of the documented operational processes.

The objective is to understand how responsibilities, information and decisions are distributed across the restaurant's operations.

---

## Key Stakeholders & Operational Roles

### Primary Stakeholder

| Stakeholder | Process Involvement | Role in Analysis |
|---|---|---|
| **Restaurant Manager** | Reservation, Supplier Receiving, Cash Reconciliation | Primary stakeholder interviewed for business-process information and operational requirements |

### Operational Roles Identified in the Process Models

| Role | Process Involvement |
|---|---|
| Customer | Reservation, Customer Service, Delivery, Payment |
| Service Staff | Customer Service, Delivery, Reservation Support |
| Kitchen Staff | Supplier Receiving, Kitchen Preparation |
| Cashier | Payment, Cash Reconciliation |
| Supplier | Supplier Receiving |

### System

| System | Process Involvement |
|---|---|
| Restaurant System | Reservation, Customer Service, Delivery, Payment |
---

## Process-Level Insights

### 01. Reservation

The reservation process is driven by table availability and includes multiple decision paths covering deposit confirmation, waiting-list handling, reservation confirmation and cancellation/refund.

The system supports reservation information display and table-status updates. 

**BA Insight:**  
Reservation management depends on accurate and timely visibility of table status, customer information and deposit status.

---

### 02. Supplier Receiving

The receiving process validates incoming goods against two main dimensions: **quantity** and **quality**.

When received goods do not meet the expected condition, the process branches into supplementary delivery or return handling.

**BA Insight:**  
Receiving is not simply a goods handover process; it requires exception handling and communication between the restaurant, kitchen and supplier.

---

### 03. Kitchen Preparation

The kitchen receives order information from the system, prepares the food, and determines the appropriate preparation outcome based on whether the order is for dine-in or delivery/takeaway.

**BA Insight:**  
Kitchen execution is dependent on the accuracy and availability of upstream order information.

---

### 04. Customer Service

The serving process includes order entry through a tablet, system update, kitchen coordination, food serving, additional orders and unavailable-item handling.

Additional orders trigger the ordering flow again, while unavailable items require the customer to select an alternative.

**BA Insight:**  
Customer service is an iterative process with repeated coordination between customer, service staff, system and kitchen.

---

### 05. Delivery

Online orders require coordination among the system, service staff, kitchen and customer.

The process contains alternative outcomes for successful and unsuccessful delivery and includes payment-status verification before completion.

**BA Insight:**  
Delivery combines operational fulfillment with customer communication and payment-status control.

---

### 06. Payment

The payment process includes invoice retrieval, customer verification, invoice correction, deposit deduction, payment-method selection and optional VAT invoice handling.

Three payment methods are supported: cash, bank transfer and card.

**BA Insight:**  
Payment contains several verification and decision points, making accuracy and information consistency critical before the transaction is completed.

---

### 07. Cash Reconciliation

At the end of a shift, the cashier checks the cash balance, classifies invoices by payment method and compares actual amounts with system records.

A discrepancy triggers another verification step before the shortage is resolved or revenue is handed over to management.

**BA Insight:**  
Cash reconciliation functions as a control point between operational transactions and financial accountability.

---

## Cross-Process Insights

Several patterns appear across the current-state processes:

1. **High interdependency between stakeholders**  
   Customer requests frequently move across service staff, kitchen, cashier, management and the system.

2. **Multiple decision and exception points**  
   The processes contain branches for unavailable tables, unavailable items, quantity/quality discrepancies, failed deliveries, incorrect invoices and payment discrepancies.

3. **Repeated verification activities**  
   Information is checked at several points, particularly reservation, payment and cash reconciliation.

4. **Strong dependency on operational information**  
   Table status, order information, invoice information, deposit status and payment status are repeatedly used as decision inputs.

---

## BA Takeaway

The current operating model is highly dependent on coordination between people and the restaurant system.

Across the 7 core processes, the main analytical themes are:

**Information consistency → Cross-functional handoffs → Exception handling → Verification & control**

These themes form the basis for identifying process pain points and improvement opportunities.
