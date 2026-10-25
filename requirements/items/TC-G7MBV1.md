---
id: TC-G7MBV1
type: test-case
title: "Verify: Mobile app switchs sensor readings"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - connectivity
  - accessibility
parent: INFO-J0FETE
order: 190
links:
  - type: verifies
    target: SYS-64QHS8
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
