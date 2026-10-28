---
id: REQ-HWNB73Y
type: test-case
title: "Verify: Notification service authenticates humidity values"
status: Approved
priority: High
owner: Y. Saber
tags:
  - cost
former-id: TC-Z36G08
parent: REQ-WR5ZJN9
order: b0A
links:
  - type: verifies
    target: REQ-EY967YJ
    confirmed: 856e0842d1dd
  - type: verifies
    target: REQ-HAEYHZ6
    confirmed: 7aeb62dc4210
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
