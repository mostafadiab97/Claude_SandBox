---
id: REQ-VVP1W0H
type: test-case
title: "Verify: Regulation loop stores user preferences"
status: Draft
priority: Medium
former-id: TC-55YBA0
parent: REQ-XGWSK2K
order: b0I
links:
  - type: verifies
    target: REQ-QZW142T
    confirmed: 450d9078b1b0
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
