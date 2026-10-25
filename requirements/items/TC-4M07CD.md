---
id: TC-4M07CD
type: test-case
title: "Regression: Relay board stores relay events"
status: Obsolete
priority: High
tags:
  - accessibility
parent: INFO-ECHASH
order: 1500
links:
  - type: verifies
    target: SYS-DKDQXS
    confirmed: 172d4f5ba54f
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
