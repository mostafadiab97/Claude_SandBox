---
id: REQ-FSMD0CC
type: test-case
title: "Verify: Secure boot notifys user preferences"
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - regulatory
  - release-1.0
former-id: TC-SRPY18
parent: REQ-K6FGAY0
order: b0g
links:
  - type: verifies
    target: REQ-4YFGPPR
    confirmed: 102a3545c778
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
