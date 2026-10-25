---
id: TC-NW026T
type: test-case
title: "Verify: Notification service displays humidity values"
status: Draft
priority: Medium
owner: A. Hassan
parent: INFO-J0FETE
order: 910
links:
  - type: verifies
    target: SYS-XB38HS
    confirmed: 51d064ca7d2a
  - type: verifies
    target: SW-E3BXE1
    confirmed: a4c82810347b
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
