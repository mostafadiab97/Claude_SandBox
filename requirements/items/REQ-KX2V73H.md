---
id: REQ-KX2V73H
type: test-case
title: "Verify: Bluetooth LE link encrypts audit records"
status: Obsolete
priority: Medium
owner: محمد علي
tags:
  - power
former-id: TC-82GTHA
parent: REQ-67RQXCK
order: b1P
links:
  - type: verifies
    target: REQ-FD54NF7
    confirmed: efddaa3f87b9
  - type: verifies
    target: REQ-HKD1P7N
    confirmed: 8731c78398b2
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
