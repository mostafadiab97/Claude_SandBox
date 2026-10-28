---
id: REQ-CE2DRSP
type: test-case
title: "Regression: Bluetooth LE link reports sensor readings"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - security
  - i18n
former-id: TC-2M3NM4
parent: REQ-6H15AV2
order: b1n
links:
  - type: verifies
    target: REQ-84ZV56S
    confirmed: ff918beefe64
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
