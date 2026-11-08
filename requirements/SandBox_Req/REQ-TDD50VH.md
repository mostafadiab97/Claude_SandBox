---
id: REQ-TDD50VH
type: test-case
title: "Verify: Over-temperature monitor validates the room temperature"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
former-id: TC-DN9JE4
parent: REQ-K6FGAY0
order: b0e
links:
  - type: verifies
    target: REQ-WKEP01A
    confirmed: 85ba3b9261c1
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
