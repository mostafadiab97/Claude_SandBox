---
id: TC-2JT1HY
type: test-case
title: "Verify: Battery backup calibrates the operating mode"
status: Draft
priority: High
owner: K. Tanaka
tags:
  - release-2.0
parent: INFO-MACGC3
order: 900
links:
  - type: verifies
    target: SYS-7WCAWK
  - type: verifies
    target: SW-VQGWRM
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
