---
id: REQ-6Z0APZ2
type: test-case
title: "Verify: Battery backup calibrates error conditions"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - safety
  - performance
former-id: TC-54G4EA
parent: REQ-F9Z1FYS
order: b0p
links:
  - type: verifies
    target: REQ-V2FX8Q3
    confirmed: 67545fb801f7
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
