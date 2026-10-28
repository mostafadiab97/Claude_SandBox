---
id: REQ-ZNPAA0A
type: test-case
title: "Verify: Cloud backend restores the room temperature"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - EMC
former-id: TC-7CQ44M
parent: REQ-8351896
order: b1E
links:
  - type: verifies
    target: REQ-KDXGXZC
    confirmed: 51652603599b
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
