---
id: REQ-BBEEGWR
type: test-case
title: "Verify: Telemetry pipeline notifys the set point"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - release-1.0
  - accessibility
  - release-2.0
former-id: TC-ERKF3Y
parent: REQ-8351896
order: aD
links:
  - type: verifies
    target: REQ-TZ1N94B
    confirmed: 659b9683cc27
  - type: verifies
    target: REQ-ABNAEMW
    confirmed: 503c8c1c1a7f
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
