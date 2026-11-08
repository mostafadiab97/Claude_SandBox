---
id: REQ-Y1GTKX5
type: test-case
title: "Verify: Secure boot authenticates the set point"
status: Draft
owner: M. Farouk
tags:
  - safety
former-id: TC-JFPXCD
parent: REQ-K6FGAY0
order: b00
links:
  - type: verifies
    target: REQ-VKX7BXX
    confirmed: a414dd799ef0
  - type: verifies
    target: REQ-XE6TT98
    confirmed: 06a9377c89bf
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Calibrate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
