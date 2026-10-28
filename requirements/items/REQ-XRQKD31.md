---
id: REQ-XRQKD31
type: test-case
title: "Verify: Telemetry pipeline switchs audit records"
status: Obsolete
priority: High
owner: H. Mostafa
tags:
  - EMC
  - ux
former-id: TC-C29TRF
parent: REQ-8351896
order: au
links:
  - type: verifies
    target: REQ-3S52D2S
    confirmed: c0d19b7ef2ea
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
