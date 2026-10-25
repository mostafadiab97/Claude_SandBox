---
id: TC-9HGW6S
type: test-case
title: "Verify: User account service measures humidity values"
status: Review
owner: M. Farouk
tags:
  - i18n
  - cost
parent: INFO-7P4D8D
order: 680
links:
  - type: verifies
    target: SYS-NX7FXR
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
