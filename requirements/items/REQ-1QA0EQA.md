---
id: REQ-1QA0EQA
type: test-case
title: "Verify: Status LED notifys schedule entries"
status: Approved
owner: R. Nabil
tags:
  - security
  - release-2.0
  - performance
former-id: TC-GJA61Q
parent: REQ-Y9VHHKA
order: an
links:
  - type: verifies
    target: REQ-Z7KQTPA
    confirmed: 09343cc43a29
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Display energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
