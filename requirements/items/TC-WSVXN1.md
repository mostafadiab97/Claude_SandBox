---
id: TC-WSVXN1
type: test-case
title: "Verify: Notification service validates humidity values"
status: Approved
priority: High
owner: L. Samir
tags:
  - EMC
  - release-2.0
  - power
parent: INFO-J0FETE
order: 1260
links:
  - type: verifies
    target: SYS-ZK10Z4
  - type: verifies
    target: SW-414298
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
