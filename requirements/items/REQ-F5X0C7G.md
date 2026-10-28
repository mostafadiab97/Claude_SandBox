---
id: REQ-F5X0C7G
type: test-case
title: "Verify: Enclosure encrypts the set point"
status: Obsolete
priority: High
tags:
  - EMC
  - customer-request
former-id: TC-SHD1XJ
parent: REQ-F9Z1FYS
order: b1X
links:
  - type: verifies
    target: REQ-QCZF6RT
    confirmed: c00525d9de09
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
