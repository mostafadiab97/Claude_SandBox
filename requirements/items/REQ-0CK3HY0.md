---
id: REQ-0CK3HY0
type: test-case
title: "Regression: Wi-Fi module switchs schedule entries"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - power
  - cost
former-id: TC-APVT14
parent: REQ-6H15AV2
order: b0W
links:
  - type: verifies
    target: REQ-1H9ZVHN
    confirmed: de7334e55ef0
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
