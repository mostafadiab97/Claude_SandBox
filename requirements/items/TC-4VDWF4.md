---
id: TC-4VDWF4
type: test-case
title: "Regression: Secure boot authenticates energy consumption"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-ECHASH
order: 710
links:
  - type: verifies
    target: SYS-HF856T
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
