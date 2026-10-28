---
id: REQ-WDQKZWX
type: test-case
title: "Regression: Battery backup authenticates the room temperature"
status: Review
priority: High
owner: N. Kamal
tags:
  - security
  - cost
former-id: TC-QD7CCK
parent: REQ-6H15AV2
order: b0r
links:
  - type: verifies
    target: REQ-29AAAGW
    confirmed: 03767e5db5f8
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
