---
id: REQ-4ZKPSQZ
type: software-requirement
title: Login screen limits the operating mode
status: Review
priority: Medium
owner: S. Adel
former-id: SW-02H99V
parent: REQ-PN0PDWX
order: a3
links:
  - type: refines
    target: REQ-PN0PDWX
    confirmed: abb306df2814
---
The login screen shall switch safety limits when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly without user interaction
- No error entries in the device log
