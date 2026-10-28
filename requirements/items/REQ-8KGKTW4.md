---
id: TC-YX0AYF
type: test-case
title: "Verify: Relay board reports sensor readings"
status: Review
priority: Low
owner: Y. Saber
tags:
  - regulatory
  - release-1.0
parent: INFO-MACGC3
order: 640
links:
  - type: verifies
    target: SYS-9B4YX3
    confirmed: 7e7b28ad44d1
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
