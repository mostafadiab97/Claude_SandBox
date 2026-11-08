---
id: REQ-40QCVBT
type: test-case
title: "Verify: Telemetry pipeline displays the set point"
status: Draft
priority: High
owner: M. Farouk
tags:
  - accessibility
former-id: TC-9Q2PAR
parent: REQ-8351896
order: b1N
links:
  - type: verifies
    target: REQ-EP8W3RT
    confirmed: 1f0c64db8df4
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
