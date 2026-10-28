---
id: TC-NPBHZC
type: test-case
title: "Verify: OTA server detects the set point"
status: Review
priority: High
owner: R. Nabil
tags:
  - connectivity
parent: INFO-7P4D8D
order: 80
links:
  - type: verifies
    target: SYS-2RPS4X
    confirmed: 6a90f09e6ec1
  - type: verifies
    target: SW-EJ1VD0
    confirmed: 34b66d1bd62f
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Measure error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
