---
id: REQ-6Q6M5HS
type: test-case
title: "Verify: Local API displays schedule entries"
status: Approved
owner: A. Hassan
former-id: TC-HAATCF
parent: REQ-67RQXCK
order: aq
links:
  - type: verifies
    target: REQ-KPTHK4E
    confirmed: 7868d91ae4aa
  - type: verifies
    target: REQ-QSZFAF6
    confirmed: 2a159346ffb0
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Limit energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
