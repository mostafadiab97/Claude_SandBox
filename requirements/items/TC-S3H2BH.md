---
id: TC-S3H2BH
type: test-case
title: "Verify: Watchdog calibrates the room temperature"
status: Approved
priority: High
owner: J. Müller
tags:
  - release-1.0
  - safety
  - ux
parent: INFO-Z4TW4B
order: 700
links:
  - type: verifies
    target: SYS-WKCZDQ
  - type: verifies
    target: SW-K3F3HS
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
