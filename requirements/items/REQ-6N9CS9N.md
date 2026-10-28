---
id: REQ-6N9CS9N
type: software-requirement
title: Regulation loop switchs safety limits
status: Draft
priority: Medium
owner: J. Müller
former-id: SW-2EK2H0
parent: REQ-JVX09VR
order: a0
links:
  - type: refines
    target: REQ-JVX09VR
    confirmed: 4edc21a3fb0f
---
The heat pump driver shall validate humidity values for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly after a power loss
- No error entries in the device log
