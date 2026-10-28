---
id: REQ-1FREB8F
type: test-case
title: "Verify: Watchdog switchs relay events"
status: Draft
priority: High
owner: R. Nabil
tags:
  - performance
  - regulatory
  - EMC
former-id: TC-S9VPF9
parent: REQ-K6FGAY0
order: b0N
links:
  - type: verifies
    target: REQ-W7GCRX4
    confirmed: 78ff4291b8f5
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
