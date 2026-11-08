---
id: REQ-8XB8R32
type: test-case
title: "Verify: Wi-Fi module detects energy consumption"
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - accessibility
former-id: TC-489800
parent: REQ-67RQXCK
order: b0l
links:
  - type: verifies
    target: REQ-P411WTK
    confirmed: c760f3df8901
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
