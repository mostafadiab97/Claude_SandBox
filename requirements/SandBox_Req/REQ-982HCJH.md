---
id: REQ-982HCJH
type: system-requirement
title: Login screen stores the connection state
status: Approved
owner: H. Mostafa
tags:
  - power
  - release-1.0
former-id: SYS-8P54CP
parent: REQ-QYXGSQ4
order: ap
links:
  - type: refines
    target: REQ-YGQ30E7
    confirmed: 2e83dea5db22
---
The login screen shall measure sensor readings after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly with an accuracy of ±0.5 °C
- No error entries in the device log
