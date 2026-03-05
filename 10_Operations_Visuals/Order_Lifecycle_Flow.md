# Wholesale Order Lifecycle Flow

This diagram illustrates the operational lifecycle of a wholesale order from purchase order receipt through payment completion.

```
Retail Partner / Distributor
        │
        │ Purchase Order
        ▼
Order Intake
(EDI / Portal / Sales Entry)
        │
        ▼
Order QA Validation
(SKU / Pricing / Compliance)
        │
        ▼
ERP Order Creation
        │
        ▼
Inventory Allocation
        │
        ▼
Warehouse Fulfillment
(Pick / Pack / Label)
        │
        ▼
Shipment Execution
(Carrier Booking / Routing Compliance)
        │
        ▼
Shipment Confirmation
(ASN Transmission)
        │
        ▼
Invoice Generation
        │
        ▼
Payment Processing
```
