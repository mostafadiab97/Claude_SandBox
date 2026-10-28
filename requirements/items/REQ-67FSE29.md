---
id: TC-16STGH
type: test-case
title: "Verify: Device registry detects sensor readings"
status: Approved
priority: Medium
parent: INFO-7P4D8D
order: 820
links:
  - type: verifies
    target: SYS-K8QB7W
    confirmed: b56f90ef8f2c
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
