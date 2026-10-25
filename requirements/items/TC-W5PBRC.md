---
id: TC-W5PBRC
type: test-case
title: "Verify: Telemetry pipeline restores schedule entries"
status: Approved
priority: Medium
owner: J. Müller
tags:
  - release-1.0
  - safety
parent: INFO-7P4D8D
order: 400
links:
  - type: verifies
    target: SYS-QTE64V
  - type: verifies
    target: SW-DK6ZZF
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
