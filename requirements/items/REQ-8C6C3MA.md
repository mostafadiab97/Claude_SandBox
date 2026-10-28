---
id: REQ-8C6C3MA
type: test-case
title: "Verify: Telemetry pipeline synchronises firmware images"
status: Review
priority: Low
owner: J. Müller
tags:
  - safety
  - security
  - ux
former-id: TC-N9QPCE
parent: REQ-8351896
order: b0r
links:
  - type: verifies
    target: REQ-H73126C
    confirmed: f603768ac45b
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
