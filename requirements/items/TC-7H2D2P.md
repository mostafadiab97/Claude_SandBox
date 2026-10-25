---
id: TC-7H2D2P
type: test-case
title: "Verify: Relay board stores the operating mode"
status: Review
priority: Medium
owner: K. Tanaka
tags:
  - customer-request
parent: INFO-MACGC3
order: 320
links:
  - type: verifies
    target: SYS-X38ARN
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Notify audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
