---
id: REQ-TKRT5QP
type: test-case
title: "Verify: Main PCB stores sensor readings"
status: Approved
owner: É. Laurent
tags:
  - security
  - safety
  - release-1.0
former-id: TC-RYCZFZ
parent: REQ-F9Z1FYS
order: b0P
links:
  - type: verifies
    target: REQ-4CBY78D
    confirmed: c00f25df31a0
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
