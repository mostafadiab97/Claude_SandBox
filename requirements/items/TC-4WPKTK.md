---
id: TC-4WPKTK
type: test-case
title: "Verify: Bluetooth LE link synchronises energy consumption"
status: Approved
priority: High
owner: J. Müller
tags:
  - cost
  - release-1.0
parent: INFO-F0M7VC
order: 1110
links:
  - type: verifies
    target: SYS-2DYZPV
    confirmed: 37aac0e40a8d
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
