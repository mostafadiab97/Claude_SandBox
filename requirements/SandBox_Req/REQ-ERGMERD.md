---
id: REQ-ERGMERD
type: test-case
title: "Verify: Main PCB calibrates the room temperature"
status: Approved
priority: Low
former-id: TC-RNAN3V
parent: REQ-F9Z1FYS
order: aR
links:
  - type: verifies
    target: REQ-E7EV6P4
    confirmed: fd85d789dbcd
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
