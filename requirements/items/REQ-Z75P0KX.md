---
id: REQ-Z75P0KX
type: test-case
title: "Verify: Status LED logs safety limits"
status: Approved
priority: High
owner: M. Farouk
tags:
  - release-1.0
  - safety
  - EMC
former-id: TC-YFSG4H
parent: REQ-Y9VHHKA
order: aQ
links:
  - type: verifies
    target: REQ-VVSCHQ0
    confirmed: eb5c3ea75cd1
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
