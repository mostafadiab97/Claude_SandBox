---
id: REQ-ZJ0NR40
type: test-case
title: "Verify: Mobile app logs schedule entries"
status: Review
priority: High
owner: N. Kamal
tags:
  - power
  - release-1.0
  - performance
former-id: TC-5RQ73N
parent: REQ-WR5ZJN9
order: aj
links:
  - type: verifies
    target: REQ-29843F8
    confirmed: 404b82aa8516
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Report schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
