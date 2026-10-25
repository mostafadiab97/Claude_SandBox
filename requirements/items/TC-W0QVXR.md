---
id: TC-W0QVXR
type: test-case
title: "Verify: Mobile app validates sensor readings"
status: Review
priority: Low
owner: N. Kamal
tags:
  - release-1.0
parent: INFO-J0FETE
order: 810
links:
  - type: verifies
    target: SYS-35QZ1B
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
