---
id: REQ-Y1JWWZS
type: test-case
title: "Verify: Wi-Fi module displays sensor readings"
status: Draft
priority: High
former-id: TC-GHHSJJ
parent: REQ-67RQXCK
order: ax
links:
  - type: verifies
    target: REQ-7BH6AP4
    confirmed: d352273ada77
  - type: verifies
    target: REQ-VQKFAS9
    confirmed: a5bfa0077b08
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Calibrate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
