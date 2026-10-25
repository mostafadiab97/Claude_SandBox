---
id: TC-PSQ7F2
type: test-case
title: "Verify: Secure boot synchronises audit records"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - release-2.0
  - accessibility
parent: INFO-Z4TW4B
order: 1480
links:
  - type: verifies
    target: SYS-PG0K3E
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
