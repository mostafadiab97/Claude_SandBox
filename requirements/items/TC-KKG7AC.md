---
id: TC-KKG7AC
type: test-case
title: "Verify: Telemetry pipeline detects sensor readings"
status: Draft
priority: Medium
owner: M. Farouk
parent: INFO-7P4D8D
order: 1630
links:
  - type: verifies
    target: SYS-G85CT4
    confirmed: 278fe2b83855
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
