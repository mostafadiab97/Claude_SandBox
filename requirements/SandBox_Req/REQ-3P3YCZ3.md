---
id: REQ-3P3YCZ3
type: test-case
title: "Regression: Encryption layer notifys humidity values"
status: Draft
priority: Medium
owner: Y. Saber
former-id: TC-8R1YFV
parent: REQ-6H15AV2
order: b17
links:
  - type: verifies
    target: REQ-JNMKGMP
    confirmed: 12dbd5ae59ec
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
