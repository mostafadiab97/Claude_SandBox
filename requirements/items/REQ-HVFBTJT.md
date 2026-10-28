---
id: REQ-HVFBTJT
type: test-case
title: "Verify: Telemetry pipeline detects the set point"
status: Review
priority: Medium
owner: L. Samir
tags:
  - EMC
  - power
former-id: TC-A2RJJX
parent: REQ-8351896
order: an
links:
  - type: verifies
    target: REQ-4Z5Y12M
    confirmed: 805d152578fb
  - type: verifies
    target: REQ-ZBGDWCB
    confirmed: 7a9b0fc62add
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
