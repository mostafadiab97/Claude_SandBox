---
id: REQ-ZTQPFDE
type: test-case
title: "Verify: Touch display reports humidity values"
status: Approved
priority: Medium
owner: J. Müller
tags:
  - release-2.0
  - cost
former-id: TC-VCJC3Q
parent: REQ-Y9VHHKA
order: ag
links:
  - type: verifies
    target: REQ-1FQWZ0W
    confirmed: 41b07dbfc705
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
