---
id: REQ-EGPCCBX
type: test-case
title: "Verify: Boiler interface validates relay events"
status: Obsolete
priority: Medium
owner: J. Müller
former-id: TC-FCJMXF
parent: REQ-XGWSK2K
order: b0S
links:
  - type: verifies
    target: REQ-QT5K7YB
    confirmed: 6a7a9fdc0288
  - type: verifies
    target: REQ-A2DSQ6Q
    confirmed: a13f7b1862ac
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Limit relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
