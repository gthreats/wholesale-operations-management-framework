# Operations Toolkit (Example)
This folder contains example operational tools used to support wholesale operations management.

## Tools Included

### Operations Performance Dashboard
Tracks operational KPIs such as order accuracy, fulfillment performance, and routing compliance.

### Inventory Tracking Model
Provides visibility into available inventory, reserved inventory, and reorder thresholds across warehouse locations.

### Order Status Report
Monitors order lifecycle status from order receipt through shipment and delivery.

These tools demonstrate how operational data can be used to support real-time decision making and performance monitoring within wholesale and supply chain environments.

# Operations Performance Dashboard

This dashboard provides operational leadership with real-time visibility into wholesale operational performance.

---

## KPI Overview

| KPI | Current Value | Target | Status |
|----|----|----|----|
| Order Accuracy Rate | 98.6% | 98% | On Track |
| On-Time Shipment Rate | 96.1% | 95% | On Track |
| Fill Rate | 95.8% | 95% | On Track |
| Routing Compliance Rate | 97.4% | 96% | On Track |
| Invoice Accuracy Rate | 99.1% | 98% | On Track |
| Chargeback Rate | 1.2% | <2% | On Track |

---

## Order Activity

| Date | Orders Received | Orders Processed | Orders Shipped | Orders On Hold |
|----|----|----|----|----|
| Jan 1 | 85 | 80 | 78 | 5 |
| Jan 2 | 92 | 88 | 84 | 4 |
| Jan 3 | 75 | 72 | 70 | 3 |

---

## Fulfillment Performance

| Warehouse | Orders Fulfilled | On-Time Shipments | Delayed Shipments |
|----|----|----|----|
| Distribution Center 1 | 450 | 430 | 20 |
| Distribution Center 2 | 390 | 372 | 18 |
| 3PL West | 210 | 198 | 12 |

---

This dashboard helps leadership monitor operational efficiency and identify performance issues quickly.

# Inventory Tracking Model

This model provides visibility into inventory availability, allocation, and reorder planning across warehouse locations.

---

## Inventory Overview

| SKU | Product Name | Warehouse | Available Inventory | Reserved Inventory | Available to Sell | Reorder Point |
|----|----|----|----|----|----|----|
| SKU-1001 | Classic Watch | DC1 | 1200 | 350 | 850 | 500 |
| SKU-1002 | Sport Watch | DC1 | 900 | 400 | 500 | 300 |
| SKU-1003 | Leather Strap | DC2 | 2200 | 500 | 1700 | 800 |
| SKU-1004 | Metal Bracelet | DC2 | 600 | 200 | 400 | 250 |

---

## Inventory Monitoring Metrics

| Metric | Description |
|------|------|
| Available Inventory | Total inventory physically in stock |
| Reserved Inventory | Inventory allocated to existing orders |
| Available to Sell | Inventory available for new orders |
| Reorder Point | Inventory level that triggers replenishment |

---

Inventory tracking ensures that wholesale orders can be fulfilled without stockouts while maintaining efficient inventory levels.

# Order Status Report

The order status report provides real-time visibility into the lifecycle of wholesale orders from receipt through delivery.

---

## Order Tracking

| Order ID | Customer | Order Date | Status | Warehouse | Shipment Date | Tracking Number |
|----|----|----|----|----|----|----|
| ORD-1001 | Retailer A | Jan 3 | Processing | DC1 | Pending | - |
| ORD-1002 | Retailer B | Jan 3 | Shipped | DC2 | Jan 4 | TRK234823 |
| ORD-1003 | Retailer C | Jan 4 | On Hold | DC1 | - | - |
| ORD-1004 | Retailer D | Jan 5 | Fulfillment | 3PL West | Pending | - |
| ORD-1005 | Retailer E | Jan 5 | Delivered | DC1 | Jan 6 | TRK875234 |

---

## Order Status Definitions

| Status | Description |
|------|------|
| Received | Purchase order received |
| Processing | Order being validated and processed |
| Allocated | Inventory reserved for the order |
| Fulfillment | Warehouse picking and packing |
| Shipped | Shipment dispatched |
| Delivered | Shipment received by partner |
| On Hold | Order paused due to validation or inventory issue |

---

Order status tracking enables operations teams to monitor order progress and quickly resolve operational exceptions.
