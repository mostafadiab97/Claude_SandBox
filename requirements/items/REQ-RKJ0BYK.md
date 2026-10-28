---
id: REQ-RKJ0BYK
type: test-case
title: "Regression: Secure boot logs the operating mode"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - security
  - safety
former-id: TC-H85RGH
parent: REQ-6H15AV2
order: b15
links:
  - type: verifies
    target: REQ-8565GVW
    confirmed: 372b9844dfa7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
