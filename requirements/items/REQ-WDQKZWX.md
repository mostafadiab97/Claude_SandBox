---
id: TC-QD7CCK
type: test-case
title: "Regression: Battery backup authenticates the room temperature"
status: Review
priority: High
owner: N. Kamal
tags:
  - security
  - cost
parent: INFO-ECHASH
order: 1160
links:
  - type: verifies
    target: SYS-R6T7X1
    confirmed: 03767e5db5f8
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
