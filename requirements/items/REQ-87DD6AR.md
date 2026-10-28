---
id: TC-PSQ8B1
type: test-case
title: "Verify: Telemetry pipeline reports the operating mode"
status: Approved
priority: High
owner: S. Adel
tags:
  - EMC
  - release-1.0
  - cost
parent: INFO-7P4D8D
order: 170
links:
  - type: verifies
    target: SYS-Z2TFC8
    confirmed: 985116655f53
  - type: verifies
    target: SW-KZQTY6
    confirmed: 2d0abae3753b
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
