---
id: TC-A6HD1B
type: test-case
title: "Verify: Tamper detection restores the connection state"
status: Draft
priority: Low
owner: J. Müller
parent: INFO-Z4TW4B
order: 190
links:
  - type: verifies
    target: SYS-BQJJNH
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Limit firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
