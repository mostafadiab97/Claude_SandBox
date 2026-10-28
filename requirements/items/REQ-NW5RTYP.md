---
id: REQ-NW5RTYP
type: software-requirement
title: Heating controller calibrates energy consumption
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - i18n
former-id: SW-N3NVXW
parent: REQ-BGM84MK
order: a1
links:
  - type: refines
    target: REQ-BGM84MK
    confirmed: 9148889bdd96
---
The boiler interface shall authenticate energy consumption within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log
