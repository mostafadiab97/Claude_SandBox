---
id: REQ-EJKE7AA
type: test-case
title: "Verify: Boiler interface limits audit records"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - customer-request
  - safety
former-id: TC-BJWMZ7
parent: REQ-XGWSK2K
order: b0L
links:
  - type: verifies
    target: REQ-BD7JAPN
    confirmed: 112d894849fe
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
