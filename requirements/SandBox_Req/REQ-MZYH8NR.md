---
id: REQ-MZYH8NR
type: test-case
title: "Verify: User account service calibrates error conditions"
status: Draft
owner: Y. Saber
tags:
  - i18n
former-id: TC-0E188T
parent: REQ-8351896
order: b10
links:
  - type: verifies
    target: REQ-4QRKTH2
    confirmed: 5128bf667abb
  - type: verifies
    target: REQ-CMXC7R6
    confirmed: c5b8f223d682
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Notify humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
