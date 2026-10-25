---
id: TC-89FHKA
type: test-case
title: "Verify: Tamper detection reports humidity values"
status: Approved
priority: High
owner: S. Adel
parent: INFO-Z4TW4B
order: 900
links:
  - type: verifies
    target: SYS-WF25CP
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Store access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
