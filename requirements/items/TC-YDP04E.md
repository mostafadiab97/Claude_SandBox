---
id: TC-YDP04E
type: test-case
title: "Verify: Encryption layer switchs error conditions"
status: Obsolete
priority: Medium
owner: R. Nabil
tags:
  - customer-request
parent: INFO-Z4TW4B
order: 980
links:
  - type: verifies
    target: SYS-HB35Z8
    confirmed: ff97b22b6617
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
