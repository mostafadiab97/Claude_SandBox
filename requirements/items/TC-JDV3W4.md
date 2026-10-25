---
id: TC-JDV3W4
type: test-case
title: "Verify: Touch display stores the connection state"
status: Review
priority: High
parent: INFO-HTSZ15
order: 440
links:
  - type: verifies
    target: SYS-A8QJ0D
  - type: verifies
    target: SW-VHWR9A
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Measure the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
