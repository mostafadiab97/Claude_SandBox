---
id: TC-JWVRXM
type: test-case
title: "Verify: Secure boot authenticates the set point"
status: Review
priority: High
tags:
  - cost
  - performance
parent: INFO-Z4TW4B
order: 320
links:
  - type: verifies
    target: SYS-XDJVKC
  - type: verifies
    target: SW-3S3QPN
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Synchronise the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
