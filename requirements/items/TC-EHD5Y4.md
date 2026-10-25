---
id: TC-EHD5Y4
type: test-case
title: "Verify: Tamper detection authenticates user preferences"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-Z4TW4B
order: 130
links:
  - type: verifies
    target: SYS-95649D
    confirmed: 1d3bba17b129
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Report the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
