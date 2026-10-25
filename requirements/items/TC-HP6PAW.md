---
id: TC-HP6PAW
type: test-case
title: "Verify: Enclosure logs the operating mode"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - safety
parent: INFO-MACGC3
order: 1710
links:
  - type: verifies
    target: SYS-10B2S4
    confirmed: b19977729874
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
