---
id: TC-BZFCE0
type: test-case
title: "Verify: Login screen calibrates humidity values"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - accessibility
parent: INFO-J0FETE
order: 600
links:
  - type: verifies
    target: SYS-Y9J3XR
    confirmed: e9321a9a2b2f
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
