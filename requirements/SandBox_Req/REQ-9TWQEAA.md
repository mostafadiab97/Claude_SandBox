---
id: REQ-9TWQEAA
type: test-case
title: "Verify: User account service measures firmware images"
status: Draft
priority: Low
owner: J. Müller
tags:
  - connectivity
  - release-2.0
former-id: TC-SQRWQD
parent: REQ-8351896
order: aP
links:
  - type: verifies
    target: REQ-7CV0RRH
    confirmed: 2fc7492bf655
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
