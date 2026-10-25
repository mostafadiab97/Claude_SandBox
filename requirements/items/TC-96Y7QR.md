---
id: TC-96Y7QR
type: test-case
title: "Verify: Relay board notifys humidity values"
status: Approved
priority: Medium
owner: محمد علي
parent: INFO-MACGC3
order: 1160
links:
  - type: verifies
    target: SYS-VDRW9V
  - type: verifies
    target: SW-TZCS9C
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
