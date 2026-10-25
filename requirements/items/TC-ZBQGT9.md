---
id: TC-ZBQGT9
type: test-case
title: "Verify: Relay board detects the room temperature"
status: Approved
priority: Medium
tags:
  - release-2.0
parent: INFO-MACGC3
order: 290
links:
  - type: verifies
    target: SYS-1JDYJJ
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
