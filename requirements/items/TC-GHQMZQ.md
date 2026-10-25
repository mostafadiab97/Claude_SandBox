---
id: TC-GHQMZQ
type: test-case
title: "Verify: Power supply limits the set point"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - performance
  - release-2.0
  - security
parent: INFO-MACGC3
order: 380
links:
  - type: verifies
    target: SYS-Q1NDZA
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
