# ReceivablesIQ — Accounts Receivable & Cash Flow Risk Analytics

## Project Overview

ReceivablesIQ is a Power BI analytics project designed to help businesses monitor accounts receivable, track customer payments, identify overdue invoices, and understand outstanding balances.

The dashboard provides insights into invoice performance, payment collection trends, customer-level receivables, and dispute resolution.

## Business Problem

Businesses often face challenges in tracking unpaid invoices, monitoring overdue payments, and identifying customers who contribute significantly to outstanding receivables.

Without a consolidated view of accounts receivable, finance teams may struggle to monitor collection performance and identify potential cash flow risks.

**ReceivablesIQ addresses this problem by bringing invoice, payment, customer, and dispute data together in an interactive dashboard.**

## Project Objectives

- Monitor total invoiced and collected amounts.
- Identify outstanding and overdue receivables.
- Analyse monthly invoice and payment trends.
- Understand invoice payment distribution.
- Identify customers with the highest outstanding and overdue amounts.
- Monitor dispute resolution status.
- Enable interactive analysis using slicers.

## Tools & Technologies

- **Power BI** — Dashboard development and visualisation
- **Power Query** — Data transformation and preparation
- **DAX** — Measures and business calculations
- **CSV** — Data sources

## Dataset

The project uses seven CSV files:

| Dataset | Description |
|---|---|
| customers.csv | Customer information |
| invoices.csv | Invoice details and amounts |
| payments.csv | Payment transactions |
| payment_applications.csv | Payment allocation against invoices |
| disputes.csv | Invoice dispute information |
| collection_activities.csv | Collection follow-up activities |
| date.csv | Calendar and date attributes |

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Invoice Amount | 3.49 BN |
| Total Payment Received | 2.90 BN |
| Outstanding Amount | 606.88 M |
| Overdue Amount | 606.88 M |
| Future Due Amount | 0.00 |

## Dashboard Features

### 1. Monthly Invoice vs Payment Trend
A line chart comparing monthly invoiced amounts with payments received to understand billing and collection patterns.

### 2. Invoice Payment Distribution
A donut chart showing the proportion of:
- Paid Invoices — 77.17%
- Unpaid Invoices — 14.55%
- Partially Paid Invoices — 8.28%

### 3. Disputed by Status
A donut chart showing:
- Resolved Disputes — 56.7%
- Open Disputes — 43.3%

### 4. Top 7 Customers by Outstanding Amount
Identifies customers contributing the highest outstanding balances.

### 5. Top 7 Customers by Overdue Amount
Highlights customers with the highest overdue receivables.

## Interactive Filters

The dashboard includes:
- Year
- Dispute Status
- Region

These slicers allow users to explore the data using different filters.

## Key Business Insights

- Total invoiced value is approximately 3.49 billion, while payments received are approximately 2.90 billion.
- Outstanding receivables amount to approximately 606.88 million.
- The entire outstanding balance is currently classified as overdue in the displayed reporting period.
- Paid invoices account for 77.17% of invoices.
- Open disputes account for 43.3% of recorded disputes.
- Customer-level analysis highlights the accounts contributing most to outstanding and overdue balances.

## Project Structure

```text
ReceivablesIQ/
│
├── Dashboard/
│   └── ReceivablesIQ.pbix
│
├── Dataset/
│   └── CSV files
│
├── Screenshots/
│   └── Dashboard screenshots
│
├── Images/
│   └── Project images and logo
│
└── README.md
```

## Conclusion

ReceivablesIQ demonstrates how business intelligence and data analytics can help finance teams monitor receivables, evaluate payment performance, identify overdue customer balances, and gain better visibility into cash flow risks.

---

**Project Type:** Business Intelligence / Financial Analytics  
**Domain:** Accounts Receivable & Finance  
**Developed using:** Microsoft Power BI