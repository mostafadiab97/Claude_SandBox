---
id: TC-CZ4DSA
type: test-case
title: "Verify: Watchdog authenticates the operating mode"
status: Review
owner: L. Samir
tags:
  - EMC
parent: INFO-Z4TW4B
order: 1340
links:
  - type: verifies
    target: SYS-WPKDG7
    confirmed: 871bc601285c
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Notify humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
