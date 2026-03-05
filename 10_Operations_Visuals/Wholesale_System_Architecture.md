# Wholesale System Architecture

Wholesale operations depend on multiple integrated systems that support order processing, inventory management, logistics coordination, and financial transactions.

The following architecture illustrates how operational data flows between systems.

Retail Partner Systems
(NuOrder / JOOR / Retail Portals)
        │
        │ Purchase Orders
        ▼
EDI Integration Platform
(SPS Commerce / TrueCommerce)
        │
        ▼
Enterprise Resource Planning (ERP)
(NetSuite / SAP / Sage)
        │
        ├───────────────┐
        │               │
        ▼               ▼
Warehouse Management   Financial Systems
System (WMS)           (Billing / AR)
        │
        ▼
Logistics Systems
(Carriers / TMS)
        │
        ▼
Shipment Delivery
