---
id: TC-HGC5N5
type: test-case
title: "Verify: Watchdog encrypts user preferences"
status: Approved
priority: High
owner: محمد علي
tags:
  - safety
  - cost
  - security
parent: INFO-Z4TW4B
order: 670
links:
  - type: verifies
    target: SYS-BKCVJB
  - type: verifies
    target: SW-NSH5XV
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
