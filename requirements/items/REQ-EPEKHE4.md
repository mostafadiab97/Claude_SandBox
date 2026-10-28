---
id: REQ-EPEKHE4
type: test-case
title: "Verify: Regulation loop measures safety limits"
status: Draft
priority: Low
owner: A. Hassan
former-id: TC-AZB5Q1
parent: REQ-XGWSK2K
order: aJ
links:
  - type: verifies
    target: REQ-WTBR2TG
    confirmed: 0af48dc95869
  - type: verifies
    target: REQ-FAJCE2B
    confirmed: 3d19be192f78
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Limit relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
