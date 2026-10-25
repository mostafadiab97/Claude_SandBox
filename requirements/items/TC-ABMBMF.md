---
id: TC-ABMBMF
type: test-case
title: "Verify: Cloud backend detects audit records"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - performance
  - i18n
parent: INFO-7P4D8D
order: 660
links:
  - type: verifies
    target: SYS-1F54XW
  - type: verifies
    target: SW-YGN6FK
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
