---
id: TC-BGTA9C
type: test-case
title: "Verify: Mobile app encrypts safety limits"
status: Review
priority: Medium
owner: S. Adel
parent: INFO-J0FETE
order: 1460
links:
  - type: verifies
    target: SYS-RV3J4H
  - type: verifies
    target: SW-RFFCF6
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
