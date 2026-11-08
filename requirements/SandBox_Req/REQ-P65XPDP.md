---
id: REQ-P65XPDP
type: test-case
title: "Verify: Cloud backend limits safety limits"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - cost
  - performance
former-id: TC-91DX85
parent: REQ-8351896
order: b08
links:
  - type: verifies
    target: REQ-89HPNKM
    confirmed: 30d123440a38
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Restore humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
