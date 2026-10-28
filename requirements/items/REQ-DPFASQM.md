---
id: REQ-DPFASQM
type: test-case
title: "Verify: Main PCB validates the set point"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - customer-request
former-id: TC-Q38D71
parent: REQ-F9Z1FYS
order: b0c
links:
  - type: verifies
    target: REQ-DV0E664
    confirmed: 248750d69b90
  - type: verifies
    target: REQ-RYXAYBT
    confirmed: 65a51bcffb34
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
