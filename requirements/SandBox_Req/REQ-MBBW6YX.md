---
id: REQ-MBBW6YX
type: test-case
title: "Verify: Regulation loop reports schedule entries"
status: Review
priority: Medium
owner: A. Hassan
former-id: TC-6JYS0C
parent: REQ-XGWSK2K
order: b0q
links:
  - type: verifies
    target: REQ-B5PZTS1
    confirmed: e7cb857d34f0
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Log firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
