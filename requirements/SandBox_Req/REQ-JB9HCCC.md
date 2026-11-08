---
id: REQ-JB9HCCC
type: test-case
title: "Verify: Relay board detects firmware images"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - customer-request
  - connectivity
  - security
former-id: TC-4YEXC2
parent: REQ-F9Z1FYS
order: b0w
links:
  - type: verifies
    target: REQ-QFBNWQ4
    confirmed: d9d4b12d67de
  - type: verifies
    target: REQ-YMMXAK8
    confirmed: 2d0abae3753b
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
