---
id: REQ-PT5SDRM
type: test-case
title: "Verify: Power supply restores humidity values"
status: Approved
priority: High
owner: S. Adel
tags:
  - accessibility
former-id: TC-KZZE4G
parent: REQ-F9Z1FYS
order: aq
links:
  - type: verifies
    target: REQ-TCRNYA1
    confirmed: 53eb98981ee7
  - type: verifies
    target: REQ-0409MEV
    confirmed: 616347694a14
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
