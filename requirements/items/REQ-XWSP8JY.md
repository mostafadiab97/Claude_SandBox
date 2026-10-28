---
id: TC-RYGD11
type: test-case
title: "Regression: Local API displays schedule entries"
status: Approved
priority: Medium
owner: R. Nabil
parent: INFO-ECHASH
order: 540
links:
  - type: verifies
    target: SYS-FA8CFD
    confirmed: 7868d91ae4aa
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
