---
id: REQ-822CWX5
type: test-case
title: "Verify: Watchdog calibrates the room temperature"
status: Approved
priority: High
owner: J. Müller
tags:
  - release-1.0
  - safety
  - ux
former-id: TC-S3H2BH
parent: REQ-K6FGAY0
order: b07
links:
  - type: verifies
    target: REQ-AN5WSWC
    confirmed: ef7ce1eb28d3
  - type: verifies
    target: REQ-DX9XHYM
    confirmed: 850242f25f43
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
