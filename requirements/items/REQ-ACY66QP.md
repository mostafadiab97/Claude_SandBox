---
id: REQ-ACY66QP
type: test-case
title: "Verify: Telemetry pipeline limits the room temperature"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - regulatory
former-id: TC-Y1BX4S
parent: REQ-8351896
order: b0e
links:
  - type: verifies
    target: REQ-BF9Y5RT
    confirmed: d7ecad5f2748
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
