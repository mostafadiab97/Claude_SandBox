---
id: REQ-9ZP558D
type: test-case
title: "Regression: Wi-Fi module limits the set point"
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - safety
former-id: TC-GN8YWF
parent: REQ-6H15AV2
order: b07
links:
  - type: verifies
    target: REQ-Q7W6CHZ
    confirmed: e1266f4ab489
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
