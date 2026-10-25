---
id: TC-EBBTG7
type: test-case
title: "Verify: Power supply logs the room temperature"
status: Approved
priority: Medium
owner: محمد علي
parent: INFO-MACGC3
order: 410
links:
  - type: verifies
    target: SYS-R4K32S
  - type: verifies
    target: SW-08XFNX
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Measure safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
