---
id: REQ-6K86EAQ
type: test-case
title: "Verify: Secure boot displays safety limits"
status: Draft
priority: Medium
tags:
  - regulatory
  - release-1.0
  - performance
former-id: TC-4ABWFC
parent: REQ-K6FGAY0
order: b0q
links:
  - type: verifies
    target: REQ-H685WGE
    confirmed: ba8d79699d39
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
