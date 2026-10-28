---
id: REQ-KRAFWYQ
type: test-case
title: "Verify: User account service restores schedule entries"
status: Review
priority: High
owner: N. Kamal
tags:
  - power
former-id: TC-TPDENB
parent: REQ-8351896
order: b1Y
links:
  - type: verifies
    target: REQ-CES1JSE
    confirmed: c95413eef36f
  - type: verifies
    target: REQ-YGF56RH
    confirmed: 7c536d464892
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
