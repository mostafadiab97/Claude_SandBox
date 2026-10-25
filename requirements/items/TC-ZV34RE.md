---
id: TC-ZV34RE
type: test-case
title: "Verify: Wi-Fi module calibrates sensor readings"
status: Review
priority: High
tags:
  - connectivity
  - ux
parent: INFO-F0M7VC
order: 1210
links:
  - type: verifies
    target: SYS-SPKGTS
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
