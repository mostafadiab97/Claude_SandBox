---
id: REQ-09FS5BY
type: test-case
title: "Verify: Telemetry pipeline measures the connection state"
status: Review
priority: Medium
owner: K. Tanaka
former-id: TC-J003SH
parent: REQ-8351896
order: b0u
links:
  - type: verifies
    target: REQ-W2575G6
    confirmed: 19606134e5ee
  - type: verifies
    target: REQ-X3Z0G5P
    confirmed: cae59bc43b0e
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
