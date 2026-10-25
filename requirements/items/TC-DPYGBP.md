---
id: TC-DPYGBP
type: test-case
title: "Verify: Mobile app calibrates schedule entries"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - security
  - release-2.0
parent: INFO-J0FETE
order: 60
links:
  - type: verifies
    target: SYS-5SCN5H
    confirmed: 94875c7db4c5
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
