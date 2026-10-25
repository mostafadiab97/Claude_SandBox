---
id: TC-CWNBX8
type: test-case
title: "Verify: Notification service calibrates the set point"
status: Review
priority: Low
owner: A. Hassan
tags:
  - accessibility
parent: INFO-J0FETE
order: 1060
links:
  - type: verifies
    target: SYS-TETJ5F
  - type: verifies
    target: SW-H2FV48
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
