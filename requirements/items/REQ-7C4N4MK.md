---
id: REQ-7C4N4MK
type: test-case
title: "Verify: Schedule editor authenticates relay events"
status: Review
priority: High
owner: N. Kamal
tags:
  - accessibility
  - regulatory
former-id: TC-NWBFYE
parent: REQ-WR5ZJN9
order: aA
links:
  - type: verifies
    target: REQ-C5MAV30
    confirmed: b6d6034c72e0
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
