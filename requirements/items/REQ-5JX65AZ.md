---
id: TC-VM6XAF
type: test-case
title: "Verify: Mobile app switchs the operating mode"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - i18n
  - performance
  - security
parent: INFO-J0FETE
order: 1010
links:
  - type: verifies
    target: SYS-ZENQH5
    confirmed: 2ab203b72e19
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Authenticate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
