---
id: REQ-P11YCKF
type: test-case
title: "Verify: Enclosure notifys access tokens"
status: Draft
priority: Medium
owner: R. Nabil
former-id: TC-8T29F9
parent: REQ-F9Z1FYS
order: b1J
links:
  - type: verifies
    target: REQ-9EQV92B
    confirmed: 0b7909b67648
  - type: verifies
    target: REQ-CSPBTT0
    confirmed: f300000fd52a
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
