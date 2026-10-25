---
id: TC-H9DZYA
type: test-case
title: "Verify: Telemetry pipeline limits access tokens"
status: Approved
priority: High
owner: S. Adel
tags:
  - EMC
  - power
  - regulatory
parent: INFO-7P4D8D
order: 1150
links:
  - type: verifies
    target: SYS-AC34S0
  - type: verifies
    target: SW-BYV6KE
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
