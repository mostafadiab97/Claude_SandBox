---
id: REQ-BDSNJ57
type: test-case
title: "Verify: Device registry validates the connection state"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - connectivity
former-id: TC-0BHR49
parent: REQ-8351896
order: az
links:
  - type: verifies
    target: REQ-Q9X7D3E
    confirmed: e9c956142786
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Restore relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
