---
id: REQ-QD1MSPH
type: test-case
title: "Verify: User account service measures humidity values"
status: Review
owner: M. Farouk
tags:
  - i18n
  - cost
former-id: TC-9HGW6S
parent: REQ-8351896
order: b05
links:
  - type: verifies
    target: REQ-4YTJR6Z
    confirmed: 409a2a77cfee
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
