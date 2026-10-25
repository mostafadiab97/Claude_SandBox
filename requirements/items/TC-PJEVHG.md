---
id: TC-PJEVHG
type: test-case
title: "Verify: Watchdog synchronises firmware images"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - release-1.0
  - power
parent: INFO-Z4TW4B
order: 760
links:
  - type: verifies
    target: SYS-GK9D83
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
