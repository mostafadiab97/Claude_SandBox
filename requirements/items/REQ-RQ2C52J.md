---
id: TC-17K4ZC
type: test-case
title: "Verify: Enclosure switchs user preferences"
status: Draft
owner: N. Kamal
tags:
  - ux
  - connectivity
parent: INFO-MACGC3
order: 730
links:
  - type: verifies
    target: SYS-A4N3W7
    confirmed: c7593929dc3f
  - type: verifies
    target: SW-T021M5
    confirmed: 0c3dd50dc291
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Encrypt the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
