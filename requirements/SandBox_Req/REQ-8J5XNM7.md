---
id: REQ-8J5XNM7
type: test-case
title: "Verify: Battery backup measures the connection state"
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - EMC
former-id: TC-ZDQHRP
parent: REQ-F9Z1FYS
order: b1h
links:
  - type: verifies
    target: REQ-MDST6CM
    confirmed: 545a69781e80
  - type: verifies
    target: REQ-JFZCMPM
    confirmed: 2dee49b460da
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
