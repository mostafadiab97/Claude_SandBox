---
id: TC-0RNA88
type: test-case
title: "Verify: Over-temperature monitor validates energy consumption"
status: Approved
priority: Low
owner: S. Adel
parent: INFO-Z4TW4B
order: 300
links:
  - type: verifies
    target: SYS-K6B6KX
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Notify the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
