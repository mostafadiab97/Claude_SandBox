---
id: TC-Y0QTD7
type: test-case
title: "Verify: Mobile app switchs the connection state"
status: Draft
owner: É. Laurent
parent: INFO-J0FETE
order: 180
links:
  - type: verifies
    target: SYS-EQ4ME8
  - type: verifies
    target: SW-2C9HYA
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
