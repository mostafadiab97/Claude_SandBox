---
id: TC-EZF6PB
type: test-case
title: "Verify: Telemetry pipeline displays the connection state"
status: Approved
owner: K. Tanaka
parent: INFO-7P4D8D
order: 250
links:
  - type: verifies
    target: SYS-X491FT
    confirmed: 8674f6feb478
  - type: verifies
    target: SW-V8G75G
    confirmed: 9bbfacd2c8bc
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
