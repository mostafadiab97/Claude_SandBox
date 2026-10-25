---
id: TC-GYBY3K
type: test-case
title: "Verify: Telemetry pipeline limits audit records"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - EMC
parent: INFO-7P4D8D
order: 1070
links:
  - type: verifies
    target: SYS-35NR1X
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
