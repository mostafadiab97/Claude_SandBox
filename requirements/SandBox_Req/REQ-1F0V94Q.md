---
id: REQ-1F0V94Q
type: test-case
title: "Verify: Schedule editor logs the connection state"
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - ux
former-id: TC-Z1YDR4
parent: REQ-WR5ZJN9
order: av
links:
  - type: verifies
    target: REQ-1MFX129
    confirmed: 1344b9a930e1
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Limit the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
