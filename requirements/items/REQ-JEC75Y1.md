---
id: REQ-JEC75Y1
type: test-case
title: "Verify: Home dashboard logs the room temperature"
status: Draft
priority: High
owner: J. Müller
tags:
  - performance
  - release-1.0
former-id: TC-QS422F
parent: REQ-WR5ZJN9
order: as
links:
  - type: verifies
    target: REQ-60N26XW
    confirmed: 2cd9efe1d517
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Switch schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
