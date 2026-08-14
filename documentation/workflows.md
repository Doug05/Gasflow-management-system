mermaid
flowchart LR

A[Available Cylinder]
--> B[Assigned To Customer]

B --> C[Returned By Customer]

C --> D[Sent For Refilling]

D --> E[Refilling Process]

E --> F[Returned From Filler]

F --> A

\# Workflows



\## Customer Cylinder Assignment



Available Cylinder

↓

Assign to Customer

↓

Update Inventory

↓

Create Transaction Record



\## Cylinder Return



Customer Returns Cylinder

↓

Inventory Updated

↓

Cylinder Available



\## Refill Workflow



Available Empty Cylinder

↓

Send To Filler

↓

Refilling

↓

Receive Filled Cylinder

↓

Inventory Updated



\## Billing Workflow



Customer Transaction

↓

Invoice Generation

↓

GST Calculation

↓

Payment Tracking



\## Backup Workflow



Application Data

↓

Google Drive Backup

↓

Secure Storage

↓

Restore When Needed

mermaid
flowchart TD

A[Customer]

A --> B[Payment]

A --> C[Deposit]

B --> D[Payment Records]

C --> E[Deposit Records]

D --> F[Analytics]

E --> F
