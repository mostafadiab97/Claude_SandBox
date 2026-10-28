---
id: TC-XZ3SSZ
type: test-case
title: "Verify: OTA server stores the room temperature"
status: Review
priority: Medium
owner: L. Samir
tags:
  - performance
parent: INFO-7P4D8D
order: 1560
links:
  - type: verifies
    target: SYS-2NQ3E8
    confirmed: 08cad2a24d2f
  - type: verifies
    target: SW-EHGN0R
    confirmed: c5b8f223d682
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
