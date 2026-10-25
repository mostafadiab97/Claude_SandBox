---
id: TC-G2Y6Q1
type: test-case
title: "Verify: Mobile app reports safety limits"
status: Approved
priority: Low
owner: R. Nabil
parent: INFO-J0FETE
order: 1380
links:
  - type: verifies
    target: SYS-367JHA
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
