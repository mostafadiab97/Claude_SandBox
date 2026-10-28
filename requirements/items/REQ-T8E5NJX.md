---
id: REQ-T8E5NJX
type: test-case
title: "Verify: Telemetry pipeline restores schedule entries"
status: Approved
priority: Medium
owner: J. Müller
tags:
  - release-1.0
  - safety
former-id: TC-W5PBRC
parent: REQ-8351896
order: ad
links:
  - type: verifies
    target: REQ-DQ0W5RA
    confirmed: 27661a1b1fc7
  - type: verifies
    target: REQ-5ERHXB0
    confirmed: 3b32dc108d16
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
