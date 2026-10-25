---
id: TC-23QE8C
type: test-case
title: "Verify: Telemetry pipeline switchs safety limits"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
parent: INFO-7P4D8D
order: 1010
links:
  - type: verifies
    target: SYS-MQY2B0
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
