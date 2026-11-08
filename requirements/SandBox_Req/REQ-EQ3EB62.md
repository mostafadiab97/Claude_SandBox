---
id: REQ-EQ3EB62
type: test-case
title: "Verify: OTA server stores the room temperature"
status: Review
priority: Medium
owner: L. Samir
tags:
  - performance
former-id: TC-XZ3SSZ
parent: REQ-8351896
order: b1V
links:
  - type: verifies
    target: REQ-9FZHANA
    confirmed: 08cad2a24d2f
  - type: verifies
    target: REQ-CMXC7R6
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
