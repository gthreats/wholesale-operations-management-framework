# Wholesale System Architecture

Wholesale operations depend on multiple integrated systems that support order processing, inventory management, logistics coordination, and financial transactions.

The following architecture illustrates how operational data flows between systems.

```mermaid
flowchart TD
A[Retail Partner Systems] -->|Purchase Orders| B[EDI Integration Platform]
B --> C[ERP System]
C --> D[Warehouse Management System]
C --> E[Financial Systems]
D --> F[Logistics Systems]
F --> G[Shipment Delivery]
```
