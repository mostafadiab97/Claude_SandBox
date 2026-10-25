---
id: TC-2TAQSH
type: test-case
title: "Verify: Local API validates the set point"
status: Approved
priority: High
owner: H. Mostafa
parent: INFO-F0M7VC
order: 730
links:
  - type: verifies
    target: SYS-HH08PK
    confirmed: "8228102962e4"
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
