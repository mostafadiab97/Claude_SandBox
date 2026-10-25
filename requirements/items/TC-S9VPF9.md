---
id: TC-S9VPF9
type: test-case
title: "Verify: Watchdog switchs relay events"
status: Draft
priority: High
owner: R. Nabil
tags:
  - performance
  - regulatory
  - EMC
parent: INFO-Z4TW4B
order: 860
links:
  - type: verifies
    target: SYS-CB769Y
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
