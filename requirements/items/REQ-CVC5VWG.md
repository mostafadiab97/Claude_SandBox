---
id: REQ-CVC5VWG
type: test-case
title: "Verify: Heat pump driver displays the connection state"
status: Approved
priority: High
owner: S. Adel
tags:
  - release-1.0
  - cost
former-id: TC-BWTS02
parent: REQ-XGWSK2K
order: b1L
links:
  - type: verifies
    target: REQ-5ARG7AP
    confirmed: 3c95eb652d79
  - type: verifies
    target: REQ-27RKNKQ
    confirmed: a4cbb686541c
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Synchronise error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
