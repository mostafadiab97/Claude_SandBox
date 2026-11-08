---
id: REQ-0RY7R0P
type: test-case
title: "Verify: Mobile app stores humidity values"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - performance
  - EMC
  - ux
former-id: TC-FRZ3JJ
parent: REQ-WR5ZJN9
order: ag
links:
  - type: verifies
    target: REQ-TK8PFSP
    confirmed: d30e404e164e
  - type: verifies
    target: REQ-GWHHVB1
    confirmed: 9c00155f291a
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
