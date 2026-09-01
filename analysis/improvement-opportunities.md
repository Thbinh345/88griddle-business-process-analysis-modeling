# Improvement Opportunities

> Improvement opportunities are derived from the identified process pain points. They describe potential business and process improvements rather than prescribing a specific technical implementation.

---

## 01. Reduce Invoice Rework

**Related Pain Point:** 01

### Opportunity

Improve the payment workflow so that the final order information is consolidated and verified before the payment transaction is completed.

### Expected Outcome

- Reduce repeated invoice printing
- Reduce cashier rework
- Shorten the payment cycle
- Improve billing accuracy

## 02. Automate Deposit Status Verification

**Related Pain Point:** 02

### Opportunity

Move deposit-status verification from a manual cashier activity to the restaurant system.

The system should retrieve the customer's reservation and deposit status from the recorded reservation information and automatically determine whether a deposit has been made.

If a deposit exists, the system applies the deposit deduction to the payment amount; otherwise, the full invoice amount is used.

### Expected Outcome

- Remove an unnecessary manual verification step
- Reduce cashier workload
- Improve consistency between reservation and payment information
- Support faster payment processing

## 03. Improve Information Consistency Across Order & Payment

**Related Pain Points:** 03

### Opportunity

Establish a consistent flow of order, invoice, deposit and payment-status information across service staff, kitchen and cashier activities.

The restaurant system should act as the central reference point for current transaction information.

### Expected Outcome

- Reduce repeated manual verification
- Improve information consistency
- Reduce dependency on manual handoffs
- Support faster coordination between functions



## 04. Streamline Additional-Order Handling

**Related Pain Point:** 04

### Opportunity

Allow additional items to be associated with the customer's existing order instead of restarting the full order-processing cycle.

The process should update the existing order and notify the relevant downstream function.

### Expected Outcome

- Reduce repeated processing steps
- Simplify service-to-kitchen coordination
- Improve handling of additional orders



## 05. Standardize Exception Handling

**Related Pain Point:** 05

### Opportunity

Define explicit handling paths for recurring exception scenarios, including:

- Unavailable table
- Out-of-stock item
- Quantity discrepancy
- Quality failure
- Failed delivery
- Incorrect invoice
- Payment discrepancy

Each exception should clearly identify:

**Trigger → Decision → Responsible role → Next action → Resolution**

### Expected Outcome

- Improve process consistency
- Reduce ambiguity during exception handling
- Make operational responsibilities clearer
- Support future system requirements



## 06. Strengthen Cash Reconciliation Control

**Related Pain Point:** 03

### Opportunity

Structure the end-of-shift reconciliation process around a clear control sequence:

**Expected Amount → Actual Amount → Variance → Verification → Resolution → Handover**

### Expected Outcome

- Improve financial control
- Make discrepancies easier to identify and resolve
- Clarify accountability during shift closing

---

## Improvement Priority Matrix

| Opportunity | Process Impact | Business Value | 
|---|---|---|
| 01. Reduce Invoice Rework | Payment | High | 
| 02. Deposit Status Verification | Payment | High | 
| 03. Improve Information Consistency | Cross-process | High | 
| 04. Streamline Additional Orders | Service / Kitchen | Medium | 
| 05. Standardize Exception Handling | Cross-process | High | 
| 06. Strengthen Cash Reconciliation | Cash reconciliation | High | 

---

## Recommendation

For the To-Be modeling phase, **Payment** is selected as the first improvement candidate because it combines:

- Invoice verification
- Rework handling
- Deposit deduction
- Multiple payment methods
- Optional VAT invoice handling
- Payment confirmation

This makes it a suitable process for demonstrating how an identified As-Is issue can be translated into a future-state process model.
