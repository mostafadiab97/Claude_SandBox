---
id: REQ-N9PKF8Z
type: test-case
title: "Verify: Telemetry pipeline notifys schedule entries"
status: Review
former-id: TC-FBN2Z7
parent: REQ-8351896
order: ax
links:
  - type: verifies
    target: REQ-89S1J9Z
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
