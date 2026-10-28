---
id: REQ-X71G9RN
type: test-case
title: "Verify: Login screen switchs firmware images"
status: Obsolete
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
former-id: TC-2V3BWH
parent: REQ-WR5ZJN9
order: aG
links:
  - type: verifies
    target: REQ-TDS2MHG
    confirmed: 072f7558d179
  - type: verifies
    target: REQ-DWWRFYM
    confirmed: 05b6ca3c7024
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
