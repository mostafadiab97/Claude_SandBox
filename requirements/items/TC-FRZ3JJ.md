---
id: TC-FRZ3JJ
type: test-case
title: "Verify: Mobile app stores humidity values"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - performance
  - EMC
  - ux
parent: INFO-J0FETE
order: 430
links:
  - type: verifies
    target: SYS-ZM1TJV
  - type: verifies
    target: SW-3Z17MT
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
