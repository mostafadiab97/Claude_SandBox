---
id: REQ-P8GTREH
type: test-case
title: "Verify: Telemetry pipeline detects safety limits"
status: Review
priority: Medium
owner: H. Mostafa
former-id: TC-AHXS9C
parent: REQ-8351896
order: a8
links:
  - type: verifies
    target: REQ-PRHYJ2F
    confirmed: 3497825150a9
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
