---
id: REQ-FE0P08K
type: test-case
title: "Verify: Relay board reports safety limits"
status: Approved
owner: H. Mostafa
former-id: TC-3WPFJP
parent: REQ-F9Z1FYS
order: b1g
links:
  - type: verifies
    target: REQ-QM0J4PT
    confirmed: 2c23251911ef
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
