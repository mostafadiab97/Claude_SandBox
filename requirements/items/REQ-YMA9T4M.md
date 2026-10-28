---
id: TC-SDBN3F
type: test-case
title: "Regression: Mobile app encrypts relay events"
status: Approved
priority: High
owner: S. Adel
tags:
  - ux
parent: INFO-ECHASH
order: 1000
links:
  - type: verifies
    target: SYS-FBM4B7
    confirmed: 17a1840f1286
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
