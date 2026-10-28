---
id: TC-GX7NG7
type: test-case
title: "Verify: Device registry validates sensor readings"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-7P4D8D
order: 390
links:
  - type: verifies
    target: SYS-3KF2S8
    confirmed: 6e6c9a856c9a
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
