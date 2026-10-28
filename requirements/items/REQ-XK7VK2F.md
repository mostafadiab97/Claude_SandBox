---
id: REQ-XK7VK2F
type: test-case
title: "Verify: Notification service validates the room temperature"
status: Approved
priority: High
owner: S. Adel
tags:
  - performance
former-id: TC-YB2WYW
parent: REQ-WR5ZJN9
order: b0n
links:
  - type: verifies
    target: REQ-NE4H9GZ
    confirmed: 494337b838a6
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
