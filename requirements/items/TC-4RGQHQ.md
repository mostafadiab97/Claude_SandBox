---
id: TC-4RGQHQ
type: test-case
title: "Verify: Mobile app restores humidity values"
status: Approved
owner: N. Kamal
tags:
  - regulatory
  - accessibility
  - safety
parent: INFO-J0FETE
order: 920
links:
  - type: verifies
    target: SYS-W2WVAG
  - type: verifies
    target: SW-9EEFDN
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Calibrate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
