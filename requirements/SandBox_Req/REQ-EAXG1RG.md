---
id: REQ-EAXG1RG
type: test-case
title: "Verify: Local API notifys the connection state"
status: Approved
priority: High
owner: R. Nabil
former-id: TC-810F06
parent: REQ-67RQXCK
order: aT
links:
  - type: verifies
    target: REQ-QFQR7WB
    confirmed: 6280da70f001
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
