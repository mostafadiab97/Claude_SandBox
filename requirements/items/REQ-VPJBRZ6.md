---
id: REQ-VPJBRZ6
type: test-case
title: "Verify: Boiler interface encrypts the connection state"
status: Draft
priority: Medium
owner: محمد علي
tags:
  - cost
  - customer-request
  - EMC
former-id: TC-66PRNQ
parent: REQ-XGWSK2K
order: as
links:
  - type: verifies
    target: REQ-4F46C46
    confirmed: 37d7aaee7050
---
**Objective:** verify that the boiler interface behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the boiler interface with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
