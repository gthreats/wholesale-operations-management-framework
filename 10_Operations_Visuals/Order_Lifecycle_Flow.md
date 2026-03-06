# Wholesale Order Lifecycle Flow

This diagram illustrates the operational lifecycle of a wholesale order from purchase order receipt through payment completion.

```text
Retail Partner / Distributor
        |
        v
Purchase Order Received
        |
        v
Order Intake (EDI / Portal / Sales Entry)
        |
        v
Order QA Validation
(SKU / Pricing / Compliance)
        |
        v
ERP Order Creation
        |
        v
Inventory Allocation
        |
        v
Warehouse Fulfillment
(Pick / Pack / Label)
        |
        v
Shipment Execution
(Carrier Booking / Routing Compliance)
        |
        v
Shipment Confirmation
(ASN Transmission)
        |
        v
Invoice Generation
        |
        v
Payment Processing
```
