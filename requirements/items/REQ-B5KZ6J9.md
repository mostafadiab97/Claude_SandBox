---
id: REQ-B5KZ6J9
type: test-case
title: "Verify: Local API notifys user preferences"
status: Obsolete
priority: Medium
owner: محمد علي
tags:
  - cost
former-id: TC-WYE71E
parent: REQ-67RQXCK
order: az
links:
  - type: verifies
    target: REQ-P78AYDQ
    confirmed: a9c0f51b3815
  - type: verifies
    target: REQ-2S5180J
    confirmed: b1317ed9239c
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
