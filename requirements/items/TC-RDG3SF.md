---
id: TC-RDG3SF
type: test-case
title: "Verify: Telemetry pipeline validates error conditions"
status: Review
priority: Low
owner: H. Mostafa
parent: INFO-7P4D8D
order: 1230
links:
  - type: verifies
    target: SYS-FP6P6A
  - type: verifies
    target: SW-82VWC8
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Encrypt the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
