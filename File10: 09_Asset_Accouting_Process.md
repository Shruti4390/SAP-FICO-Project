# Asset Accounting Process

## Overview

Asset Accounting (FI-AA) is used to manage and monitor the fixed assets of Skyline Real Estate Management. It records asset acquisitions, depreciation, transfers, retirements, and provides accurate asset valuation for financial reporting.

**Business Scenario**

Skyline purchases a new elevator system for one of its commercial buildings at a cost of USD 50,000. The asset is capitalized and depreciation is calculated automatically according to the company’s accounting policy.

**Process Flow**

Asset Creation → Asset Acquisition → Depreciation Calculation → Asset Reporting

**SAP Transaction Codes**

| Activity | T-Code |
|----------|--------|
| Create Asset Master | AS01 |
| Display Asset Master | AS03 |
| Asset Acquisition | F-90 |
| Asset Explorer | AW01N |
| Asset Retirement | F-92 |

**Sample Journal Entry**

Dr. Building Equipment Asset …… USD 50,000

Cr. Bank Account ……………… USD 50,000

**Expected Output**

The asset is successfully capitalized, depreciation is calculated periodically, and asset values are reflected in the Balance Sheet.

**Business Benefits**

* Accurate asset tracking
* Automated depreciation calculation
* Better capital expenditure management
* Improved statutory reporting
