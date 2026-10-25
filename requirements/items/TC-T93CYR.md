---
id: TC-T93CYR
type: test-case
title: "Verify: Telemetry pipeline validates audit records"
status: Draft
priority: High
owner: N. Kamal
parent: INFO-7P4D8D
order: 1170
links:
  - type: verifies
    target: SYS-MK2A6C
  - type: verifies
    target: SW-WKH1E6
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
