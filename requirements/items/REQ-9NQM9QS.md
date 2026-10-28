---
id: REQ-9NQM9QS
type: test-case
title: "Verify: Wi-Fi module switchs humidity values"
status: Obsolete
priority: Medium
owner: محمد علي
tags:
  - accessibility
  - regulatory
former-id: TC-7C271Q
parent: REQ-67RQXCK
order: b0h
links:
  - type: verifies
    target: REQ-JMY59GP
    confirmed: 879d2491ed8f
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
