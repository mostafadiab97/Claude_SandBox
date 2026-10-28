---
id: TC-JWG6R0
type: test-case
title: "Verify: Local API restores firmware images"
status: Approved
owner: Y. Saber
tags:
  - customer-request
  - release-1.0
  - release-2.0
parent: INFO-F0M7VC
order: 670
links:
  - type: verifies
    target: SYS-DNKAZZ
    confirmed: 22452286eeb7
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
