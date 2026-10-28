---
id: REQ-V0GY4D5
type: test-case
title: "Verify: Regulation loop synchronises the room temperature"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - safety
  - performance
former-id: TC-YT9JRS
parent: REQ-XGWSK2K
order: aC
links:
  - type: verifies
    target: REQ-2QD5T4F
    confirmed: 706f127e04d0
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
