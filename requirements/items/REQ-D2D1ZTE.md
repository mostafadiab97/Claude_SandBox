---
id: REQ-D2D1ZTE
type: test-case
title: "Verify: Telemetry pipeline switchs safety limits"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
former-id: TC-23QE8C
parent: REQ-8351896
order: b0c
links:
  - type: verifies
    target: REQ-090RJ6Q
    confirmed: ab87fdd691b9
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Encrypt user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
