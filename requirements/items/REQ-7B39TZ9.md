---
id: REQ-7B39TZ9
type: test-case
title: "Verify: Zone valve calibrates relay events"
status: Obsolete
priority: Medium
owner: S. Adel
former-id: TC-KGPGWV
parent: REQ-XGWSK2K
order: a6
links:
  - type: verifies
    target: REQ-98JGE89
    confirmed: bba9c1adc60e
  - type: verifies
    target: REQ-A2DSQ6Q
    confirmed: a13f7b1862ac
---
**Objective:** verify that the zone valve behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the zone valve with default settings.
2. Validate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
