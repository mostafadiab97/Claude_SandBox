---
id: TC-370KDA
type: test-case
title: "Verify: Notification service encrypts error conditions"
status: Draft
priority: Medium
owner: S. Adel
tags:
  - regulatory
  - ux
parent: INFO-J0FETE
order: 300
links:
  - type: verifies
    target: SYS-T44M5X
    confirmed: b93a511f8f0f
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
