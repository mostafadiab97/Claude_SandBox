---
id: TC-GHHSJJ
type: test-case
title: "Verify: Wi-Fi module displays sensor readings"
status: Draft
priority: High
parent: INFO-F0M7VC
order: 600
links:
  - type: verifies
    target: SYS-W81PVH
  - type: verifies
    target: SW-8RY8RE
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Calibrate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
