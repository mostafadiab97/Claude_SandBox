---
id: REQ-YW76C0T
type: test-case
title: "Verify: Device registry stores audit records"
status: Obsolete
owner: N. Kamal
tags:
  - cost
  - release-1.0
former-id: TC-HFP8QD
parent: REQ-8351896
order: b0B
links:
  - type: verifies
    target: REQ-H1HVVK4
    confirmed: 76300eb27743
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
