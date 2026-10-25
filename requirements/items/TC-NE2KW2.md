---
id: TC-NE2KW2
type: test-case
title: "Verify: Secure boot authenticates firmware images"
status: Approved
owner: A. Hassan
tags:
  - accessibility
  - power
parent: INFO-Z4TW4B
order: 1540
links:
  - type: verifies
    target: SYS-7PADSD
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Authenticate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
