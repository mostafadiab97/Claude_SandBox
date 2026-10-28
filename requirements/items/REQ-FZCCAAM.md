---
id: REQ-FZCCAAM
type: test-case
title: "Verify: Telemetry pipeline displays firmware images"
status: Approved
priority: Medium
owner: L. Samir
former-id: TC-K6DYGD
parent: REQ-8351896
order: a6
links:
  - type: verifies
    target: REQ-YRG0KW0
    confirmed: 3e7e54a5d4f3
  - type: verifies
    target: REQ-ZZ2DVYX
    confirmed: ea7ac01e52a8
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Authenticate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
