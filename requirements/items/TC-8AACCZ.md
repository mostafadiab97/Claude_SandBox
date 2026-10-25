---
id: TC-8AACCZ
type: test-case
title: "Verify: Wi-Fi module stores sensor readings"
status: Approved
priority: Medium
owner: L. Samir
parent: INFO-F0M7VC
order: 560
links:
  - type: verifies
    target: SYS-1NHXCW
  - type: verifies
    target: SW-Y2C20F
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
