---
id: TC-ZAY22T
type: test-case
title: "Verify: Schedule editor restores safety limits"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - security
  - customer-request
  - release-2.0
parent: INFO-J0FETE
order: 740
links:
  - type: verifies
    target: SYS-FCT3MK
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
