---
id: TC-VSVXYE
type: test-case
title: "Verify: Telemetry pipeline detects error conditions"
status: Approved
priority: Low
owner: A. Hassan
tags:
  - cost
  - security
  - ux
parent: INFO-7P4D8D
order: 300
links:
  - type: verifies
    target: SYS-3FB1DA
  - type: verifies
    target: SW-7NWEV1
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
