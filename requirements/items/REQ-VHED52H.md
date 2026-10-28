---
id: REQ-VHED52H
type: test-case
title: "Verify: Telemetry pipeline restores sensor readings"
status: Draft
priority: High
owner: محمد علي
tags:
  - regulatory
  - accessibility
former-id: TC-QP59SJ
parent: REQ-8351896
order: b1P
links:
  - type: verifies
    target: REQ-D8575E7
    confirmed: 11ac230159e7
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
