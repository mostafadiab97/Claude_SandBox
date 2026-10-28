---
id: TC-AZDHZP
type: test-case
title: "Verify: Login screen notifys the set point"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - release-2.0
parent: INFO-J0FETE
order: 800
links:
  - type: verifies
    target: SYS-KFH2GP
    confirmed: a8dcaf0bf6d6
  - type: verifies
    target: SW-6ZNEMR
    confirmed: 8cdaa51b3615
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Limit the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
