---
id: REQ-4G0D34X
type: test-case
title: "Verify: Zone valve displays firmware images"
status: Draft
priority: High
owner: S. Adel
tags:
  - cost
former-id: TC-K3H1FQ
parent: REQ-XGWSK2K
order: ay
links:
  - type: verifies
    target: REQ-Z5ZXT27
    confirmed: 039687c494cb
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Display the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
