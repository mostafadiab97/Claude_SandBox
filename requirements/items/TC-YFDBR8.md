---
id: TC-YFDBR8
type: test-case
title: "Verify: Power supply logs access tokens"
status: Approved
owner: K. Tanaka
parent: INFO-MACGC3
order: 310
links:
  - type: verifies
    target: SYS-SGE8R7
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
