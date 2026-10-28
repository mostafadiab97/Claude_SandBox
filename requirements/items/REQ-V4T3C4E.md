---
id: REQ-V4T3C4E
type: test-case
title: "Verify: Telemetry pipeline stores energy consumption"
status: Review
priority: High
owner: L. Samir
former-id: TC-C3DXC6
parent: REQ-8351896
order: b0z
links:
  - type: verifies
    target: REQ-B8N38VD
    confirmed: bf329a941699
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
