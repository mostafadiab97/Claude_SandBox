---
id: TC-RCNMFM
type: test-case
title: "Verify: Bluetooth LE link switchs safety limits"
status: Draft
priority: High
owner: M. Farouk
tags:
  - performance
  - power
parent: INFO-F0M7VC
order: 1280
links:
  - type: verifies
    target: SYS-3PY964
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
