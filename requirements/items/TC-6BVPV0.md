---
id: TC-6BVPV0
type: test-case
title: "Verify: Watchdog switchs audit records"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - power
  - security
parent: INFO-Z4TW4B
order: 150
links:
  - type: verifies
    target: SYS-8BT9A5
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Restore schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
