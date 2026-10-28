---
id: TC-Z2HYDQ
type: test-case
title: "Verify: Telemetry pipeline limits error conditions"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - EMC
parent: INFO-7P4D8D
order: 1580
links:
  - type: verifies
    target: SYS-SQM30D
    confirmed: 61b33a5fb3c5
  - type: verifies
    target: SW-RKA76Z
    confirmed: f76ca26e4df8
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
