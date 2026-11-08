---
id: REQ-Z0M4ZPB
type: test-case
title: "Verify: Wi-Fi module authenticates the set point"
status: Draft
priority: High
tags:
  - i18n
  - EMC
former-id: TC-QP5201
parent: REQ-67RQXCK
order: b0u
links:
  - type: verifies
    target: REQ-8K4Y908
    confirmed: ccffd7b9a5e5
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
