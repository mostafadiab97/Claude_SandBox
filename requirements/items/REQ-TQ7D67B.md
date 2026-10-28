---
id: REQ-TQ7D67B
type: test-case
title: "Verify: Local API stores the connection state"
status: Approved
owner: L. Samir
former-id: TC-5DJV59
parent: REQ-67RQXCK
order: b0b
links:
  - type: verifies
    target: REQ-6Y7ZTW0
    confirmed: cd27f13dbcce
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Display the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
