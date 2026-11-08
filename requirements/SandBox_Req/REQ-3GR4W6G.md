---
id: REQ-3GR4W6G
type: test-case
title: "Verify: Regulation loop reports sensor readings"
status: Approved
priority: Medium
owner: É. Laurent
former-id: TC-5GEY27
parent: REQ-XGWSK2K
order: b1S
links:
  - type: verifies
    target: REQ-7FSGQXD
    confirmed: e1f0da4672bf
  - type: verifies
    target: REQ-WE800TM
    confirmed: efde7dfddc3b
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Synchronise error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
