---
id: REQ-1R8F7FF
type: test-case
title: "Verify: Power supply stores the operating mode"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - safety
former-id: TC-YZVPTY
parent: REQ-F9Z1FYS
order: b08
links:
  - type: verifies
    target: REQ-X3TS6B3
    confirmed: 0dcc5954ae38
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
