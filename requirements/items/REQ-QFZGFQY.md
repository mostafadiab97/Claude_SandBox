---
id: TC-ZPAYSJ
type: test-case
title: "Verify: Mobile app synchronises firmware images"
status: Approved
priority: High
owner: R. Nabil
parent: INFO-J0FETE
order: 990
links:
  - type: verifies
    target: SYS-1XCVNB
    confirmed: 54d963c03420
  - type: verifies
    target: SW-KZQTY6
    confirmed: 2d0abae3753b
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
