---
id: REQ-EBMXKQY
type: test-case
title: "Verify: Touch display displays access tokens"
status: Approved
priority: Medium
owner: Y. Saber
former-id: TC-3WRYSW
parent: REQ-Y9VHHKA
order: al
links:
  - type: verifies
    target: REQ-5NHNVG1
    confirmed: 7956526ae9f5
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
