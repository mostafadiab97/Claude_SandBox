---
id: TC-R63RRN
type: test-case
title: "Verify: Mobile app displays energy consumption"
status: Approved
owner: N. Kamal
parent: INFO-J0FETE
order: 1350
links:
  - type: verifies
    target: SYS-91G81P
  - type: verifies
    target: SW-89WYP8
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
