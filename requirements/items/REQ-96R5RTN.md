---
id: REQ-96R5RTN
type: interface-requirement
title: Main PCB notifys error conditions
status: Approved
priority: High
owner: L. Samir
former-id: IF-NHYR20
parent: REQ-SXVZTB3
order: a3
links:
  - type: refines
    target: REQ-SXVZTB3
    confirmed: 60a80a1c9e4e
---
The power supply shall switch error conditions when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
