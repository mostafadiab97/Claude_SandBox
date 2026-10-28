---
id: REQ-SWAZB04
type: test-case
title: "Verify: Telemetry pipeline detects sensor readings"
status: Draft
priority: Medium
owner: M. Farouk
former-id: TC-KKG7AC
parent: REQ-8351896
order: b1c
links:
  - type: verifies
    target: REQ-3485MQF
    confirmed: 278fe2b83855
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
