---
id: TC-E3JMGS
type: test-case
title: "Verify: Wi-Fi module logs error conditions"
status: Draft
priority: Medium
owner: M. Farouk
parent: INFO-F0M7VC
order: 1330
links:
  - type: verifies
    target: SYS-A3STJH
    confirmed: 01e4f44d3a9c
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Limit firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
