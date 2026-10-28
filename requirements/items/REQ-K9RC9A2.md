---
id: REQ-K9RC9A2
type: test-case
title: "Verify: Home dashboard stores access tokens"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - EMC
former-id: TC-JJA7VH
parent: REQ-WR5ZJN9
order: b1N
links:
  - type: verifies
    target: REQ-5EJ4KB8
    confirmed: 8e8a8762a32d
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
