---
id: REQ-0YPJXBH
type: test-case
title: "Verify: Menu system switchs safety limits"
status: Review
priority: Low
former-id: TC-5NVFZ2
parent: REQ-Y9VHHKA
order: b0o
links:
  - type: verifies
    target: REQ-0ACXJ6N
    confirmed: dde92a3c92b3
  - type: verifies
    target: REQ-G61EFQM
    confirmed: 7e07c68a1de6
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
