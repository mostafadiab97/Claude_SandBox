---
id: REQ-VBHKGDC
type: test-case
title: "Verify: Tamper detection switchs access tokens"
status: Approved
priority: High
owner: S. Adel
tags:
  - customer-request
  - performance
former-id: TC-K0XDZW
parent: REQ-K6FGAY0
order: aW
links:
  - type: verifies
    target: REQ-JM876BB
    confirmed: f3e9ccc7a316
  - type: verifies
    target: REQ-M5X6C27
    confirmed: 5579dea52157
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
