---
id: TC-4ERA8B
type: test-case
title: "Verify: Mobile app encrypts the set point"
status: Draft
priority: High
owner: A. Hassan
parent: INFO-J0FETE
order: 1450
links:
  - type: verifies
    target: SYS-Z9T7JH
  - type: verifies
    target: SW-YH3CS4
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
