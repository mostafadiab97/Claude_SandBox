---
id: REQ-11BE4JZ
type: test-case
title: "Regression: Menu system measures firmware images"
status: Approved
owner: J. Müller
tags:
  - EMC
  - accessibility
former-id: TC-380EB2
parent: REQ-6H15AV2
order: as
links:
  - type: verifies
    target: REQ-XWFNNXT
    confirmed: a080ef16fc5e
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
