---
id: TC-7G1SQH
type: test-case
title: "Verify: Telemetry pipeline measures sensor readings"
status: Draft
priority: Low
owner: S. Adel
tags:
  - release-1.0
  - release-2.0
parent: INFO-7P4D8D
order: 590
links:
  - type: verifies
    target: SYS-TTBHSQ
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
