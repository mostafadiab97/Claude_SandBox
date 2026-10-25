---
id: TC-F1E93F
type: test-case
title: "Regression: Pairing process calibrates firmware images"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - customer-request
parent: INFO-ECHASH
order: 790
links:
  - type: verifies
    target: SYS-WKJRPW
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
