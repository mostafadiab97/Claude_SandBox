---
id: REQ-8NWS16X
type: test-case
title: "Verify: Telemetry pipeline validates audit records"
status: Draft
priority: High
owner: N. Kamal
former-id: TC-T93CYR
parent: REQ-8351896
order: b0s
links:
  - type: verifies
    target: REQ-V3SSX4W
    confirmed: f66b9f28edb5
  - type: verifies
    target: REQ-522SQG5
    confirmed: 5823f2494dfc
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
