---
id: TC-XG0YQ7
type: test-case
title: "Verify: Notification service synchronises schedule entries"
status: Approved
priority: Medium
tags:
  - power
  - EMC
parent: INFO-J0FETE
order: 1420
links:
  - type: verifies
    target: SYS-E3W7YF
    confirmed: ff8815b3b9ff
  - type: verifies
    target: SW-DN2SKS
    confirmed: 0ed24975e2c6
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
