---
id: TC-Y1BX4S
type: test-case
title: "Verify: Telemetry pipeline limits the room temperature"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - regulatory
parent: INFO-7P4D8D
order: 1030
links:
  - type: verifies
    target: SYS-C4HEZ6
    confirmed: d7ecad5f2748
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
