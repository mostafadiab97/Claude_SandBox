---
id: REQ-70YGBDA
type: test-case
title: "Verify: Cloud backend authenticates access tokens"
status: Draft
priority: High
owner: S. Adel
tags:
  - release-2.0
  - safety
  - ux
former-id: TC-3A6ENJ
parent: REQ-8351896
order: b0P
links:
  - type: verifies
    target: REQ-2921YSS
    confirmed: 0da0bb7a7e52
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
