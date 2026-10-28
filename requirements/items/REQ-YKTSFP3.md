---
id: TC-E1XCQ1
type: test-case
title: "Verify: OTA server notifys the operating mode"
status: Draft
priority: Medium
owner: Y. Saber
parent: INFO-7P4D8D
order: 530
links:
  - type: verifies
    target: SYS-J2BCRS
    confirmed: dbe3e7f88972
  - type: verifies
    target: SW-5H3R25
    confirmed: d0a887012e16
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
