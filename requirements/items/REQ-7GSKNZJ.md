---
id: REQ-7GSKNZJ
type: test-case
title: "Verify: User account service stores energy consumption"
status: Approved
owner: É. Laurent
tags:
  - power
  - accessibility
former-id: TC-KS53QH
parent: REQ-8351896
order: b09
links:
  - type: verifies
    target: REQ-QW1EM2B
    confirmed: bc880bb42e39
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
