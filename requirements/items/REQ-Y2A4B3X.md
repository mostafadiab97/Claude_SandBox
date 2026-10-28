---
id: REQ-Y2A4B3X
type: test-case
title: "Verify: Watchdog reports schedule entries"
status: Review
priority: Medium
owner: محمد علي
tags:
  - power
  - connectivity
former-id: TC-SVG7SE
parent: REQ-K6FGAY0
order: b0i
links:
  - type: verifies
    target: REQ-SATNXSC
    confirmed: a822090bf9b4
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Restore energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
