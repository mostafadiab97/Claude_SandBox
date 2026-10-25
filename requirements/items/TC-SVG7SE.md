---
id: TC-SVG7SE
type: test-case
title: "Verify: Watchdog reports schedule entries"
status: Review
priority: Medium
owner: محمد علي
tags:
  - power
  - connectivity
parent: INFO-Z4TW4B
order: 1070
links:
  - type: verifies
    target: SYS-NVH3G7
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Restore energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
