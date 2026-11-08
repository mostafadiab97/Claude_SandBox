---
id: REQ-J36G46J
type: interface-requirement
title: Bluetooth LE link calibrates energy consumption
status: Obsolete
priority: Medium
owner: R. Nabil
tags:
  - customer-request
  - ux
  - release-2.0
former-id: IF-HSPZKH
parent: REQ-A2XPEJG
order: a2
links:
  - type: refines
    target: REQ-A2XPEJG
    confirmed: 306846e9f601
---
The Wi-Fi module shall store energy consumption within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log
