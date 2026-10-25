---
id: TC-8ZKZ79
type: test-case
title: "Verify: Secure boot limits safety limits"
status: Approved
priority: Low
owner: محمد علي
parent: INFO-Z4TW4B
order: 910
links:
  - type: verifies
    target: SYS-1TC8XF
    confirmed: f8bd8f1b6b39
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Limit firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
