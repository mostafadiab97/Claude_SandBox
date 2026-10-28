---
id: REQ-73KYA0N
type: test-case
title: "Verify: Main PCB limits the set point"
status: Draft
priority: Medium
tags:
  - i18n
former-id: TC-4Q8PSE
parent: REQ-F9Z1FYS
order: af
links:
  - type: verifies
    target: REQ-KP43F6H
    confirmed: 98030a3341f7
  - type: verifies
    target: REQ-CN8JGGR
    confirmed: 71a1736b67f4
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
