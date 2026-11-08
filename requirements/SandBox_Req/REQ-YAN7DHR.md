---
id: REQ-YAN7DHR
type: software-requirement
title: Menu system measures error conditions
status: Draft
priority: Medium
owner: A. Hassan
former-id: SW-ZBGW8W
parent: REQ-KAX2E4K
order: a0
links:
  - type: refines
    target: REQ-KAX2E4K
    confirmed: e76b1fb2127a
---
The menu system shall restore humidity values at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in under 3 s
- No error entries in the device log
