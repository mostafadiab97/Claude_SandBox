---
id: REQ-7X7ZFSD
type: test-case
title: "Verify: Telemetry pipeline displays error conditions"
status: Approved
priority: High
owner: É. Laurent
former-id: TC-799X7Z
parent: REQ-8351896
order: a5
links:
  - type: verifies
    target: REQ-FGY59FP
    confirmed: f027b997b7f0
  - type: verifies
    target: REQ-GMP88V8
    confirmed: e02c4513eee6
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
