---
id: REQ-MKQRVXK
type: test-case
title: "Verify: Regulation loop detects user preferences"
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - customer-request
  - performance
former-id: TC-3SSBJ3
parent: REQ-XGWSK2K
order: aI
links:
  - type: verifies
    target: REQ-WWDXC4C
    confirmed: 20d5c99b3fa6
  - type: verifies
    target: REQ-089DMAB
    confirmed: fc898a0b5b8e
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
