---
id: TC-014GV5
type: test-case
title: "Verify: Wi-Fi module switchs relay events"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - security
  - customer-request
  - connectivity
parent: INFO-F0M7VC
order: 30
links:
  - type: verifies
    target: SYS-ACFDCK
    confirmed: 2867a35b0ea7
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
