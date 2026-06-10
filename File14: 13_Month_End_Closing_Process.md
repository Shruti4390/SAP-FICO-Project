# Month-End Closing Process

## Overview

The Month-End Closing process ensures that all financial transactions are posted, reconciled, and reviewed before preparing monthly financial statements.

**Business Scenario**

At the end of every month, Skyline performs vendor reconciliation, customer reconciliation, depreciation posting, accrual posting, and General Ledger review before generating financial reports.

**Process Flow**

Transaction Review → Reconciliations → Adjustments → Closing Entries → Financial Statements

**SAP Transaction Codes**

| Activity | T-Code |
|----------|--------|
| Display Document | FB03 |
| Reverse Document | FB08 |
| GL Line Items | FBL3N |
| Vendor Line Items | FBL1N |
| Customer Line Items | FBL5N |

**Closing Activities**

* Verify General Ledger balances
* Review Vendor Accounts
* Review Customer Accounts
* Post Accruals
* Verify Depreciation
* Perform Bank Reconciliation
* Generate Financial Reports

**Business Benefits**

* Accurate financial statements
* Faster month-end close
* Better audit readiness
* Improved financial control
