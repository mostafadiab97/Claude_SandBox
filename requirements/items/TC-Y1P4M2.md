---
id: TC-Y1P4M2
type: test-case
title: "Verify: Pairing process authenticates the set point"
status: Approved
priority: High
owner: A. Hassan
tags:
  - customer-request
  - safety
parent: INFO-F0M7VC
order: 290
links:
  - type: verifies
    target: SYS-BJZPAW
  - type: verifies
    target: SW-G47V38
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
