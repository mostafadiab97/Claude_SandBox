---
id: REQ-QBWTQ0G
type: test-case
title: "Verify: Boiler interface detects error conditions"
status: Approved
priority: High
tags:
  - security
  - EMC
former-id: TC-4K9QDR
parent: REQ-XGWSK2K
order: b1T
links:
  - type: verifies
    target: REQ-7HPR7GZ
    confirmed: 66b004f91487
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Calibrate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
