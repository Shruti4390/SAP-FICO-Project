# Leasing Revenue Process

## Overview

Leasing Revenue Management is one of the core financial processes for Skyline Real Estate Management. Rental income from residential and commercial properties is recorded, monitored, and reported through SAP FICO.

**Business Scenario**

A commercial tenant leases office space for USD 12,000 per month. The monthly rent invoice is generated, payment is received, and revenue is recognized in the General Ledger.

**Process Flow**

Lease Agreement → Monthly Rent Invoice → Customer Payment → Revenue Recognition → Financial Reporting

**SAP Transaction Codes**

| Activity | T-Code |
|----------|--------|
| Customer Invoice | FB70 |
| Incoming Payment | F-28 |
| Customer Line Items |	FBL5N |
| Display Accounting Document |	FB03 |

**Sample Journal Entry**

Dr. Customer Receivable ………. USD 12,000

Cr. Rental Revenue …………… USD 12,000

**Expected Output**

Rental revenue is recognized accurately, customer balances are updated, and management receives real-time revenue reports.

**Business Benefits**

* Accurate lease revenue recognition
* Improved receivable tracking
* Better cash flow forecasting
* Enhanced financial reporting
