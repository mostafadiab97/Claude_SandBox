---
id: REQ-1ARC4ER
type: test-case
title: "Verify: Status LED reports access tokens"
status: Draft
priority: High
owner: S. Adel
tags:
  - release-1.0
former-id: TC-V8XQVD
parent: REQ-Y9VHHKA
order: b05
links:
  - type: verifies
    target: REQ-2RR2EQ4
    confirmed: 3622c05b8ec0
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
