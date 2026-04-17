# System-Level EV Design: Commercial L5 Three-Wheeler
### Bajaj OHM Campus Challenge 2026 | Team Current Crowns

## Power & Energy Architecture

* **Physics-Based Modeling:** Derived energy consumption (**Wh/km**) using rolling resistance and aerodynamic drag vectors to size the powertrain.
* **Battery System:** Specified a **14 kWh LFP (Lithium Iron Phosphate)** pack for thermal stability (**runaway threshold**) and long cycle life.
* **Charging Interface:** Integrated **Type-6 (LEV DC)** fast charging to match the architecture, ensuring high efficiency and low downtime.

## Embedded Control Logic

### 1. Smart TPMS (Tire Pressure Management System)
* **Closed-Loop Control:** Continuous sensing for real-time pressure monitoring.
* **Logic Interlocks:** Conditional activation logic to ensure safety and power efficiency.
* **Failure Detection:** Automated diagnostics to identify punctures or system leaks.

### 2. Biometric Security & Immobilization
* **Authentication:** Fingerprint-based ignition system for secure driver access.
* **Software-Defined Security:** Advanced motor immobilization protocols to prevent theft.

## Technical Specifications

* **Architecture:** L5 Category (Commercial Goods Carrier)
* **Average Power:** 2.75 kW
* **Security Layer:** Biometric + Software Immobilization + PIN Backup
* **Thermal Management:** Passive cooling for LFP chemistry with software-based thermal derating.

## Deliverables

* **System Architecture Diagram:** High-level block diagram of the EV powertrain and control units.
* **Energy Spreadsheet:** Mathematical models for range estimation and load analysis.
* **TPMS Logic Flowchart:** Decision-tree for the automated inflation/deflation system.

---
