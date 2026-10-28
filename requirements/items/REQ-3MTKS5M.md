---
id: REQ-3MTKS5M
type: test-case
title: "Verify: Battery backup logs the operating mode"
status: Review
priority: High
owner: M. Farouk
former-id: TC-P345X4
parent: REQ-F9Z1FYS
order: b04
links:
  - type: verifies
    target: REQ-2ZWJ0AY
    confirmed: f7cbafb4c165
  - type: verifies
    target: REQ-0VHPMD0
    confirmed: c06850e126af
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
