---
id: REQ-4Z9ZXJM
type: test-case
title: "Verify: Status LED switchs sensor readings"
status: Review
priority: Medium
owner: K. Tanaka
former-id: TC-J2ZP0Y
parent: REQ-Y9VHHKA
order: aF
links:
  - type: verifies
    target: REQ-6PD797G
    confirmed: dcde66db1e30
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
