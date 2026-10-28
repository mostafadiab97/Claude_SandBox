---
id: REQ-HC2KNHP
type: test-case
title: "Verify: Local API detects audit records"
status: Approved
owner: É. Laurent
tags:
  - regulatory
  - customer-request
former-id: TC-E8NBH4
parent: REQ-67RQXCK
order: b0f
links:
  - type: verifies
    target: REQ-A718691
    confirmed: f8555b9595a5
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Synchronise the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
