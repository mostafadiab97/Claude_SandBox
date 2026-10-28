---
id: REQ-QFHRY0X
type: test-case
title: "Verify: Status LED calibrates firmware images"
status: Draft
priority: Low
owner: É. Laurent
tags:
  - ux
former-id: TC-QKQY5N
parent: REQ-Y9VHHKA
order: b0S
links:
  - type: verifies
    target: REQ-AYKW2SY
    confirmed: 909e2792e686
  - type: verifies
    target: REQ-W8W3BM0
    confirmed: 6fff5afcb2fa
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Store firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
