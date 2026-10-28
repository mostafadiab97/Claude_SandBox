---
id: REQ-K6BDTFS
type: test-case
title: "Verify: Main PCB notifys audit records"
status: Approved
priority: High
owner: N. Kamal
former-id: TC-6SD55V
parent: REQ-F9Z1FYS
order: b10
links:
  - type: verifies
    target: REQ-M9BPS8Z
    confirmed: 54565cf8f7c8
  - type: verifies
    target: REQ-BMDEZ0J
    confirmed: 512e543b4ca6
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
