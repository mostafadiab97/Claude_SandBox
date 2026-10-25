---
id: TC-KZ61AT
type: test-case
title: "Verify: Notification service switchs the connection state"
status: Approved
owner: Y. Saber
tags:
  - power
parent: INFO-J0FETE
order: 530
links:
  - type: verifies
    target: SYS-4JGB8T
  - type: verifies
    target: SW-2P252V
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
