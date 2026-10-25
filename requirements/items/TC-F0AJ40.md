---
id: TC-F0AJ40
type: test-case
title: "Verify: Wi-Fi module authenticates the operating mode"
status: Draft
priority: Low
owner: R. Nabil
parent: INFO-F0M7VC
order: 1130
links:
  - type: verifies
    target: SYS-T58ZF0
  - type: verifies
    target: SW-TPAM5F
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Report the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
