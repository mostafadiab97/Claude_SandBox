---
id: REQ-8HSS5BH
type: test-case
title: "Verify: Battery backup measures the operating mode"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - i18n
  - EMC
  - security
former-id: TC-K3XVWW
parent: REQ-F9Z1FYS
order: a6
links:
  - type: verifies
    target: REQ-TA12WYD
    confirmed: c37aca9c7e04
  - type: verifies
    target: REQ-AZWAQ09
    confirmed: 86f3854ab240
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Restore humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
