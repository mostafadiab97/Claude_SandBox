---
id: REQ-Z8SQ9TZ
type: test-case
title: "Verify: Wi-Fi module reports humidity values"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - power
former-id: TC-6JRQRQ
parent: REQ-67RQXCK
order: b0U
links:
  - type: verifies
    target: REQ-SHYGEGX
    confirmed: bc96873ba6c1
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
