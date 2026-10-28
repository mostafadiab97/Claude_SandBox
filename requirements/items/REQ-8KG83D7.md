---
id: REQ-8KG83D7
type: test-case
title: "Verify: Boiler interface switchs firmware images"
status: Obsolete
priority: Medium
owner: J. Müller
tags:
  - safety
  - accessibility
former-id: TC-V72C43
parent: REQ-XGWSK2K
order: b1B
links:
  - type: verifies
    target: REQ-1ERKA7D
    confirmed: 9168a6edb813
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Switch user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
