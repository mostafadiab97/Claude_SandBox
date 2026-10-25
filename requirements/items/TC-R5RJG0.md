---
id: TC-R5RJG0
type: test-case
title: "Verify: Secure boot restores access tokens"
status: Draft
priority: High
owner: K. Tanaka
tags:
  - connectivity
  - customer-request
  - release-2.0
parent: INFO-Z4TW4B
order: 1410
links:
  - type: verifies
    target: SYS-82XYZM
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
