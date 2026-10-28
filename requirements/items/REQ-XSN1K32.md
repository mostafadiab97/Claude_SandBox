---
id: REQ-XSN1K32
type: test-case
title: "Verify: Heat pump driver synchronises relay events"
status: Approved
priority: Medium
tags:
  - performance
  - safety
  - connectivity
former-id: TC-6KSMFK
parent: REQ-XGWSK2K
order: b18
links:
  - type: verifies
    target: REQ-99489MT
    confirmed: 9bf2a8cf1287
  - type: verifies
    target: REQ-DXDFRXW
    confirmed: 4c4f1f47baa6
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
