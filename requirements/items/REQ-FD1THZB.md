---
id: REQ-FD1THZB
type: test-case
title: "Verify: Relay board detects error conditions"
status: Draft
priority: Low
owner: L. Samir
tags:
  - i18n
former-id: TC-JK74PG
parent: REQ-F9Z1FYS
order: b0L
links:
  - type: verifies
    target: REQ-P9DQTYH
    confirmed: af22712052f7
  - type: verifies
    target: REQ-0X5RN4G
    confirmed: 4246796f63fe
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Restore the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
