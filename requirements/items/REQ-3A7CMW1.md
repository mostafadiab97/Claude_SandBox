---
id: REQ-3A7CMW1
type: test-case
title: "Verify: Cloud backend detects the room temperature"
status: Approved
priority: High
owner: K. Tanaka
former-id: TC-NRKTZ4
parent: REQ-8351896
order: aN
links:
  - type: verifies
    target: REQ-XA0H1EA
    confirmed: 0e79beed01a7
  - type: verifies
    target: REQ-VR0XBC8
    confirmed: 367a6b674b14
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
