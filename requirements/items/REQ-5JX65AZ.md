---
id: REQ-5JX65AZ
type: test-case
title: "Verify: Mobile app switchs the operating mode"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - i18n
  - performance
  - security
former-id: TC-VM6XAF
parent: REQ-WR5ZJN9
order: b0c
links:
  - type: verifies
    target: REQ-XDK478A
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
