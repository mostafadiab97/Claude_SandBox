---
id: REQ-R02KX3P
type: test-case
title: "Regression: Bluetooth LE link measures sensor readings"
status: Obsolete
priority: Medium
former-id: TC-9XSRQX
parent: REQ-6H15AV2
order: b25
links:
  - type: verifies
    target: REQ-93GSKTC
    confirmed: f6e72f885951
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
