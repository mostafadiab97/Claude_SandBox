---
id: TC-KS53QH
type: test-case
title: "Verify: User account service stores energy consumption"
status: Approved
owner: É. Laurent
tags:
  - power
  - accessibility
parent: INFO-7P4D8D
order: 720
links:
  - type: verifies
    target: SYS-XZE982
    confirmed: bc880bb42e39
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
