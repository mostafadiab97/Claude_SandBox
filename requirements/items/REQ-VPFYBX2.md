---
id: TC-ZT703M
type: test-case
title: "Regression: Notification service stores access tokens"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - EMC
parent: INFO-ECHASH
order: 630
links:
  - type: verifies
    target: SYS-BS5G2C
    confirmed: 19954ae1e0af
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
