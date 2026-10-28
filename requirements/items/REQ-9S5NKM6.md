---
id: REQ-9S5NKM6
type: test-case
title: "Verify: Boiler interface detects access tokens"
status: Approved
priority: High
owner: J. Müller
tags:
  - safety
former-id: TC-RACC9H
parent: REQ-XGWSK2K
order: aO
links:
  - type: verifies
    target: REQ-XW7FZ05
    confirmed: 2cf0a5310219
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Validate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
