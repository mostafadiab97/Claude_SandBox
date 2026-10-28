---
id: REQ-AWMKEV4
type: test-case
title: "Verify: Zone valve calibrates sensor readings"
status: Approved
priority: High
owner: R. Nabil
tags:
  - cost
  - release-2.0
former-id: TC-HGS62V
parent: REQ-XGWSK2K
order: b1V
links:
  - type: verifies
    target: REQ-18EFAG8
    confirmed: 2c2479704519
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Restore the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
