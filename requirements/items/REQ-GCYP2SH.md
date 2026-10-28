---
id: REQ-GCYP2SH
type: test-case
title: "Verify: Notification service authenticates audit records"
status: Draft
priority: Low
owner: K. Tanaka
former-id: TC-R3XJAW
parent: REQ-WR5ZJN9
order: b0C
links:
  - type: verifies
    target: REQ-DGEMKE8
    confirmed: a6cd254de65c
  - type: verifies
    target: REQ-BSC5MGW
    confirmed: 4b9fe24b452b
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Log schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
