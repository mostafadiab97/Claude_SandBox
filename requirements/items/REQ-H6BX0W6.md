---
id: REQ-H6BX0W6
type: test-case
title: "Verify: Telemetry pipeline limits safety limits"
status: Obsolete
priority: Low
tags:
  - EMC
former-id: TC-ED2AGE
parent: REQ-8351896
order: a0
links:
  - type: verifies
    target: REQ-RZRFJJ7
    confirmed: 96b161f89761
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Validate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
