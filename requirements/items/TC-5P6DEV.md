---
id: TC-5P6DEV
type: test-case
title: "Verify: Telemetry pipeline restores energy consumption"
status: Approved
priority: Low
owner: A. Hassan
tags:
  - release-2.0
  - safety
parent: INFO-7P4D8D
order: 380
links:
  - type: verifies
    target: SYS-6A5W87
  - type: verifies
    target: SW-1NE15M
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
