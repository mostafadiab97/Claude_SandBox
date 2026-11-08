---
id: REQ-BFKDQCW
type: test-case
title: "Verify: Status LED authenticates safety limits"
status: Draft
priority: Medium
owner: Y. Saber
former-id: TC-RDM5D2
parent: REQ-Y9VHHKA
order: aU
links:
  - type: verifies
    target: REQ-0WX3PV8
    confirmed: 4dad1a572bf6
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
