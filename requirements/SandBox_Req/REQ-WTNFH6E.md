---
id: REQ-WTNFH6E
type: test-case
title: "Verify: Local API synchronises access tokens"
status: Obsolete
priority: High
owner: A. Hassan
former-id: TC-8J0JSN
parent: REQ-67RQXCK
order: b09
links:
  - type: verifies
    target: REQ-WG3XYJ3
    confirmed: 4dae60ba5140
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Authenticate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
