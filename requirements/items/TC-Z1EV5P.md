---
id: TC-Z1EV5P
type: test-case
title: "Verify: Battery backup stores sensor readings"
status: Review
priority: Low
owner: A. Hassan
parent: INFO-MACGC3
order: 1090
links:
  - type: verifies
    target: SYS-7XYG17
    confirmed: b02cb0cbf227
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
