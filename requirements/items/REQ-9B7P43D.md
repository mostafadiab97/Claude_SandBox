---
id: REQ-9B7P43D
type: test-case
title: "Verify: Telemetry pipeline restores energy consumption"
status: Approved
priority: Low
owner: A. Hassan
tags:
  - release-2.0
  - safety
former-id: TC-5P6DEV
parent: REQ-8351896
order: ab
links:
  - type: verifies
    target: REQ-9YN386K
    confirmed: 739d6ec12ecc
  - type: verifies
    target: REQ-3FB2ST0
    confirmed: c98e92367d85
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
