---
id: REQ-6PSZR5D
type: test-case
title: "Verify: Device registry notifys sensor readings"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - accessibility
  - power
  - safety
former-id: TC-H71GBZ
parent: REQ-8351896
order: b1T
links:
  - type: verifies
    target: REQ-XEBH9VA
    confirmed: 00a1e26f4144
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Display energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
