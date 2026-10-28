---
id: REQ-K0MQQGN
type: test-case
title: "Verify: Mobile app switchs the connection state"
status: Draft
owner: É. Laurent
former-id: TC-Y0QTD7
parent: REQ-WR5ZJN9
order: aH
links:
  - type: verifies
    target: REQ-J25YGJQ
    confirmed: 00f1fdeebe62
  - type: verifies
    target: REQ-JG21K63
    confirmed: 4b4be5d0d1b1
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
