---
id: REQ-JM66AX5
type: software-requirement
title: Login screen authenticates relay events
status: Review
priority: High
tags:
  - i18n
former-id: SW-D8ZPBJ
parent: REQ-AKDTNC9
order: a0
links:
  - type: refines
    target: REQ-AKDTNC9
    confirmed: f4fac07cb110
---
The login screen shall notify the room temperature within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly in under 3 s
- No error entries in the device log
