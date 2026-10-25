---
id: TC-FMZ4VH
type: test-case
title: "Verify: User account service detects user preferences"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-7P4D8D
order: 270
links:
  - type: verifies
    target: SYS-94CAYR
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
