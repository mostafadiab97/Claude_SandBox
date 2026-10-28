---
id: REQ-3JACY8K
type: test-case
title: "Verify: Mobile app encrypts relay events"
status: Approved
priority: High
owner: L. Samir
tags:
  - ux
former-id: TC-8JDQ6P
parent: REQ-WR5ZJN9
order: b09
links:
  - type: verifies
    target: REQ-0BCC2Y7
    confirmed: c2dee4a6831a
  - type: verifies
    target: REQ-T15RRBN
    confirmed: 3d295cfeb105
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Limit the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
