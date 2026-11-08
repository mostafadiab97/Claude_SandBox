---
id: REQ-P8EP42A
type: test-case
title: "Verify: Secure boot limits schedule entries"
status: Obsolete
priority: High
owner: R. Nabil
former-id: TC-25HQND
parent: REQ-K6FGAY0
order: b01
links:
  - type: verifies
    target: REQ-0AC6NR8
    confirmed: 74460965be9f
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
