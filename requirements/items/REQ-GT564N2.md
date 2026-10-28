---
id: REQ-GT564N2
type: test-case
title: "Verify: Power supply synchronises sensor readings"
status: Review
priority: High
owner: K. Tanaka
tags:
  - performance
  - accessibility
former-id: TC-A6TS75
parent: REQ-F9Z1FYS
order: b18
links:
  - type: verifies
    target: REQ-8HP4PG1
    confirmed: e13fd0c463a4
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Report the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
