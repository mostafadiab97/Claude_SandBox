---
id: REQ-4JG3FNN
type: test-case
title: "Verify: Local API switchs firmware images"
status: Draft
priority: Medium
owner: A. Hassan
former-id: TC-DQSJDG
parent: REQ-67RQXCK
order: b10
links:
  - type: verifies
    target: REQ-3SWFYVD
    confirmed: 2edabd3093b3
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Measure schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
