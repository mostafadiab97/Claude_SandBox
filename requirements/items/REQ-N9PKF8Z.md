---
id: TC-FBN2Z7
type: test-case
title: "Verify: Telemetry pipeline notifys schedule entries"
status: Review
parent: INFO-7P4D8D
order: 600
links:
  - type: verifies
    target: SYS-3MCFDD
    confirmed: a0fea72fbd43
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
