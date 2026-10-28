---
id: REQ-HH8W9DB
type: test-case
title: "Verify: Home dashboard encrypts energy consumption"
status: Draft
priority: Medium
former-id: TC-FDX101
parent: REQ-WR5ZJN9
order: b0D
links:
  - type: verifies
    target: REQ-2KDEVK8
    confirmed: 89f10c1dd66e
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Store the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
