---
id: REQ-GD73AN0
type: test-case
title: "Verify: Touch display displays the connection state"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - security
  - ux
  - regulatory
former-id: TC-S92ETK
parent: REQ-Y9VHHKA
order: b0D
links:
  - type: verifies
    target: REQ-H1M276S
    confirmed: 072a30500dc2
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
