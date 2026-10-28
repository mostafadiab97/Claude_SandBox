---
id: REQ-NQ4T4XT
type: test-case
title: "Verify: Mobile app restores humidity values"
status: Approved
owner: N. Kamal
tags:
  - regulatory
  - accessibility
  - safety
former-id: TC-4RGQHQ
parent: REQ-WR5ZJN9
order: b0T
links:
  - type: verifies
    target: REQ-GBSZ6MB
    confirmed: 2e87eec370fa
  - type: verifies
    target: REQ-3MNYEMC
    confirmed: 94ba9510fda2
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Calibrate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
