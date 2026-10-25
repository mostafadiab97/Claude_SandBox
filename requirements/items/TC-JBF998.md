---
id: TC-JBF998
type: test-case
title: "Verify: Relay board stores error conditions"
status: Review
tags:
  - release-2.0
parent: INFO-MACGC3
order: 440
links:
  - type: verifies
    target: SYS-85957D
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Report audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
