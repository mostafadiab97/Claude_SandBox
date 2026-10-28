---
id: REQ-8CDN95P
type: test-case
title: "Verify: Local API limits the operating mode"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - accessibility
former-id: TC-CMXWE1
parent: REQ-67RQXCK
order: b0d
links:
  - type: verifies
    target: REQ-B2JJXAA
    confirmed: f55a56f18a08
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
