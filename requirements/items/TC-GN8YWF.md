---
id: TC-GN8YWF
type: test-case
title: "Regression: Wi-Fi module limits the set point"
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - safety
parent: INFO-ECHASH
order: 700
links:
  - type: verifies
    target: SYS-0W57FW
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
