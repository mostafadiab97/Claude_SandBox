---
id: TC-78JFCD
type: test-case
title: "Verify: Watchdog restores humidity values"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - ux
  - release-1.0
parent: INFO-Z4TW4B
order: 990
links:
  - type: verifies
    target: SYS-37F447
    confirmed: ab26978cce76
  - type: verifies
    target: SW-5P6W1P
    confirmed: 97699e3cfebd
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
