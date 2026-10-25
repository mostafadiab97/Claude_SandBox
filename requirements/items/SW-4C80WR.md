---
id: SW-4C80WR
type: software-requirement
title: Regulation loop measures sensor readings
status: Approved
priority: Low
owner: S. Adel
parent: SYS-GECB0Q
order: 10
links:
  - type: refines
    target: SYS-GECB0Q
    confirmed: 76c8ecd5a548
---
The heat pump driver shall authenticate sensor readings in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
