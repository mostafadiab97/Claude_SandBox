---
id: REQ-4MR61V0
type: test-case
title: "Verify: Notification service switchs the connection state"
status: Approved
owner: Y. Saber
tags:
  - power
former-id: TC-KZ61AT
parent: REQ-WR5ZJN9
order: aq
links:
  - type: verifies
    target: REQ-D5YEACT
    confirmed: c2e09763d836
  - type: verifies
    target: REQ-EFTGX4R
    confirmed: 3e6e63c540b2
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
