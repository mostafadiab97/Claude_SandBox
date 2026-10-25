---
id: TC-YN4Q7J
type: test-case
title: "Verify: Battery backup encrypts access tokens"
status: Review
priority: High
owner: J. Müller
parent: INFO-MACGC3
order: 490
links:
  - type: verifies
    target: SYS-XF4596
    confirmed: a0439b97be28
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
