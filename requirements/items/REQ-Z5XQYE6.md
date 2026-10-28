---
id: REQ-Z5XQYE6
type: test-case
title: "Verify: Pairing process logs the operating mode"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - security
former-id: TC-H53HHV
parent: REQ-67RQXCK
order: b1E
links:
  - type: verifies
    target: REQ-CJE6CS7
    confirmed: 906d4acd43e6
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Report firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
