---
id: REQ-K0S3V9E
type: test-case
title: "Verify: Telemetry pipeline detects humidity values"
status: Draft
priority: High
tags:
  - connectivity
former-id: TC-G1PZ3X
parent: REQ-8351896
order: b1a
links:
  - type: verifies
    target: REQ-HZB6Z1A
    confirmed: 2208a37cfcbe
  - type: verifies
    target: REQ-JFZCMPM
    confirmed: 2dee49b460da
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
