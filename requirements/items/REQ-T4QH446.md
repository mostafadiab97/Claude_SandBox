---
id: TC-9X3GV7
type: test-case
title: "Regression: Zone valve notifys the connection state"
status: Review
priority: Medium
owner: S. Adel
tags:
  - accessibility
parent: INFO-ECHASH
order: 1700
links:
  - type: verifies
    target: SYS-2GY8ED
    confirmed: af1bc2a80b1d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
