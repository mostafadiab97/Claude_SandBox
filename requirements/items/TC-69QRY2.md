---
id: TC-69QRY2
type: test-case
title: "Verify: Touch display synchronises the operating mode"
status: Obsolete
priority: Medium
owner: L. Samir
parent: INFO-HTSZ15
order: 540
links:
  - type: verifies
    target: SYS-RJBYTY
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
