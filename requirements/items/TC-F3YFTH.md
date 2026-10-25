---
id: TC-F3YFTH
type: test-case
title: "Verify: Notification service encrypts schedule entries"
status: Review
priority: Medium
owner: S. Adel
tags:
  - release-2.0
  - connectivity
  - i18n
parent: INFO-J0FETE
order: 1190
links:
  - type: verifies
    target: SYS-XF6HRT
    confirmed: 8fa995f67a12
  - type: verifies
    target: SW-4P595V
    confirmed: a1c29b0d37be
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Calibrate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
