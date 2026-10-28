---
id: REQ-ERC43BQ
type: test-case
title: "Verify: Cloud backend detects audit records"
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - performance
  - i18n
former-id: TC-ABMBMF
parent: REQ-8351896
order: b03
links:
  - type: verifies
    target: REQ-5FT15N5
    confirmed: 63e961a2987d
  - type: verifies
    target: REQ-748P32A
    confirmed: 78f42f77ff9a
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
