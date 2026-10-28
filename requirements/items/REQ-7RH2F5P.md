---
id: TC-6PRK32
type: test-case
title: "Verify: Notification service logs the operating mode"
status: Approved
owner: J. Müller
parent: INFO-J0FETE
order: 1150
links:
  - type: verifies
    target: SYS-NE90V9
    confirmed: d34ffbeb0cc6
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
