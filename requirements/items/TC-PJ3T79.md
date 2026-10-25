---
id: TC-PJ3T79
type: test-case
title: "Verify: Status LED reports the operating mode"
status: Draft
priority: Low
owner: M. Farouk
tags:
  - release-2.0
  - power
parent: INFO-HTSZ15
order: 1020
links:
  - type: verifies
    target: SYS-J7BTY7
  - type: verifies
    target: SW-VTZYV6
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
