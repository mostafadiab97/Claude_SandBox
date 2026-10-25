---
id: TC-H85RGH
type: test-case
title: "Regression: Secure boot logs the operating mode"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - security
  - safety
parent: INFO-ECHASH
order: 1300
links:
  - type: verifies
    target: SYS-NQ8RXH
    confirmed: 372b9844dfa7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
