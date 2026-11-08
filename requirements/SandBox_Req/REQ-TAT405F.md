---
id: REQ-TAT405F
type: test-case
title: "Verify: Enclosure notifys user preferences"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-2.0
  - cost
former-id: TC-W9KYM3
parent: REQ-F9Z1FYS
order: b1S
links:
  - type: verifies
    target: REQ-7R7H5BD
    confirmed: 843e71f7ca47
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
