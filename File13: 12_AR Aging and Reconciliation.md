# AR Aging and Reconciliation

## Overview

Accounts Receivable (AR) Aging is used to monitor outstanding customer balances based on the number of days invoices remain unpaid. It helps Skyline Real Estate Management improve collections and maintain healthy cash flow.

**Business Scenario**

A tenant has not paid the monthly rent for 45 days. The Finance team reviews the AR Aging Report and follows up for payment while reconciling the customer account.

**Process Flow**

Customer Invoice → Outstanding Balance → AR Aging Analysis → Customer Follow-up → Payment Collection → Reconciliation

**SAP Transaction Codes**

| Activity | T-Code | 
|----------|--------|
| Customer Line Items | FBL5N |
| Incoming Payment | F-28 |
| Display Accounting Document | FB03 |

**Sample Journal Entry**

Dr. Bank Account ………….. USD 10,000

Cr. Customer Receivable ……. USD 10,000

**Expected Output**

Outstanding customer balances are monitored, overdue invoices are identified, and customer accounts are reconciled accurately.

**Business Benefits**

* Improved collection efficiency
* Better cash flow management
* Reduced outstanding receivables
* Accurate customer account reconciliation
