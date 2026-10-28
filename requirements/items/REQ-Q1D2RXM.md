---
id: REQ-Q1D2RXM
type: test-case
title: "Regression: User account service synchronises audit records"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - performance
  - regulatory
former-id: TC-WJT2Q1
parent: REQ-6H15AV2
order: b1l
links:
  - type: verifies
    target: REQ-SBES3DX
    confirmed: 0ff5a626958c
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
