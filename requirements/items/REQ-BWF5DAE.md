---
id: REQ-BWF5DAE
type: test-case
title: "Verify: Watchdog calibrates the connection state"
status: Obsolete
priority: Low
owner: H. Mostafa
tags:
  - release-2.0
former-id: TC-RW5T9Z
parent: REQ-K6FGAY0
order: b0z
links:
  - type: verifies
    target: REQ-YPG30G6
    confirmed: 4c2aa84ed807
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
