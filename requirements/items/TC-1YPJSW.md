---
id: TC-1YPJSW
type: test-case
title: "Verify: Login screen encrypts error conditions"
status: Draft
owner: Y. Saber
tags:
  - release-2.0
  - i18n
parent: INFO-J0FETE
order: 150
links:
  - type: verifies
    target: SYS-2Y9FGT
  - type: verifies
    target: SW-CGSC6B
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
