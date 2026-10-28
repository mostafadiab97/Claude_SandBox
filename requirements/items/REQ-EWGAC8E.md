---
id: REQ-EWGAC8E
type: test-case
title: "Verify: Wi-Fi module switchs audit records"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - release-2.0
former-id: TC-XJFQEV
parent: REQ-67RQXCK
order: b08
links:
  - type: verifies
    target: REQ-FSK3RQV
    confirmed: eb82d81a139b
  - type: verifies
    target: REQ-S3R9PG4
    confirmed: 6bafc433808a
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
