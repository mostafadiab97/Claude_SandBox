---
id: REQ-ENCBK4S
type: test-case
title: "Verify: Bluetooth LE link notifys the set point"
status: Obsolete
priority: High
owner: K. Tanaka
tags:
  - safety
former-id: TC-7A2HKN
parent: REQ-67RQXCK
order: b0N
links:
  - type: verifies
    target: REQ-4VK134D
    confirmed: 3502cbffc9ec
  - type: verifies
    target: REQ-6HYHTXA
    confirmed: 879f9929e26b
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
