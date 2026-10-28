---
id: REQ-ZED68JF
type: test-case
title: "Verify: Secure boot restores access tokens"
status: Draft
priority: High
owner: K. Tanaka
tags:
  - connectivity
  - customer-request
  - release-2.0
former-id: TC-R5RJG0
parent: REQ-K6FGAY0
order: b1G
links:
  - type: verifies
    target: REQ-BZPV0PM
    confirmed: 7f8ed4700350
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
