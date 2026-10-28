---
id: TC-7PR1Y2
type: test-case
title: "Verify: Secure boot limits safety limits"
status: Review
priority: Medium
owner: Y. Saber
parent: INFO-Z4TW4B
order: 230
links:
  - type: verifies
    target: SYS-HMK3XJ
    confirmed: 243ec13ec9e6
  - type: verifies
    target: SW-NA4WSY
    confirmed: bff4a0ed5836
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
