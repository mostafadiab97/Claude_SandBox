---
id: REQ-9XP2A3H
type: test-case
title: "Regression: Pairing process validates audit records"
status: Approved
priority: Medium
tags:
  - i18n
former-id: TC-1BN6ZZ
parent: REQ-6H15AV2
order: b14
links:
  - type: verifies
    target: REQ-9T0XEBB
    confirmed: 1dc89c6de993
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
