---
id: TC-ZATYCT
type: test-case
title: "Verify: Notification service notifys the set point"
status: Draft
priority: Low
owner: L. Samir
tags:
  - safety
  - customer-request
parent: INFO-J0FETE
order: 1280
links:
  - type: verifies
    target: SYS-MRHZSS
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Measure schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
