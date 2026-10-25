---
id: TC-ED0HAX
type: test-case
title: "Verify: Pairing process encrypts relay events"
status: Obsolete
priority: Medium
owner: محمد علي
parent: INFO-F0M7VC
order: 460
links:
  - type: verifies
    target: SYS-JF3REC
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
