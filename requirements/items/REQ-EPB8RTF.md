---
id: REQ-EPB8RTF
type: test-case
title: "Verify: Local API detects the operating mode"
status: Approved
priority: High
owner: Y. Saber
tags:
  - cost
  - regulatory
  - ux
former-id: TC-XPQ955
parent: REQ-67RQXCK
order: b1K
links:
  - type: verifies
    target: REQ-HY0DZ5N
    confirmed: 342197138fa1
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
