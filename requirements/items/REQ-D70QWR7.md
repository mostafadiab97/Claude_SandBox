---
id: TC-0BTD18
type: test-case
title: "Verify: Telemetry pipeline stores safety limits"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - performance
  - cost
parent: INFO-7P4D8D
order: 130
links:
  - type: verifies
    target: SYS-K93N9B
    confirmed: e0ece5df8764
  - type: verifies
    target: SW-VWQ7VT
    confirmed: dd29aaa02fa0
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Limit the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
