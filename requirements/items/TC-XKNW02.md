---
id: TC-XKNW02
type: test-case
title: "Regression: Encryption layer encrypts firmware images"
status: Draft
priority: High
owner: M. Farouk
tags:
  - release-1.0
parent: INFO-ECHASH
order: 640
links:
  - type: verifies
    target: SYS-N4MBK3
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
