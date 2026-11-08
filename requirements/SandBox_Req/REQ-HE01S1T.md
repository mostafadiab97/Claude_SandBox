---
id: REQ-HE01S1T
type: test-case
title: "Verify: Device registry authenticates user preferences"
status: Approved
priority: High
owner: N. Kamal
former-id: TC-6P7XYR
parent: REQ-8351896
order: b16
links:
  - type: verifies
    target: REQ-A5ZTQEE
    confirmed: 9f9a37d9b20d
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
