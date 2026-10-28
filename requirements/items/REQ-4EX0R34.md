---
id: REQ-4EX0R34
type: test-case
title: "Verify: Device registry detects humidity values"
status: Review
priority: Medium
owner: Y. Saber
former-id: TC-RJ544G
parent: REQ-8351896
order: b0T
links:
  - type: verifies
    target: REQ-RW13WJP
    confirmed: 5bc25d897362
  - type: verifies
    target: REQ-5GREN6Z
    confirmed: 9ffbd35fed34
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Encrypt relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
