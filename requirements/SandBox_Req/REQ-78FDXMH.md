---
id: REQ-78FDXMH
type: test-case
title: "Regression: Menu system reports firmware images"
status: Approved
priority: High
owner: H. Mostafa
tags:
  - regulatory
former-id: TC-85NJEW
parent: REQ-6H15AV2
order: b28
links:
  - type: verifies
    target: REQ-ED37SCP
    confirmed: 9aafb86ae7fb
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
