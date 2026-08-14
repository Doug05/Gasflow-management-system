\# Features



\## Cylinder Inventory



\- Unique Cylinder IDs

\- Filled Cylinder Tracking

\- Empty Cylinder Tracking

\- Refill Tracking

\- Cylinder Status Monitoring

\- Cylinder History

```mermaid
flowchart TD

A[Customer]

A --> B[Request Cylinder]

B --> C[Assign Cylinder]

C --> D[Generate Invoice]

D --> E[Receive Payment]

E --> F[Update Records]

F --> G[Reports]
```

\## Customer Management



\- Unique Customer IDs

\- Customer Records

\- Contact Information

\- Cylinder Assignment History

\- Transaction History



\## Billing



\- Invoice Generation

\- GST Support

\- Billing Records

\- Invoice History



\## Payments \& Deposits



\- Payment Tracking

\- Deposit Tracking

\- Outstanding Balance Monitoring

```mermaid
flowchart TD

A[New Cylinder]

A --> B[Inventory]

B --> C[Available]

C --> D[Assigned]

D --> E[Returned]

E --> F[Refilling]

F --> C
```

\## Dashboard



\- Inventory Overview

\- Customer Statistics

\- Payment Status

\- Operational Alerts



\## Reporting



\- Sales Reports

\- Inventory Reports

\- Customer Reports

\- Excel Export

\- CSV Export

\- Power BI Integration

```mermaid
flowchart TD

A[Customer Transaction]

A --> B[Generate Invoice]

B --> C[GST Calculation]

C --> D[Final Bill]

D --> E[Payment Tracking]

E --> F[Invoice History]
```

\## Backup



\- Google Drive Backup

\- Restore Functionality



\## Deployment



\- Packaged Desktop Application

\- Local Database Storage

