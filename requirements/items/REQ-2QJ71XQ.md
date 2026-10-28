---
id: TC-1K3BET
type: test-case
title: "Verify: Notification service detects access tokens"
status: Draft
priority: High
owner: S. Adel
parent: INFO-J0FETE
order: 10
links:
  - type: verifies
    target: SYS-AQ211W
    confirmed: 17e9d0952657
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Report the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
