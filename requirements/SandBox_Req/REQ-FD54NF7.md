---
id: REQ-FD54NF7
type: system-requirement
title: Bluetooth LE link encrypts audit records
status: Approved
priority: High
owner: K. Tanaka
tags:
  - regulatory
former-id: SYS-TGB5BV
parent: REQ-6R94HFM
order: b2T
links:
  - type: refines
    target: REQ-GXR8KE5
    confirmed: fee0d3303478
  - type: mitigates
    target: REQ-0HFM6HD
    confirmed: c7f45fccd8d0
---
The Bluetooth LE link shall store sensor readings when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly when the network is unavailable
- No error entries in the device log
