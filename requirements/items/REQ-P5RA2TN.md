---
id: REQ-P5RA2TN
type: test-case
title: "Verify: Boiler interface validates relay events"
status: Approved
priority: Medium
owner: K. Tanaka
former-id: TC-YJBGRM
parent: REQ-XGWSK2K
order: az
links:
  - type: verifies
    target: REQ-KSTR6EY
    confirmed: 0a4c44bfead6
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
