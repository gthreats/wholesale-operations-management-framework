# Wholesale System Architecture

This simplified architecture shows how wholesale orders move through operational systems.

```mermaid
flowchart TD
A[Retail Partner] --> B[EDI Platform]
B --> C[ERP System]
C --> D[Warehouse]
D --> E[Shipping]
E --> F[Delivery]
```
