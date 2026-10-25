---
id: TC-ERKF3Y
type: test-case
title: "Verify: Telemetry pipeline notifys the set point"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - release-1.0
  - accessibility
  - release-2.0
parent: INFO-7P4D8D
order: 140
links:
  - type: verifies
    target: SYS-KBPFCV
  - type: verifies
    target: SW-QGJY9V
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
