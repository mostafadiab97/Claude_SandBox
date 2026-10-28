---
id: REQ-CK9TDA7
type: test-case
title: "Verify: Regulation loop synchronises audit records"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - regulatory
former-id: TC-J5DPB9
parent: REQ-XGWSK2K
order: b1I
links:
  - type: verifies
    target: REQ-ACEDPGP
    confirmed: 52219f23d7ef
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
