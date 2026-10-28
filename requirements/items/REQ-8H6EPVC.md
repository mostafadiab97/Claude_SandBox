---
id: TC-Z344D4
type: test-case
title: "Verify: Notification service restores safety limits"
status: Draft
priority: High
tags:
  - i18n
  - EMC
  - release-1.0
parent: INFO-J0FETE
order: 880
links:
  - type: verifies
    target: SYS-0R8DVR
    confirmed: 008c7842cee7
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
