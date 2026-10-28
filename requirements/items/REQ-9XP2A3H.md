---
id: TC-1BN6ZZ
type: test-case
title: "Regression: Pairing process validates audit records"
status: Approved
priority: Medium
tags:
  - i18n
parent: INFO-ECHASH
order: 1290
links:
  - type: verifies
    target: SYS-DVDRV2
    confirmed: 1dc89c6de993
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
