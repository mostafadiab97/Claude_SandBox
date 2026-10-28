---
id: REQ-FV9RMQK
type: test-case
title: "Verify: Telemetry pipeline restores schedule entries"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - safety
  - power
former-id: TC-49E755
parent: REQ-8351896
order: b19
links:
  - type: verifies
    target: REQ-A5VJKDZ
    confirmed: 6b28de77da9f
  - type: verifies
    target: REQ-2AFGFSP
    confirmed: 9395fb23e6ef
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Calibrate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
