---
id: TC-0ZP3XC
type: test-case
title: "Regression: User account service stores the operating mode"
status: Draft
priority: High
owner: محمد علي
parent: INFO-ECHASH
order: 750
links:
  - type: verifies
    target: SYS-0QZ4FS
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
