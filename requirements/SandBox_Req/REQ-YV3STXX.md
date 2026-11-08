---
id: REQ-YV3STXX
type: test-case
title: "Verify: Cloud backend reports energy consumption"
status: Approved
priority: High
owner: R. Nabil
former-id: TC-99TDKT
parent: REQ-8351896
order: aA
links:
  - type: verifies
    target: REQ-JFKDB4C
    confirmed: d45a11dd5456
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
