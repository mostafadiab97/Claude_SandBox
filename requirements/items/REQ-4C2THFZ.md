---
id: REQ-4C2THFZ
type: test-case
title: "Regression: Local API validates the connection state"
status: Approved
priority: High
tags:
  - i18n
former-id: TC-WQ3CEY
parent: REQ-6H15AV2
order: b20
links:
  - type: verifies
    target: REQ-BNSVZ8R
    confirmed: b3432a56f6cd
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
