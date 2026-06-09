# General Ledger (GL) Process

## Overview

The General Ledger (GL) is the core component of SAP FICO that records all financial transactions of Skyline Real Estate Management. Every accounting transaction from Accounts Payable, Accounts Receivable, Asset Accounting, and Bank Accounting ultimately updates the General Ledger.

**Business Scenario**

Skyline records monthly rental income and operating expenses for its residential and commercial properties. These transactions are automatically posted to the General Ledger, ensuring accurate financial reporting.

**Process Flow**

Business Transaction → SAP Posting → General Ledger Update → Financial Statements

**SAP Transaction Codes**

| Activity | T-Code |
|----------|--------|
| Post General Journal Entry | FB50 |
| Display Document | FB03 |
| Display GL Line Items | FBL3N |
| Reverse Document | FB08 |

**Sample Journal Entry**

Dr. Bank Account …………. USD 15,000

Cr. Rental Revenue ………. USD 15,000

**Expected Output**

The transaction updates the General Ledger and is reflected in the Balance Sheet and Profit & Loss Statement.

**Business Benefits**

* Centralized accounting records
* Accurate financial reporting
* Real-time financial visibility
* Faster month-end closing
