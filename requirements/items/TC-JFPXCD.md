---
id: TC-JFPXCD
type: test-case
title: "Verify: Secure boot authenticates the set point"
status: Draft
owner: M. Farouk
tags:
  - safety
parent: INFO-Z4TW4B
order: 630
links:
  - type: verifies
    target: SYS-RZ204B
    confirmed: a414dd799ef0
  - type: verifies
    target: SW-BS2GHY
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
