# Accounts Payable (AP) Process

## Overview

The Accounts Payable process manages vendor invoices and payments for Skyline Real Estate Management, ensuring timely settlement of liabilities and accurate expense recording.

**Business Scenario**

A maintenance contractor submits an invoice of USD 5,000 for building repair services. The Finance team verifies and posts the invoice in SAP before processing payment.

**Process Flow**

Vendor Invoice Received → Invoice Verification → Invoice Posting → Vendor Payment → Vendor Account Updated

**SAP Transaction Codes**

| Activity | T-Code |
|----------|--------|
| Vendor Invoice | FB60 |
| Vendor Payment | F-53 |
| Vendor Line Items | FBL1N |
| Display Accounting Document | FB03 | 

**Sample Journal Entry**

Dr. Maintenance Expense …… USD 5,000

Cr. Vendor Payable ……….. USD 5,000

**Expected Output**

The vendor invoice is successfully posted, vendor balances are updated, and the expense is reflected in the General Ledger.

**Business Benefits**

* Timely vendor payments
* Reduced manual processing
* Improved expense tracking
* Better cash flow management
