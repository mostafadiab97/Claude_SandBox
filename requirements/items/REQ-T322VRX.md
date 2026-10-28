---
id: TC-AF5Q4Q
type: test-case
title: "Verify: Tamper detection displays error conditions"
status: Review
priority: High
owner: N. Kamal
tags:
  - EMC
  - cost
parent: INFO-Z4TW4B
order: 350
links:
  - type: verifies
    target: SYS-F7SWPF
    confirmed: 89bbd5dd030b
  - type: verifies
    target: SW-SKZG0A
    confirmed: ea742fa40ce3
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Switch error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
