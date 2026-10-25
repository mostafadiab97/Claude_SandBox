---
id: TC-ANN5KE
type: test-case
title: "Verify: Tamper detection encrypts relay events"
status: Draft
priority: Low
tags:
  - security
parent: INFO-Z4TW4B
order: 310
links:
  - type: verifies
    target: SYS-AN3CZW
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Detect energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
