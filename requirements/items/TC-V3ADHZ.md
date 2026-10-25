---
id: TC-V3ADHZ
type: test-case
title: "Verify: Secure boot authenticates energy consumption"
status: Approved
priority: High
tags:
  - customer-request
parent: INFO-Z4TW4B
order: 940
links:
  - type: verifies
    target: SYS-HF856T
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
