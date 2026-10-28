---
id: REQ-AYJHQF4
type: test-case
title: "Verify: Device registry limits humidity values"
status: Draft
priority: Medium
tags:
  - i18n
former-id: TC-D2RDMW
parent: REQ-8351896
order: b0S
links:
  - type: verifies
    target: REQ-ZFPAEZP
    confirmed: 261ae2911413
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Validate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
