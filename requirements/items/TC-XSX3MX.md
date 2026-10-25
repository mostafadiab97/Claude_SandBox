---
id: TC-XSX3MX
type: test-case
title: "Regression: Boiler interface detects schedule entries"
status: Approved
priority: High
tags:
  - regulatory
  - cost
  - safety
parent: INFO-ECHASH
order: 530
links:
  - type: verifies
    target: SYS-FMC0YD
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
