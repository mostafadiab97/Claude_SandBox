---
id: TC-327CWJ
type: test-case
title: "Verify: Telemetry pipeline synchronises safety limits"
status: Approved
priority: Low
owner: N. Kamal
tags:
  - safety
  - customer-request
  - i18n
parent: INFO-7P4D8D
order: 160
links:
  - type: verifies
    target: SYS-77PVXT
    confirmed: 33b1a201b47a
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
