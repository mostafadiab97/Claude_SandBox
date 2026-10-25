---
id: TC-8WDBR2
type: test-case
title: "Verify: Touch display validates schedule entries"
status: Approved
priority: Low
owner: محمد علي
tags:
  - ux
  - regulatory
parent: INFO-HTSZ15
order: 1470
links:
  - type: verifies
    target: SYS-ECD1HY
    confirmed: 7483f5483c58
  - type: verifies
    target: SW-BYVAYF
    confirmed: 74dc91e27dbd
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
