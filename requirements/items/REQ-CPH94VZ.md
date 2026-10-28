---
id: REQ-CPH94VZ
type: test-case
title: "Verify: Zone valve displays the operating mode"
status: Draft
priority: High
owner: R. Nabil
tags:
  - security
  - cost
former-id: TC-M6DJ1Z
parent: REQ-XGWSK2K
order: ah
links:
  - type: verifies
    target: REQ-7638CXD
    confirmed: c8c012d7096b
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Calibrate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
