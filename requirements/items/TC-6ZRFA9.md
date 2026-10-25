---
id: TC-6ZRFA9
type: test-case
title: "Verify: Bluetooth LE link authenticates audit records"
status: Approved
priority: Medium
tags:
  - security
  - connectivity
parent: INFO-F0M7VC
order: 970
links:
  - type: verifies
    target: SYS-S0ZBTB
  - type: verifies
    target: SW-6MVV07
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Notify relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
