# Pain Point Analysis

> Pain points below are derived from stakeholder context and the documented As-Is process models. 
---

## 01. Invoice Rework During Payment

### Process Evidence

The customer reviews the invoice before payment. When information is incorrect, the cashier rechecks the order, reprints the invoice and asks the customer to verify it again.

### Pain Point

The payment process contains a rework loop caused by incorrect invoice information.

### Business Impact / Risk

- Extends the payment cycle
- Increases cashier workload
- Creates additional opportunities for repeated correction


## 02. Repeated Manual Verification

### Process Evidence

Verification activities appear across several processes, including:

- Table availability and reservation information
- Deposit status
- Order and invoice information
- Payment status
- Cash reconciliation

### Pain Point

The same or related information must be checked at multiple stages before the process can continue.

### Business Impact / Risk

- Additional operational effort
- Greater dependency on staff accuracy
- Higher risk of inconsistent information between process stages
  


## 03. Repeated Processing for Additional Orders

### Process Evidence

During customer service, additional orders are accepted and processed. After an additional order is recorded, the process returns to the temporary-invoice stage before kitchen processing continues.

### Pain Point

Additional orders introduce a repeated processing cycle instead of extending the existing order flow directly.

### Business Impact / Risk

- Additional processing steps
- More coordination between service staff and kitchen
- Potential increase in order-processing time



## 04. Exception-Driven Process Loops

### Process Evidence

Multiple processes contain exception branches that require additional processing or return to previous activities:

| Process | Exception |
|---|---|
| Reservation | No available table / customer cancellation |
| Supplier Receiving | Quantity shortage / quality failure |
| Customer Service | Out of stock item |
| Delivery | Unsuccessful delivery |
| Payment | Incorrect invoice |
| Cash Reconciliation | Cash discrepancy |

### Pain Point

Exception handling is distributed across multiple branches and often requires additional verification, communication or reprocessing.

### Business Impact / Risk

- Longer process cycle in exception cases
- Higher coordination effort
- Increased operational complexity

---

## Priority Summary

| ID | Pain Point | Priority | Process Impact |
|---|---|---|---|
| 01 | Invoice rework | High | Payment |
| 02 | Repeated verification | High | Reservation / Payment / Reconciliation |
| 03 | Repeated additional-order processing | Medium | Customer Service / Kitchen |
| 04 | Exception-driven loops | High | Cross-process |

---

## Interpretation

The most significant improvement themes are not isolated activities but recurring patterns across the operating model:

**Reduce rework → Improve information consistency → Simplify exception handling → Strengthen operational control**
