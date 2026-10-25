---
id: TC-NMQAQ7
type: test-case
title: "Verify: Mobile app notifys audit records"
status: Approved
owner: Y. Saber
parent: INFO-J0FETE
order: 1230
links:
  - type: verifies
    target: SYS-78N6Z3
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
