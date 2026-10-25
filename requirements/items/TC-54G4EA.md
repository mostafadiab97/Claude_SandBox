---
id: TC-54G4EA
type: test-case
title: "Verify: Battery backup calibrates error conditions"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - safety
  - performance
parent: INFO-MACGC3
order: 1140
links:
  - type: verifies
    target: SYS-PNS6E7
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
