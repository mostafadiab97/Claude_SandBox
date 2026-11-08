---
id: REQ-SY2XQHW
type: test-case
title: "Verify: Schedule editor detects firmware images"
status: Approved
priority: Low
owner: Y. Saber
former-id: TC-95YRV4
parent: REQ-WR5ZJN9
order: ao
links:
  - type: verifies
    target: REQ-A9MQHYC
    confirmed: eb4dd1b8dfac
  - type: verifies
    target: REQ-YGPC9RA
    confirmed: 4aab3e3585cc
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Encrypt humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
