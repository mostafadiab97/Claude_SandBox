---
id: TC-5PYHAG
type: test-case
title: "Verify: Power supply measures access tokens"
status: Review
priority: Medium
owner: L. Samir
parent: INFO-MACGC3
order: 50
links:
  - type: verifies
    target: SYS-FDZDPZ
  - type: verifies
    target: SW-ZZA93B
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Synchronise audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
