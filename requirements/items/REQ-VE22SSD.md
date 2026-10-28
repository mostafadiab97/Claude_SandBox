---
id: REQ-VE22SSD
type: test-case
title: "Verify: Heat pump driver encrypts user preferences"
status: Review
priority: High
owner: Y. Saber
former-id: TC-YRTXQX
parent: REQ-XGWSK2K
order: b03
links:
  - type: verifies
    target: REQ-SWQXV55
    confirmed: 93824c965ccd
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
