---
id: REQ-0FM429R
type: test-case
title: "Verify: User account service reports schedule entries"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - security
  - accessibility
former-id: TC-B49CJC
parent: REQ-8351896
order: b1J
links:
  - type: verifies
    target: REQ-2PQ5B0D
    confirmed: 3e6744bf9b31
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
