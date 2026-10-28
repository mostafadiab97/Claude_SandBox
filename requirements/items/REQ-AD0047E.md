---
id: REQ-AD0047E
type: test-case
title: "Regression: Watchdog reports energy consumption"
status: Approved
priority: High
owner: L. Samir
tags:
  - security
  - accessibility
  - release-1.0
former-id: TC-ADG5QC
parent: REQ-6H15AV2
order: b1N
links:
  - type: verifies
    target: REQ-33MFB68
    confirmed: 81a097bb4f90
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
