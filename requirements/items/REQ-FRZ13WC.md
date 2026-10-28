---
id: REQ-FRZ13WC
type: test-case
title: "Verify: Watchdog synchronises firmware images"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - release-1.0
  - power
former-id: TC-PJEVHG
parent: REQ-K6FGAY0
order: b0D
links:
  - type: verifies
    target: REQ-694D023
    confirmed: e117ad0083a4
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
