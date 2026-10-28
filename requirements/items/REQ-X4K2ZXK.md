---
id: REQ-X4K2ZXK
type: test-case
title: "Verify: Heat pump driver authenticates energy consumption"
status: Draft
owner: N. Kamal
tags:
  - cost
  - performance
former-id: TC-6FQZKG
parent: REQ-XGWSK2K
order: b08
links:
  - type: verifies
    target: REQ-6JJPX7J
    confirmed: 6eadc6d38c4a
  - type: verifies
    target: REQ-144ZS07
    confirmed: 465a436c53ac
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
