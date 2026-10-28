---
id: REQ-NXS6BMT
type: test-case
title: "Verify: Schedule editor restores safety limits"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - security
  - customer-request
  - release-2.0
former-id: TC-ZAY22T
parent: REQ-WR5ZJN9
order: b0B
links:
  - type: verifies
    target: REQ-X86M4P6
    confirmed: bc66988537d7
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Validate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
