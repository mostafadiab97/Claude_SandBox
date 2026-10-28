---
id: TC-6SZKFA
type: test-case
title: "Verify: Heat pump driver measures firmware images"
status: Review
priority: Medium
owner: L. Samir
tags:
  - power
parent: INFO-MS9DAG
order: 1470
links:
  - type: verifies
    target: SYS-3NA7W8
    confirmed: 303f8590e242
  - type: verifies
    target: SW-F7EPJP
    confirmed: feab156e1a57
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
