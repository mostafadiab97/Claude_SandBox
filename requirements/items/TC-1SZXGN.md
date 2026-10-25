---
id: TC-1SZXGN
type: test-case
title: "Verify: Secure boot restores safety limits"
status: Approved
priority: High
owner: M. Farouk
parent: INFO-Z4TW4B
order: 570
links:
  - type: verifies
    target: SYS-VR1QT6
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Restore firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
