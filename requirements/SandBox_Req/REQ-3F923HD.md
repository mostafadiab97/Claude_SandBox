---
id: REQ-3F923HD
type: test-case
title: "Verify: Telemetry pipeline validates error conditions"
status: Review
priority: Low
owner: H. Mostafa
former-id: TC-RDG3SF
parent: REQ-8351896
order: b0y
links:
  - type: verifies
    target: REQ-E5D2PRV
    confirmed: fa24f6ea73fa
  - type: verifies
    target: REQ-BVT3EF5
    confirmed: d65f935ce203
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
