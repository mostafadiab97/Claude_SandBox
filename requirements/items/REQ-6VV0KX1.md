---
id: REQ-6VV0KX1
type: test-case
title: "Verify: Watchdog authenticates the operating mode"
status: Review
owner: L. Samir
tags:
  - EMC
former-id: TC-CZ4DSA
parent: REQ-K6FGAY0
order: b19
links:
  - type: verifies
    target: REQ-2WZH649
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
