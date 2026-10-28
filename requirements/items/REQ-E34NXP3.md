---
id: TC-4WZDA4
type: test-case
title: "Verify: Watchdog measures relay events"
status: Review
priority: High
owner: N. Kamal
tags:
  - safety
  - release-1.0
parent: INFO-Z4TW4B
order: 30
links:
  - type: verifies
    target: SYS-V7ZK4B
    confirmed: d3ae0a8a942d
  - type: verifies
    target: SW-720QYN
    confirmed: e0f62860c276
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
