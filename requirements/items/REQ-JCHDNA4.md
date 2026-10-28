---
id: TC-NPZZJW
type: test-case
title: "Verify: User account service measures schedule entries"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - accessibility
  - EMC
parent: INFO-7P4D8D
order: 830
links:
  - type: verifies
    target: SYS-NKN3QV
    confirmed: 2f2d653f73be
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
