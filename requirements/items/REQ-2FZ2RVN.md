---
id: REQ-2FZ2RVN
type: test-case
title: "Verify: Heating controller measures user preferences"
status: Review
owner: R. Nabil
tags:
  - customer-request
  - cost
former-id: TC-JR9A50
parent: REQ-XGWSK2K
order: b16
links:
  - type: verifies
    target: REQ-Q28YZDM
    confirmed: e34bdb6b99b2
  - type: verifies
    target: REQ-NW5RTYP
    confirmed: 82e0295a63ac
---
**Objective:** verify that the heating controller behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heating controller with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
