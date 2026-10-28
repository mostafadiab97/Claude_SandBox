---
id: REQ-MNGGYEB
type: test-case
title: "Verify: Watchdog displays error conditions"
status: Approved
priority: Low
owner: N. Kamal
former-id: TC-AE03E9
parent: REQ-K6FGAY0
order: ak
links:
  - type: verifies
    target: REQ-RHW7HNJ
    confirmed: a257d6fd1501
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
