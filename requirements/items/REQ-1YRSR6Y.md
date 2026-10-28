---
id: REQ-1YRSR6Y
type: test-case
title: "Verify: Telemetry pipeline limits audit records"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - EMC
former-id: TC-GYBY3K
parent: REQ-8351896
order: b0i
links:
  - type: verifies
    target: REQ-5JR8KWF
    confirmed: ce0c7ab3d25e
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
