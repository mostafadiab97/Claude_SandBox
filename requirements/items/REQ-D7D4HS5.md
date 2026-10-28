---
id: REQ-D7D4HS5
type: test-case
title: "Verify: Enclosure logs audit records"
status: Draft
priority: High
owner: R. Nabil
tags:
  - security
  - release-1.0
  - customer-request
former-id: TC-K6QBDM
parent: REQ-F9Z1FYS
order: ax
links:
  - type: verifies
    target: REQ-P550GQC
    confirmed: 81dfb0ea3083
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
