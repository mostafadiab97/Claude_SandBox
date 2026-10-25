---
id: TC-5GCD7B
type: test-case
title: "Verify: OTA server encrypts sensor readings"
status: Draft
priority: Medium
parent: INFO-7P4D8D
order: 1620
links:
  - type: verifies
    target: SYS-A103QP
  - type: verifies
    target: SW-MWKQRR
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Switch schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
