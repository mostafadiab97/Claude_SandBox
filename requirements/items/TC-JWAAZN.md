---
id: TC-JWAAZN
type: test-case
title: "Verify: Watchdog synchronises safety limits"
status: Draft
priority: High
owner: محمد علي
tags:
  - regulatory
parent: INFO-Z4TW4B
order: 1140
links:
  - type: verifies
    target: SYS-BM27EB
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Restore firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
