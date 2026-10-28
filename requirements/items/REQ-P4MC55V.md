---
id: REQ-P4MC55V
type: test-case
title: "Verify: Login screen validates sensor readings"
status: Obsolete
priority: Low
owner: N. Kamal
former-id: TC-V9KX95
parent: REQ-WR5ZJN9
order: b1M
links:
  - type: verifies
    target: REQ-KZTR45M
    confirmed: 84eef3783091
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
