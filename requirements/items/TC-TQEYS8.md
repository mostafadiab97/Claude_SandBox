---
id: TC-TQEYS8
type: test-case
title: "Verify: Secure boot measures error conditions"
status: Draft
priority: High
owner: N. Kamal
tags:
  - safety
  - customer-request
parent: INFO-Z4TW4B
order: 1190
links:
  - type: verifies
    target: SYS-8T3EWK
  - type: verifies
    target: SW-G8JVAK
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
