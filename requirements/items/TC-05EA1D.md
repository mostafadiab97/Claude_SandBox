---
id: TC-05EA1D
type: test-case
title: "Verify: Relay board reports user preferences"
status: Draft
priority: Medium
owner: H. Mostafa
parent: INFO-MACGC3
order: 60
links:
  - type: verifies
    target: SYS-BD00HF
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
