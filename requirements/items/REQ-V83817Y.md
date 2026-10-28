---
id: TC-A1BH68
type: test-case
title: "Verify: Pairing process reports the room temperature"
status: Approved
tags:
  - security
parent: INFO-F0M7VC
order: 1180
links:
  - type: verifies
    target: SYS-4JFYE9
    confirmed: 71656e024c3b
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Authenticate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
