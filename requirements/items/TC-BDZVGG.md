---
id: TC-BDZVGG
type: test-case
title: "Verify: Local API restores user preferences"
status: Draft
priority: Medium
parent: INFO-F0M7VC
order: 130
links:
  - type: verifies
    target: SYS-MBT5B7
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Calibrate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
