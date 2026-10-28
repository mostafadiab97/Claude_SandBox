---
id: TC-N9QPCE
type: test-case
title: "Verify: Telemetry pipeline synchronises firmware images"
status: Review
priority: Low
owner: J. Müller
tags:
  - safety
  - security
  - ux
parent: INFO-7P4D8D
order: 1160
links:
  - type: verifies
    target: SYS-BA2G1M
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
