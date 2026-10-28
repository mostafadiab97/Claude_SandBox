---
id: REQ-ZHWSBXS
type: test-case
title: "Verify: User account service measures the room temperature"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - power
  - accessibility
  - release-1.0
former-id: TC-6FYW45
parent: REQ-8351896
order: b0I
links:
  - type: verifies
    target: REQ-13K6ME8
    confirmed: ff47382f2bba
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
