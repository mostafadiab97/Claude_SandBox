---
id: TC-HNFBNV
type: test-case
title: "Regression: Relay board stores the operating mode"
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - i18n
  - ux
  - accessibility
parent: INFO-ECHASH
order: 1350
links:
  - type: verifies
    target: SYS-X38ARN
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
