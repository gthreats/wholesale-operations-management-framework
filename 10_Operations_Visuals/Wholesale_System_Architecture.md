# Wholesale System Architecture

Wholesale operations depend on multiple integrated systems that support order processing, inventory management, logistics coordination, and financial transactions.

The following architecture illustrates how operational data flows between systems.

```mermaid
flowchart TD

A[Retail Partner Systems<br>NuOrder / JOOR / Retail Portals]
B[EDI Integration Platform<br>SPS Commerce / TrueCommerce]
C[Enterprise Resource Planning (ERP)<br>NetSuite / SAP / Sage]
D[Warehouse Management System (WMS)]
E[Financial Systems<br>Billing / Accounts Receivable]
F[Logistics Systems<br>Carriers / TMS]
G[Shipment Delivery]

A -->|Purchase Orders| B
B --> C
C --> D
C --> E
D --> F
F --> G
```
