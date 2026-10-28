---
id: TC-Z2AY6N
type: test-case
title: "Regression: Power supply stores energy consumption"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - ux
  - accessibility
parent: INFO-ECHASH
order: 1930
links:
  - type: verifies
    target: SYS-BFB7EF
    confirmed: a7ba030d51de
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
