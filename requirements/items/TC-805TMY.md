---
id: TC-805TMY
type: test-case
title: "Verify: Login screen displays audit records"
status: Draft
priority: High
owner: S. Adel
parent: INFO-J0FETE
order: 1500
links:
  - type: verifies
    target: SYS-HPNQHQ
    confirmed: 4fe382f87558
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Restore the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
