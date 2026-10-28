---
id: REQ-AR75A1G
type: system-requirement
title: Secure boot synchronises the connection state
status: Approved
priority: High
owner: N. Kamal
tags:
  - release-2.0
  - i18n
  - ux
former-id: SYS-FDJDP9
parent: REQ-H9113WA
order: b0U
links:
  - type: refines
    target: REQ-AVJ6PR8
    confirmed: fc1f05b44684
---
The secure boot shall display sensor readings within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly with an accuracy of ±0.5 °C
- No error entries in the device log
