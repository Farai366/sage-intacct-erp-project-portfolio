# Process Mapping

## Purpose
Document key finance workflows in Sage Intacct using process maps. These diagrams illustrate how transactions flow through the system.

---

## Procure-to-Pay (P2P)

```mermaid
flowchart LR
    A[Purchase Request] --> B[Purchase Order]
    B --> C[Vendor Invoice]
    C --> D[Invoice Approval Workflow]
    D --> E[Payment Run]
    E --> F[Bank Integration]
    F --> G[Vendor Paid]
flowchart LR
    A[Customer Order] --> B[Invoice Generation]
    B --> C[Revenue Recognition]
    C --> D[Collections Tracking]
    D --> E[Cash Receipt]
    E --> F[Bank Reconciliation]
flowchart LR
    A[Transaction Entry] --> B[Reconciliations]
    B --> C[Adjusting Journals]
    C --> D[Review & Approval]
    D --> E[Financial Reporting]
    E --> F[Close Period]
