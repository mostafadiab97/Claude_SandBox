---
id: TC-TFC6JE
type: test-case
title: "Verify: Device registry encrypts the set point"
status: Review
priority: High
owner: R. Nabil
parent: INFO-7P4D8D
order: 610
links:
  - type: verifies
    target: SYS-7FWKHS
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
