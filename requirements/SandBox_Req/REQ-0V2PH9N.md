---
id: REQ-0V2PH9N
type: test-case
title: "Verify: Regulation loop authenticates schedule entries"
status: Draft
priority: High
owner: R. Nabil
tags:
  - power
  - safety
former-id: TC-BMJM85
parent: REQ-XGWSK2K
order: b0m
links:
  - type: verifies
    target: REQ-Q3Z9QBY
    confirmed: 0398140de13d
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
