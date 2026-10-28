---
id: REQ-3DEA39P
type: test-case
title: "Verify: Enclosure measures access tokens"
status: Review
priority: Medium
owner: L. Samir
tags:
  - power
  - regulatory
  - release-1.0
former-id: TC-DAEQTK
parent: REQ-F9Z1FYS
order: aN
links:
  - type: verifies
    target: REQ-6XTSEB4
    confirmed: 8a991d854752
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Display humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
