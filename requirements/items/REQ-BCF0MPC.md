---
id: REQ-BCF0MPC
type: test-case
title: "Verify: Power supply stores energy consumption"
status: Approved
priority: Low
owner: L. Samir
tags:
  - release-2.0
  - power
former-id: TC-BVXQJV
parent: REQ-F9Z1FYS
order: ad
links:
  - type: verifies
    target: REQ-N1H5P0E
    confirmed: a7ba030d51de
  - type: verifies
    target: REQ-W0XSNQD
    confirmed: 926f921a05b5
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Detect access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
