---
id: REQ-AG0ES4B
type: test-case
title: "Verify: Login screen limits firmware images"
status: Approved
priority: Medium
tags:
  - regulatory
  - i18n
former-id: TC-YBFQAG
parent: REQ-WR5ZJN9
order: b0V
links:
  - type: verifies
    target: REQ-53SHBXS
    confirmed: e0be285eec93
  - type: verifies
    target: REQ-R5YSJVW
    confirmed: 54253c7ea624
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
