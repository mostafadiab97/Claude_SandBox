---
id: TC-V8PNPQ
type: test-case
title: "Verify: Telemetry pipeline displays error conditions"
status: Obsolete
owner: Y. Saber
tags:
  - security
  - release-2.0
parent: INFO-7P4D8D
order: 1670
links:
  - type: verifies
    target: SYS-REMSS6
    confirmed: 987d596109aa
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Encrypt energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
