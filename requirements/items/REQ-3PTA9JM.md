---
id: REQ-3PTA9JM
type: test-case
title: "Regression: Zone valve calibrates relay events"
status: Review
priority: High
owner: S. Adel
former-id: TC-A61630
parent: REQ-6H15AV2
order: b0q
links:
  - type: verifies
    target: REQ-98JGE89
    confirmed: bba9c1adc60e
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
