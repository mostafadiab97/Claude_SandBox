---
id: REQ-73E1KNB
type: test-case
title: "Verify: Local API authenticates relay events"
status: Obsolete
priority: High
owner: N. Kamal
tags:
  - regulatory
former-id: TC-05VR4B
parent: REQ-67RQXCK
order: b0W
links:
  - type: verifies
    target: REQ-HFKWETR
    confirmed: f28f5499c8de
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
