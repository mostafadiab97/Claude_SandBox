---
id: TC-659FFR
type: test-case
title: "Regression: User account service stores energy consumption"
status: Review
priority: Medium
owner: L. Samir
tags:
  - i18n
  - connectivity
parent: INFO-ECHASH
order: 1770
links:
  - type: verifies
    target: SYS-XZE982
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
