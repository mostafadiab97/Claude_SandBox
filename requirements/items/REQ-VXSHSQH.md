---
id: TC-3MGJRB
type: test-case
title: "Regression: Login screen limits the connection state"
status: Approved
priority: Low
owner: M. Farouk
tags:
  - ux
  - i18n
  - regulatory
parent: INFO-ECHASH
order: 1130
links:
  - type: verifies
    target: SYS-ZW9PC7
    confirmed: cf666200a270
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
