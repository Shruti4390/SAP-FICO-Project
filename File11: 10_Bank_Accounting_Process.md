# Bank Accounting Process

## Overview

Bank Accounting manages all incoming and outgoing bank transactions for Skyline Real Estate Management, ensuring proper recording of receipts, payments, and bank reconciliations.

**Business Scenario**

Monthly rental collections are deposited into the company’s bank account, while vendor payments and operational expenses are processed through the same account.

**Process Flow**

Customer Receipt → Bank Posting → Vendor Payment → Bank Reconciliation

**SAP Transaction Codes**

| Activity |	T-Code |
|----------|---------|
| Incoming Payment | F-28 |
| Outgoing Payment | F-53 |
| Display GL Account | FBL3N |
| Display Document | FB03 |

**Sample Journal Entry**

Dr. Bank Account …………….. USD 25,000

Cr. Customer Receivable ………. USD 25,000

**Expected Output**

Bank balances remain updated, customer payments are cleared, and bank reconciliation can be performed accurately.

**Business Benefits**

* Improved cash management
* Accurate bank reconciliation
* Real-time bank balance visibility
* Better liquidity monitoring
