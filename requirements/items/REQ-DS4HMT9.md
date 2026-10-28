---
id: REQ-DS4HMT9
type: test-case
title: "Verify: Relay board reports user preferences"
status: Draft
priority: Medium
owner: H. Mostafa
former-id: TC-05EA1D
parent: REQ-F9Z1FYS
order: a5
links:
  - type: verifies
    target: REQ-H1CFNB4
    confirmed: c1fda425d923
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
