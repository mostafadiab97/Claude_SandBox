---
id: REQ-8F5W5S9
type: test-case
title: "Verify: Mobile app notifys audit records"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - power
former-id: TC-E7SH0H
parent: REQ-WR5ZJN9
order: a9
links:
  - type: verifies
    target: REQ-R2X3WD7
    confirmed: c7fe0edbb759
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Report the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
