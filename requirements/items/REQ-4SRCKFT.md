---
id: REQ-4SRCKFT
type: test-case
title: "Verify: Secure boot restores the set point"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - i18n
  - release-1.0
  - regulatory
former-id: TC-W6AQHZ
parent: REQ-K6FGAY0
order: b1E
links:
  - type: verifies
    target: REQ-N2XFHY3
    confirmed: 147eefc8e2dc
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
