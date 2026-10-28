---
id: REQ-FZV5VS5
type: test-case
title: "Verify: Cloud backend notifys the connection state"
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - performance
  - ux
  - regulatory
former-id: TC-CSPTCR
parent: REQ-8351896
order: b0x
links:
  - type: verifies
    target: REQ-MAGQ1BB
    confirmed: dd3e6f066e4e
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
