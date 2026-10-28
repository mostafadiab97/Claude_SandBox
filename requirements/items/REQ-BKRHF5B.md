---
id: TC-E6K33Z
type: test-case
title: "Verify: Pairing process switchs sensor readings"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-F0M7VC
order: 700
links:
  - type: verifies
    target: SYS-96CWW2
    confirmed: e023ac8016f0
  - type: verifies
    target: SW-9338A3
    confirmed: e7cbb10f2f38
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
