# Accounts Receivable (AR) Process

## Overview

The Accounts Receivable process manages customer billing, lease revenue recognition, payment collection, and outstanding receivable tracking for Skyline Real Estate Management.

**Business Scenario**

A commercial tenant is billed USD 10,000 for monthly office rent. The invoice is created in SAP, and payment is tracked until collection.

**Process Flow**

Customer Invoice → Customer Billing → Payment Collection → Customer Account Update → AR Aging Report

**SAP Transaction Codes**

| Activity | T-Code |
|----------|--------|
| Customer Invoice | FB70 |
| Incoming Payment | F-28 |
| Customer Line Items | FBL5N |
| Display Accounting Document | FB03 |

**Sample Journal Entry**

Dr. Customer Receivable …… USD 10,000

Cr. Rental Revenue ……….. USD 10,000

**Expected Output**

The customer balance is updated, rental income is recognized, and the transaction appears in financial reports.

**Business Benefits**

* Improved receivable tracking
* Faster payment collection
* Accurate lease revenue accounting
* Better cash flow visibility
