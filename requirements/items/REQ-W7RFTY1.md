---
id: REQ-W7RFTY1
type: test-case
title: "Verify: Telemetry pipeline detects error conditions"
status: Approved
priority: Low
owner: A. Hassan
tags:
  - cost
  - security
  - ux
former-id: TC-VSVXYE
parent: REQ-8351896
order: aT
links:
  - type: verifies
    target: REQ-FGHND7N
    confirmed: e3f29c8362d3
  - type: verifies
    target: REQ-EWZ9BY7
    confirmed: ad7f11705f94
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Calibrate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
