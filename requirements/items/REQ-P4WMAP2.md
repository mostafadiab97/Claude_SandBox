---
id: REQ-P4WMAP2
type: test-case
title: "Verify: Telemetry pipeline displays the connection state"
status: Approved
owner: K. Tanaka
former-id: TC-EZF6PB
parent: REQ-8351896
order: aO
links:
  - type: verifies
    target: REQ-YYB3TCA
    confirmed: 8674f6feb478
  - type: verifies
    target: REQ-A4C1RDV
    confirmed: 9bbfacd2c8bc
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
