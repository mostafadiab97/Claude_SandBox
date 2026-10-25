---
id: TC-25HQND
type: test-case
title: "Verify: Secure boot limits schedule entries"
status: Obsolete
priority: High
owner: R. Nabil
parent: INFO-Z4TW4B
order: 640
links:
  - type: verifies
    target: SYS-E1XEK0
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Store user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
