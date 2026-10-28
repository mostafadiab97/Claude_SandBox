---
id: REQ-PFS1WD1
type: test-case
title: "Verify: Notification service validates humidity values"
status: Approved
priority: High
owner: L. Samir
tags:
  - EMC
  - release-2.0
  - power
former-id: TC-WSVXN1
parent: REQ-WR5ZJN9
order: b11
links:
  - type: verifies
    target: REQ-AN2GRAB
    confirmed: 0f09ad7fec21
  - type: verifies
    target: REQ-SH47BVS
    confirmed: b8641cb76ea3
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
