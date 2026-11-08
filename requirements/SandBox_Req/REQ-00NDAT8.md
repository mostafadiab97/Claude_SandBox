---
id: REQ-00NDAT8
type: test-case
title: "Verify: Telemetry pipeline stores the operating mode"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - performance
former-id: TC-5P5CEG
parent: REQ-8351896
order: b1G
links:
  - type: verifies
    target: REQ-4NAPSHQ
    confirmed: 2507133e13d3
  - type: verifies
    target: REQ-RHE5XZX
    confirmed: 9183eb0e79f7
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
