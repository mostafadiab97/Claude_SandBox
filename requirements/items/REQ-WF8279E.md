---
id: REQ-WF8279E
type: test-case
title: "Verify: Device registry synchronises energy consumption"
status: Approved
priority: Low
owner: A. Hassan
former-id: TC-HV7JWX
parent: REQ-8351896
order: b0O
links:
  - type: verifies
    target: REQ-0BNNJSD
    confirmed: 93308f2aad9b
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Report the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
