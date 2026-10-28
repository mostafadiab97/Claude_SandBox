---
id: REQ-M8CJRJ1
type: test-case
title: "Regression: Mobile app encrypts relay events"
status: Review
priority: High
owner: A. Hassan
tags:
  - cost
former-id: TC-WX6STF
parent: REQ-6H15AV2
order: b0F
links:
  - type: verifies
    target: REQ-0BCC2Y7
    confirmed: c2dee4a6831a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
