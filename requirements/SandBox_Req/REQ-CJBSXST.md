---
id: REQ-CJBSXST
type: test-case
title: "Verify: Regulation loop stores audit records"
status: Obsolete
priority: High
owner: S. Adel
former-id: TC-PSEKH5
parent: REQ-XGWSK2K
order: b0y
links:
  - type: verifies
    target: REQ-XTRE6E2
    confirmed: 51ad9fc7ce44
  - type: verifies
    target: REQ-G1N7WG2
    confirmed: 16e8b8a640dc
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
