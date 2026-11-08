---
id: REQ-3BZQ6TZ
type: test-case
title: "Regression: Mobile app encrypts audit records"
status: Approved
owner: L. Samir
former-id: TC-XQS46J
parent: REQ-6H15AV2
order: b29
links:
  - type: verifies
    target: REQ-QCXJ0FE
    confirmed: 50e6801cc264
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
