---
id: TC-W6AQHZ
type: test-case
title: "Verify: Secure boot restores the set point"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - i18n
  - release-1.0
  - regulatory
parent: INFO-Z4TW4B
order: 1390
links:
  - type: verifies
    target: SYS-V5VS4J
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
