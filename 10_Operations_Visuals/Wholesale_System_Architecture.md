# Wholesale System Architecture

Wholesale operations depend on multiple integrated systems that support order processing, inventory management, logistics coordination, and financial transactions.

```text
Retail Partner Systems
        |
        v
EDI Platform / Retail Portal
        |
        v
ERP System
        |
        +--------------------+
        |                    |
        v                    v
Warehouse / WMS        Financial Systems
                            |
                            v
                      Billing / AR
        |
        v
Logistics / Carrier Systems
        |
        v
Shipment Delivery
```
