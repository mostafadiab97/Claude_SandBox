---
id: REQ-RY4TDX8
type: test-case
title: "Verify: Regulation loop validates user preferences"
status: Draft
priority: Low
owner: J. Müller
tags:
  - release-2.0
former-id: TC-BR99RE
parent: REQ-XGWSK2K
order: aj
links:
  - type: verifies
    target: REQ-055JC9M
    confirmed: ed6d4a00a62b
  - type: verifies
    target: REQ-WKYH3S2
    confirmed: 50e7f7afa151
---
**Objective:** verify that the regulation loop behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the regulation loop with default settings.
2. Limit the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
