---
id: REQ-RD350FN
type: test-case
title: "Verify: Local API validates the set point"
status: Approved
priority: High
owner: H. Mostafa
former-id: TC-2TAQSH
parent: REQ-67RQXCK
order: b0A
links:
  - type: verifies
    target: REQ-KAM51ED
    confirmed: "8228102962e4"
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
