---
id: TC-FQNGHY
type: test-case
title: "Regression: Heat pump driver synchronises relay events"
status: Draft
priority: High
owner: K. Tanaka
parent: INFO-ECHASH
order: 1660
links:
  - type: verifies
    target: SYS-R95DE9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
